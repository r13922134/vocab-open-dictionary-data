# 單字 App 開放字典資料

單字 App 字典中衍生自 CC BY-SA 4.0 資料的部分，依相同授權公開。

## 檔案

| 檔案 | 內容 | 筆數 |
|---|---|---|
| `cc-cedict-search-map.tsv` | 中文搜尋對照：中文詞 → 找到的英文單字，並標明繁體或簡體 | 185,223 |
| `word-ranks.tsv` | 單字的學習優先順序（數字越小越優先） | 56,993 |

兩個檔案都是 UTF-8、Tab 分隔，第一列是欄位名稱。

## 來源與修改

- **CC-CEDICT**，MDBG；源自 Paul Denisowski 於 1997 年發起的 CEDICT。CC BY-SA 4.0。
  <https://www.mdbg.net/chinese/dictionary?page=cedict>
  修改：只取中文詞與英文解釋的對應，篩出 App 字典裡有的英文單字，做成中文搜尋對照。
- **New General Service List（NGSL）**，Browne, C., Culligan, B., & Phillips, J.。CC BY-SA 4.0。
  <https://www.newgeneralservicelist.com/new-general-service-list>
  修改：只取單字排名，與 ECDICT 的詞頻排名合併，取較小（較優先）的值。
- **ECDICT**，Copyright (c) 2025 Linwei。MIT License。
  <https://github.com/skywind3000/ECDICT>
  `word-ranks.tsv` 含有它的詞頻排名，依 MIT 授權允許以 CC BY-SA 4.0 一併公開。

資料依原樣提供，不保證正確。

## 授權

本資料以 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 授權，全文見 `LICENSE`。
使用時請標示上列來源；改作後的資料也請以相同授權分享。

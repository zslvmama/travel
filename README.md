# zslvtravel 旅遊影片時序索引

[@zslvtravel](https://www.youtube.com/@zslvtravel) 頻道全部影片的時序索引頁（依標題前綴 date_token 倒排，可即時搜尋標題與日期）。

上線網址：https://zslvmama.github.io/travel/

由本機 pipeline 產生：`build_tsv.py`（重抓頻道 metadata → TSV）→ `build_index_html.py`（TSV → index.html）→ push 本 repo 觸發 GitHub Pages 部署。

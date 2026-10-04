# Japan_tsmc

四人東京旅行規劃，2027/1/10–1/16。靜態 HTML/CSS/JavaScript，Vercel 連接 GitHub main 自動部署。

想去清單、每日行程、住宿候選；免登入新增、修改、刪除，10 秒同步。
Supabase 專用 `japan_tsmc_items` 表，與既有旅行資料分開。客戶端僅使用 publishable key。
這是一份可公開讀寫的共用清單，不限制只有四人；不要存放個資、訂單或付款資料。
更新以 revision 比對防止同時修改蓋掉彼此內容。

本機預覽：`python3 -m http.server 8080`。

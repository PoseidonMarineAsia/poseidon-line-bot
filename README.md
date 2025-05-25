# Poseidon LINE Bot

這是一個基本的 LINE Bot 样板，使用 Flask 架構，可部署至 Render、Railway 等平台。

## 使用說明

1. 安裝依賴：
```
pip install -r requirements.txt
```

2. 建立 .env 檔案，填入您的 LINE 開發者密鑰。

3. 執行：
```
python app.py
```

4. 將 `/callback` 綁定至您的 LINE Webhook。

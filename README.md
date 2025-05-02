# 📱 SmartxOffice 功能展示

主導 SmartxOffice 的端到端開發，這是一款企業內部通訊應用，支援即時聊天、語音通話、公告發布、報表提交與流程審批功能。

---

## 🎥 比較有趣的功能展示

### 1. 展示 Tag User 功能
當使用者在輸入 @ 就會自動出現 tag 列表，這地方有趣的是當 tag 列表人員很多時，需要像 Telegram 一樣需要可以往上滑，然後在 tag 列表上方空白處還是可以操作到下方的畫面。
需要控制 `override func point(inside point: CGPoint, with event: UIEvent?) -> Bool` 就可完成類似效果。影片有順便展示一下顯示 log 小工具。  
📹 影片連結：https://youtube.com/shorts/4doc-yro3Qg?si=fXs53z0ksvoKnEoM

---

### 2. 展示網頁瀏覽功能
開啟網頁後當縮小需要在畫面上新增一個 icon 的進入點，供使用者點擊後繼續操作，像 Line 目前機制一樣。  
📹 影片連結：https://youtube.com/shorts/v8z9rdZCJow?si=RVSOXVkC8sJzv9qn

---

### 3. 展示多國語系，字體大小，主題色切換功能
📹 影片連結：https://youtube.com/shorts/64I8Cnaa5sw?si=cYLxfe07BTt_fUGd

---

### 4. 展示翻譯功能
跟 Telegram 呼叫 API 方式一樣，都是去呼叫 Google API，但是目前使用的方法是免費的，所以目前這個功能不需要額外費用。  
📹 影片連結：https://www.youtube.com/shorts/FiuaEm0Y1Fg

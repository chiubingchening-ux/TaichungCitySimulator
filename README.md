# 🚌 台中城市模擬器｜Taichung City Simulator

探索台中・體驗城市交通・打造你的模擬世界！

<p align="center">
  <a href="https://chiubingchening-ux.github.io/TaichungCitySimulator/">🌐 官方網站</a> |
  <a href="https://github.com/chiubingchening-ux/TaichungCitySimulator">💻 GitHub 專案</a>
</p>

---

## 📖 專案介紹

台中城市模擬器（Taichung City Simulator）是一個以台中城市、道路與公共交通為主題的網頁模擬專案。玩家可以透過瀏覽器進入不同版本，體驗城市模擬器的開發成果。

### 專案發展方向

- 🚌 公車與公共交通模擬
- 🛣️ 城市道路、街道與十字路口
- 🚏 公車站牌及乘客上下車
- 🚇 捷運與其他交通工具
- 🚗 車輛移動與自動駕駛
- 🚶 行人與城市生活情境
- 🤖 機器人控制及自動化操作
- 🎮 更流暢的遊戲介面
- 🔐 Google 帳號登入
- 💾 存檔與帳號系統的持續開發

以上為專案發展方向，實際功能依各版本的實作情況而定。

---

## 🌐 官方網站與原始碼

- **官方網站：** https://chiubingchening-ux.github.io/TaichungCitySimulator/
- **GitHub 專案：** https://github.com/chiubingchening-ux/TaichungCitySimulator

首頁採用單一 HTML 檔案設計。請以儲存庫目前實際設定的首頁檔名及 GitHub Pages 發布設定為準。

---

## 🎮 所有遊戲版本

> 注意：請確認每個版本的 HTML 檔案已上傳至 GitHub，且檔名與網址一致，才能正常開啟。以下列出目前已知版本；新版本請在確認檔案存在後再加入。

### 🧪 Beta 測試版

| 版本 | 類型 | 遊玩連結 |
|---|---|---|
| Beta V0.1 | 初期測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/Beta%20V0.1.html) |
| Beta V0.2 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV0.2.html) |
| Beta V0.3 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV0.3.html) |
| Beta V0.4 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV0.4.html) |
| Beta V1.0.1 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.1.html) |
| Beta V1.0.2 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.2.html) |
| Beta V1.0.3 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.3.html) |
| Beta V1.0.4 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.4.html) |
| Beta V1.0.5 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.5.html) |
| Beta V1.0.6 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.6.html) |

### ✅ Formal 正式版

| 版本 | 類型 | 遊玩連結 |
|---|---|---|
| Formal V1.0 | 正式版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/Formal%20V1.0.html) |

---

## 🧭 如何開始遊玩

1. 開啟[官方網站](https://chiubingchening-ux.github.io/TaichungCitySimulator/)。
2. 選擇想體驗的遊戲版本。
3. 等待網頁載入。
4. 依照遊戲畫面上的操作提示進行遊玩。
5. 如果遊戲沒有正常顯示，請重新整理頁面，或使用最新版 Chrome、Microsoft Edge 等瀏覽器。

---

## 🔐 帳號登入教學

帳號登入功能是否可用，依首頁目前的實作及 Firebase 設定而定。若登入功能已完成設定，可以依照以下步驟操作。

### 🟢 Google 帳號登入

1. 進入[官方網站](https://chiubingchening-ux.github.io/TaichungCitySimulator/)。
2. 點擊首頁的「帳號登入」或 Google 登入按鈕。
3. 選擇 Google 帳號，並依畫面提示完成授權。
4. 返回網站，確認登入狀態或使用者資訊。

### ❓ Google 登入失敗怎麼辦？

請檢查網路、Firebase Authentication 是否啟用 Google 登入、授權網域是否包含 `chiubingchening-ux.github.io`、Firebase SDK 設定是否正確，以及瀏覽器 Console 是否有錯誤訊息。

### 🔵 Facebook 登入

**目前 Facebook 登入尚未開放。** 完成 Meta 開發者應用程式、Facebook Login、Firebase Authentication 提供者、OAuth 重新導向網址及登入測試後，才應宣告功能正式開放。

---

## 🔥 Firebase 專案設定

本專案使用的 Firebase 網頁應用程式設定如下。這些值是前端應用程式識別設定，不能取代驗證流程或資料庫安全規則。

```javascript
const firebaseConfig = {
  apiKey: "AIzaSyBlYxCZpWEu1S2P3WwQ8I3P-iXeu7wCBZI",
  authDomain: "buses-throughout-taiwan.firebaseapp.com",
  projectId: "buses-throughout-taiwan",
  storageBucket: "buses-throughout-taiwan.firebasestorage.app",
  messagingSenderId: "808388458242",
  appId: "1:808388458242:web:1a4581107e41eab013b41b"
};
```

### Google 登入設定流程

1. 前往 [Firebase Console](https://console.firebase.google.com/)。
2. 選擇 `buses-throughout-taiwan` 專案。
3. 開啟 Authentication，進入登入提供者設定。
4. 啟用 Google 登入並儲存。
5. 在授權網域清單確認或加入 `chiubingchening-ux.github.io`。
6. 回到官方網站測試登入功能。

### Firebase 安全提醒

- 不要公開 Firebase 服務帳戶私密金鑰。
- 不要將 Facebook App Secret 寫進公開 HTML 或 JavaScript。
- 不要把使用者密碼寫進程式碼。
- 使用 Firestore 或 Realtime Database 時，請設定正確的安全規則。
- Firebase 網頁設定不能取代資料庫安全規則與權限驗證。

---

## 🕹️ 遊戲操作提示

不同版本的介面可能包含方向控制、暫停、鑰匙、廣播、機器人、行人、捷運或路線等圖示。

| 功能或圖示 | 操作提示 |
|---|---|
| 方向控制 | 依畫面提示確認可控制的方向 |
| 暫停按鈕 | 若版本支援，可用來暫停或恢復模擬 |
| 鑰匙圖示 | 依遊戲內說明確認用途 |
| 廣播圖示 | 確認是否與廣播或音效功能相關 |
| 機器人圖示 | 確認是否提供自動化控制 |
| 行人圖示 | 確認是否與行人模擬相關 |
| 捷運圖示 | 確認是否提供軌道交通功能 |
| 路線選單 | 選擇該版本實際提供的路線 |

實際操作方式以各版本中的說明為準。

---

## 📜 更新歷史（Changelog）

以下只整理目前已知的版本紀錄；尚未確認的功能差異不會寫成已完成項目。

- **Beta V0.1–V0.4：** 專案早期測試版本。
- **Formal V1.0：** 專案正式版入口。
- **Beta V1.0.1–V1.0.6：** 後續 Beta 測試版本。
- **其他版本：** 請在確認對應 HTML 檔案存在後加入列表。

### 未來版本更新格式

**版本：** Beta V1.0.7  
**更新日期：** YYYY-MM-DD

**新增功能**
- 填寫實際新增的功能。

**改善項目**
- 填寫實際改善的項目。

**修復問題**
- 填寫已修復的錯誤。

**已知問題**
- 填寫尚未解決的問題。

---

## 🧪 Beta 測試說明

Beta 版本可能包含尚未完成、不穩定或需要改善的功能。測試時可留意網頁載入、按鈕操作、車輛移動、道路與路口、站牌與乘客、自動駕駛、畫面流暢度，以及重新整理後是否仍能正常遊玩。

---

## 🐛 問題回報與功能建議

GitHub 專案：https://github.com/chiubingchening-ux/TaichungCitySimulator

回報時建議提供使用版本、問題描述及重現步驟、預期與實際結果、瀏覽器，以及截圖或錯誤訊息。請勿公開分享帳號密碼、私人資訊或秘密憑證。

---

## ❓ 常見問題（FAQ）

### Q1：遊戲需要下載嗎？
目前提供 GitHub Pages 網頁入口，可直接使用瀏覽器開啟。實際需求依各版本而定。

### Q2：為什麼某個版本打不開？
請確認 HTML 檔案已上傳、檔名與大小寫正確，而且 GitHub Pages 已完成部署。

### Q3：Beta 和 Formal V1.0 有什麼不同？
Formal V1.0 是正式版入口，Beta 是測試版入口。具體差異請以各版本的實際功能為準。

### Q4：不同版本的存檔會互通嗎？
目前不要假設不同版本共用同一份進度。是否支援存檔、匯入或匯出，需依實際功能確認。

### Q5：可以在手機上玩嗎？
可以嘗試使用手機瀏覽器開啟，但觸控操作與手機相容性依各版本設計而定。

---

## 🛠️ 專案檔案結構

以下為示意結構，實際檔案以 GitHub 儲存庫為準。

```text
TaichungCitySimulator/
├── index.html 或 web.html
├── Beta V0.1.html
├── BetaV0.2.html
├── BetaV0.3.html
├── BetaV0.4.html
├── Formal V1.0.html
├── BetaV1.0.1.html
├── BetaV1.0.2.html
├── BetaV1.0.3.html
├── BetaV1.0.4.html
├── BetaV1.0.5.html
├── BetaV1.0.6.html
└── README.md
```

### 發布新版本流程

1. 將新版 HTML 與所需資源上傳至 GitHub。
2. 確認檔名及網址完全一致。
3. 確認 GitHub Pages 部署成功。
4. 開啟網址測試。
5. 更新 README 版本列表與更新歷史。

---

## 🗺️ 未來發展方向

以下為規劃方向，並非已完成的功能清單：

- 擴展道路與十字路口。
- 改善公車路線與站牌停靠。
- 增加乘客上下車情境。
- 改善自動駕駛的路線判斷。
- 探索更多交通工具。
- 改善載入速度、畫面流暢度及手機相容性。
- 完善 Google 登入與帳號狀態管理。
- 完成 Facebook 登入設定後再正式開放。
- 持續整理版本入口及更新紀錄。

---

## 📄 授權與使用說明

程式碼、圖片、標誌及其他資源應依各自適用的授權與使用條款處理。如果儲存庫尚未提供 `LICENSE` 檔案，請勿假設所有內容都可以自由複製、修改或重新發布。

---

<p align="center">
  <strong>🚌 台中城市模擬器｜Taichung City Simulator</strong><br>
  探索城市、體驗交通、持續進化！
</p>

<p align="center">
  <a href="https://chiubingchening-ux.github.io/TaichungCitySimulator/">前往官方網站</a> |
  <a href="https://github.com/chiubingchening-ux/TaichungCitySimulator">查看 GitHub 專案</a>
</p>

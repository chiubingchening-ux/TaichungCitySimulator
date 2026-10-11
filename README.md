# 🚌 台中城市模擬器｜Taichung City Simulator

探索台中・體驗城市交通・打造你的模擬世界！

<p align="center">
  <a href="https://chiubingchening-ux.github.io/TaichungCitySimulator/web.html#top">🌐 官方網站</a> |
  <a href="https://github.com/chiubingchening-ux/TaichungCitySimulator">💻 GitHub 專案</a>
</p>

---

## 📖 專案介紹

台中城市模擬器（Taichung City Simulator）是一個以台中城市、道路與公共交通為主題的網頁模擬專案。

玩家可以透過瀏覽器進入不同版本，體驗城市模擬器的開發成果。

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

## 🌐 官方網站

**台中城市模擬器官方網站：**

https://chiubingchening-ux.github.io/TaichungCitySimulator/web.html#top

**GitHub 專案原始碼：**

https://github.com/chiubingchening-ux/TaichungCitySimulator

---

## 🎮 所有遊戲版本

| 版本 | 類型 | 遊玩連結 |
|---|---|---|
| Beta V0.1 | 初期測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/Beta%20V0.1.html) |
| Beta V0.2 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV0.2.html) |
| Beta V0.3 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV0.3.html) |
| Beta V0.4 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV0.4.html) |
| Formal V1.0 | 正式版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/Formal%20V1.0.html) |
| Beta V1.0.1 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.1.html) |
| Beta V1.0.2 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.2.html) |
| Beta V1.0.3 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.3.html) |
| Beta V1.0.4 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.4.html) |
| Beta V1.0.5 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.5.html) |
| Beta V1.0.6 | 測試版 | [立即遊玩](https://chiubingchening-ux.github.io/TaichungCitySimulator/BetaV1.0.6.html) |

> 注意：請確認每個版本的 HTML 檔案已上傳至 GitHub，且檔名與網址一致，才能正常開啟。

---

## 🧭 如何開始遊玩

1. 開啟[官方網站](https://chiubingchening-ux.github.io/TaichungCitySimulator/web.html#top)。
2. 選擇想體驗的遊戲版本。
3. 等待網頁載入。
4. 依照遊戲畫面上的操作提示進行遊玩。
5. 如果遊戲沒有正常顯示，請重新整理頁面，或使用最新版 Chrome、Microsoft Edge 等瀏覽器。

---

## 🔐 帳號登入教學

台中城市模擬器首頁提供帳號登入入口。若登入功能已完成設定，可以依照以下步驟操作。

### 🟢 Google 帳號登入

**步驟一：進入官方網站**

https://chiubingchening-ux.github.io/TaichungCitySimulator/web.html#top

**步驟二：點擊「帳號登入」**

在首頁找到「帳號登入」按鈕並點擊。

**步驟三：選擇 Google 登入**

點擊「使用 Google 帳號登入」。

**步驟四：選擇 Google 帳號**

在 Google 登入視窗中選擇要使用的帳號，並依畫面提示完成授權。

**步驟五：確認登入成功**

返回台中城市模擬器，確認網站是否顯示已登入狀態或使用者資訊。

### ❓ Google 登入失敗怎麼辦？

請依序檢查：

1. 網路連線是否正常。
2. Firebase Authentication 是否已啟用 Google 登入。
3. Firebase 的授權網域是否包含 `chiubingchening-ux.github.io`。
4. 網頁是否載入正確的 Firebase SDK 和專案設定。
5. 瀏覽器是否阻擋登入彈出視窗。
6. 瀏覽器開發者工具 Console 是否出現錯誤訊息。

如果仍然無法登入，請記錄錯誤訊息，以便進一步排查。

### 🔵 Facebook 登入

**目前 Facebook 登入尚未開放。**

Facebook 登入仍需要完成以下設定：

- 建立 Meta/Facebook 開發者應用程式。
- 設定 Facebook Login。
- 在 Firebase Authentication 啟用 Facebook 登入提供者。
- 設定 OAuth 重新導向網址。
- 完成應用程式設定與登入測試。

在上述工作完成前，Facebook 登入可能無法使用。功能正式開放後，請再更新此處的說明。

---

## 🔥 Firebase 專案設定

本專案使用的 Firebase 網頁應用程式設定如下：

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

**注意：** 這段程式碼只是 Firebase 專案設定，不會自動讓登入功能生效。網站仍需要載入 Firebase SDK、初始化 Firebase，並實作登入、登出及登入狀態處理。

### Google 登入設定流程

1. 前往 [Firebase Console](https://console.firebase.google.com/)。
2. 選擇 `buses-throughout-taiwan` 專案。
3. 開啟 Authentication。
4. 找到登入提供者設定。
5. 啟用 Google 登入並儲存。
6. 在授權網域清單確認或加入 `chiubingchening-ux.github.io`。
7. 回到官方網站測試登入功能。

### Firebase 安全提醒

- 不要公開 Firebase 服務帳戶私密金鑰。
- 不要將 Facebook App Secret 寫進公開 HTML 或 JavaScript。
- 不要把使用者密碼寫進程式碼。
- 如果使用 Firestore 或 Realtime Database，請設定正確的安全規則。
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

實際操作方式以各版本中的說明為準。若按鈕沒有反應，可能是功能尚未完成或程式發生錯誤。

---

## 📜 更新歷史（Changelog）

以下依照目前已知的版本順序整理。由於尚未取得每個版本完整的功能差異，因此不會將未確認的功能寫成已完成項目。

### Beta V0.1
- 專案早期測試版本。
- 作為初期開發與測試的版本節點。

### Beta V0.2
- 延續早期測試階段。
- 保留獨立版本入口。

### Beta V0.3
- 持續累積測試版本。
- 保留版本演進紀錄。

### Beta V0.4
- V0.x 系列的後續測試版本。
- 為後續 V1.0 版本階段保留版本紀錄。

### Formal V1.0
- 專案進入 V1.0 正式版階段。
- 提供獨立的正式版遊玩入口。

### Beta V1.0.1
- V1.0 之後的後續測試版本。
- 提供獨立的 Beta 測試入口。

### Beta V1.0.2
- 新增至版本列表。
- 實際功能差異待補充。

### Beta V1.0.3
- 新增至版本列表。
- 實際功能差異待補充。

### Beta V1.0.4
- 新增至版本列表。
- 實際功能差異待補充。

### Beta V1.0.5
- 新增至版本列表。
- 實際功能差異待補充。

### Beta V1.0.6
- 目前列出的較新 Beta 版本。
- 實際功能差異待補充。

### 📝 未來版本更新格式

發布新版本時，建議使用以下格式：

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

Beta 版本可能包含尚未完成、不穩定或需要改善的功能。

測試時可以留意：

- 網頁是否能正常載入。
- 按鈕是否能正常操作。
- 車輛是否能依預期移動。
- 車輛是否會卡在道路或路口。
- 站牌與乘客功能是否正常。
- 自動駕駛是否能正常執行。
- 畫面是否流暢。
- 重新整理後是否仍能正常遊玩。
- Google 登入是否能完成授權。

---

## 🐛 問題回報與功能建議

GitHub 專案：

https://github.com/chiubingchening-ux/TaichungCitySimulator

如果發現問題或有新功能建議，可以在專案頁面查看可用的回報方式。

回報時建議提供：

1. 使用版本，例如 Beta V1.0.4。
2. 問題描述。
3. 重現問題的操作步驟。
4. 預期結果。
5. 實際結果。
6. 使用的瀏覽器。
7. 截圖或錯誤訊息。

請勿公開分享帳號密碼、私人資訊或秘密憑證。

---

## ❓ 常見問題（FAQ）

### Q1：遊戲需要下載嗎？

目前提供 GitHub Pages 網頁入口，可以直接使用瀏覽器開啟。實際需求依各版本而定。

### Q2：為什麼某個版本打不開？

請確認 HTML 檔案已上傳、檔名與大小寫正確，而且 GitHub Pages 已完成部署。

### Q3：Beta 和 Formal V1.0 有什麼不同？

Formal V1.0 是正式版入口，Beta 是測試版入口。具體差異請以各版本的實際功能為準。

### Q4：Google 登入失敗怎麼辦？

請檢查 Firebase Authentication 是否啟用 Google 登入，以及授權網域是否正確。

### Q5：Facebook 登入為什麼不能用？

目前 Facebook 登入尚未開放，仍需要完成 Meta 與 Firebase 的設定及測試。

### Q6：不同版本的存檔會互通嗎？

目前不要假設不同版本共用同一份進度。是否支援存檔、匯入或匯出，需依實際功能確認。

### Q7：可以在手機上玩嗎？

可以嘗試使用手機瀏覽器開啟，但觸控操作與手機相容性依各版本設計而定。

---

## 🛠️ 專案檔案結構

以下是檔案整理的示意範例：

```text
TaichungCitySimulator/
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
├── web.html
└── README.md
```

這是示意結構，請依照實際儲存庫保留原有的 CSS、JavaScript、圖片及其他資源檔案。

### 發布新版本的流程

1. 將新版 HTML 與所需資源上傳至 GitHub。
2. 確認檔名及網址完全一致。
3. 確認 GitHub Pages 部署成功。
4. 在瀏覽器開啟網址進行測試。
5. 更新 README 的版本列表。
6. 在更新歷史記錄實際新增、改善及修復的內容。

---

## 🗺️ 未來發展方向

以下是可持續規劃的方向，並非已完成的功能清單：

- 擴展道路與十字路口。
- 改善公車路線與站牌停靠。
- 增加乘客上下車情境。
- 改善自動駕駛的路線判斷。
- 減少車輛卡住或異常移動的情況。
- 探索更多交通工具。
- 改善載入速度與畫面流暢度。
- 改善手機與電腦的相容性。
- 完善 Google 登入與帳號狀態管理。
- 完成 Facebook 登入設定後再正式開放。
- 持續整理版本入口及更新紀錄。

---

## 📄 授權與使用說明

程式碼、圖片、標誌及其他資源應依各自適用的授權與使用條款處理。

如果 GitHub 儲存庫尚未提供明確的 `LICENSE` 檔案，請勿直接假設所有內容都可以自由複製、修改或重新發布。

未來若要開放其他開發者共同開發，建議加入適合的授權檔案，並確認外部圖片、字型及其他資源的使用權限。

---

<p align="center">
  <strong>🚌 台中城市模擬器｜Taichung City Simulator</strong>
</p>

<p align="center">
  探索城市、體驗交通、持續進化！

  <br>

  <a href="https://chiubingchening-ux.github.io/TaichungCitySimulator/web.html#top">前往官方網站</a> |
  <a href="https://github.com/chiubingchening-ux/TaichungCitySimulator">查看 GitHub 專案</a>
</p>

# 競賽公告螢幕 v3.5（2026-11-04）

給學生看的教室公告螢幕，單一 HTML 檔，打開就能用。

使用方式的靈感來自 Classroomscreen 這類教室螢幕工具，但程式、版面與美術都是自行撰寫，沒有使用 Classroomscreen 的程式碼、圖片或素材。本專案與 Classroomscreen 沒有任何關係，也未獲其授權或贊助。

## 功能
- 小工具：文字、時程表、時鐘、計時器、倒數、碼錶、鬧鐘、間隔提醒（每 N 分鐘發光或跳出提示）、圖片、畫板，可拖曳、縮放、調字體大小
- 多畫面：新增、改名、排序、複製、刪除，← → 切換
- 定時：指定時間自動切換畫面、跳出公告、開始計時器；可自動輪播畫面
- 四種風格：黑板、軟木板、計分板、小島；多種背景、可上傳照片
- 字型：楷書、黑體、明體、手寫、圓體、注音楷書、注音手寫、注音圓體
- 匯出：目前畫面 PNG、全部設定 JSON；可匯入設定
- 預設：「把目前設定存為預設」「還原成預設」
- 內建範本：臺南市 115 年度國中小 Scratch 暨 AI 程式設計競賽（11/4 下午國小組）

## 使用
直接開啟 `index.html`（建議 Chrome）。開始前點「開聲音」，按 F 全螢幕，按 B 收起工具列。
設定存在瀏覽器裡；換電腦請用「風格 → 匯出全部設定 / 匯入設定」。

字型、圖示、PNG 匯出需要網路；沒網路時其他功能照常。

## 授權
本專案程式碼採用 [MIT 授權](LICENSE)：歡迎老師們自由使用、修改、分享，只要保留版權聲明即可。

## 第三方資源與授權
本專案只從 CDN 載入以下資源，沒有把它們的檔案放進 repo：

| 資源 | 用途 | 授權 |
|---|---|---|
| [Lucide](https://lucide.dev) 0.460.0 | 工具列圖示 | ISC（源自 Feather 的圖示為 MIT） |
| [html2canvas](https://html2canvas.hertzen.com) 1.4.1 | 匯出 PNG | MIT |
| Google Fonts：Noto Sans TC、Noto Serif TC、LXGW WenKai TC、Iansui、Huninn、Bpmf Iansui、Bpmf Huninn、Bpmf Zihi Kai Std、Caveat、Fredoka、Orbitron | 字型 | SIL Open Font License 1.1 |

「Classroomscreen」為其權利人所有之名稱，本文僅用於說明靈感來源。

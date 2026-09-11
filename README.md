# 賈承恩 Andy Chia

前端工程師（求職中）· 元智大學 資訊傳播學系

個性隨和、學習力強、邏輯思維清晰、擅長統籌規劃 —— 過去累積了跨部門溝通與專案規劃的經驗，目前專注深耕前端技術，正在尋找 Junior React 前端職缺。

📍 桃園市中壢區　·　📧 andychia0309@gmail.com

<div>
  <img src="https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-433E38?style=for-the-badge" />
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</div>

<hr>

## 🚀 代表作品

### PartyMatch — 共享訂閱媒合平台

[![CI](https://github.com/AndyChia0309/PartyMatch/actions/workflows/ci.yml/badge.svg)](https://github.com/AndyChia0309/PartyMatch/actions/workflows/ci.yml)

協助使用者找到願意一起分攤 Netflix、Spotify 等熱門訂閱服務的夥伴。整合找尋夥伴、申請審核、PM 幣代管交易、服務啟用與確認、續訂等完整流程，取代過往仰賴社群私訊與人工轉帳對帳的做法。

**[🔗 GitHub Repo](https://github.com/AndyChia0309/PartyMatch)** ・ **[🌐 線上 Demo](https://partymatch.ykk910309.workers.dev)**

| 首頁 | 探索群組 | 群組管理 | 訊息中心 |
|---|---|---|---|
| ![首頁](https://raw.githubusercontent.com/AndyChia0309/PartyMatch/dev/docs/images/screenshot-home.jpg) | ![探索群組](https://raw.githubusercontent.com/AndyChia0309/PartyMatch/dev/docs/images/screenshot-explore.jpg) | ![群組管理](https://raw.githubusercontent.com/AndyChia0309/PartyMatch/dev/docs/images/screenshot-manage-groups.jpg) | ![訊息中心](https://raw.githubusercontent.com/AndyChia0309/PartyMatch/dev/docs/images/screenshot-messages.jpg) |

**技術棧**：React 19、Vite、React Router v7、Zustand、Tailwind CSS v4　·　Node.js、Express、Prisma、MySQL、Redis　·　Cloudflare（Workers／R2）、Render

**工程亮點**
- **群組生命週期狀態機**：招募、額滿、填寫帳號資訊、啟用、確認期、續訂或結束，各階段可執行的操作皆由狀態決定
- **併發安全的名額搶佔**：最後一個名額同時被多筆申請核准是實際會發生的競態情境，核准流程以資料庫交易搭配條件式更新處理
- **PM 幣代管機制**：申請當下即先行扣款代管，須待服務啟用、成員完成確認後才會撥款；退出、移除、解散或申訴等情境各自對應不同的退款規則
- **敏感資料的分層防護**：共用帳密加密落地儲存、附件走短效簽章網址、群組與成員敏感欄位依角色動態遮罩
- **自動化測試與 CI**：前端 95 個、後端 179 個單元／整合測試，涵蓋核心頁面互動與完整群組生命週期（含真實併發衝突情境），皆整合進 GitHub Actions

<hr>

## 📫 聯絡我

- ✉️ Email：andychia0309@gmail.com
- 💻 GitHub：[@AndyChia0309](https://github.com/AndyChia0309)

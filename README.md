📖 專案簡介 (Overview)
ClearGrad 是一個解決大學生「畢業學分計算」痛點的 Web 應用程式。透過直覺的視覺化介面與自動化計算，協助學生追蹤必修、選修、通識（包含博雅向度）以及跨域/國際學習的修課進度。

本專案從純本地端工具，全面進化為**「離線優先 (Offline-First) 的雲端 SaaS 架構」**。結合 Google 帳號綁定、Firebase 雲端同步與嚴謹的隱私防護機制，讓使用者在跨裝置間享受無縫、安全且不中斷的排課體驗。本專案採用 GPL-3.0 開源授權，並結合人機協作（AI-Augmented Development）模式開發。

✨ 核心功能 (Key Features)
🎓 完整學分追蹤：支援系必修、選修、通識（D1-D6 向度）及體育學分自動統計，並整合複雜的跨領域學程規則，一鍵檢核畢業門檻。

📊 GPA 即時計算機：內建支援 4.30 制 GPA 即時試算。

☁️ 跨裝置雲端同步 (New)：整合 Google 登入，排課草案與設定檔自動備份至 Firebase 企業級資料庫，手機與電腦無縫接軌。

📶 離線優先架構 (Offline-First)：無網路環境依然可流暢排課。系統內建「同步錨點 (Sync Anchor)」與「衝突抉擇防護 (Conflict Resolution)」，網路恢復時自動比對時間戳記，徹底解決跨裝置資料覆蓋問題。

🔒 企業級隱私與資安 (GDPR Compliant)：

單次隱私同意閘門：首次啟用雲端功能前需取得授權。

本地端檔案隔離：使用者上傳的成績單等證明文件，僅加密存放於本地瀏覽器，絕不上傳雲端，極致保護隱私。

被遺忘權：內建一鍵「刪除雲端備份並登出」功能，使用者擁有資料絕對掌控權。

📱 響應式設計：完美支援手機與電腦版瀏覽。

🛠️ 技術架構 (Tech Stack)
Frontend: React, TypeScript, Tailwind CSS

Backend & BaaS: Google Firebase (Authentication, Firestore)

Architecture: Offline-First, Debounce Auto-Save, Conflict Resolution Matrix, Zero-Trust Security Rules

Development: AI-Assisted (Google Antigravity), GitHub Pages

Design: Custom UI/UX

⚖️ 授權 (License)
本專案採用 GNU General Public License v3.0 授權。
Copyright (c) 2026 CHUN CHUAN YEH
Created with ❤️ by CHUN CHUAN YEH

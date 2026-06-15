# 2026 暑期一對一配樂指導 — 報名頁

> 日日有樂 SunMoon Music 教學業務
> 部署網址：https://sunmoonmusicstudio-tsai.github.io/1on1-2026summer/

## 專案內容

四堂套裝一對一配樂指導招生頁面，2026 暑期（8/1–8/31）。

## 部署方式

GitHub Pages，root branch、根目錄。修改後直接 `git push`，1–2 分鐘自動上線。

## 對應的本機工作資料夾

- 文案編輯來源：`~/Desktop/Claude資料夾/03 教學事業/02 線上課程/260514_一對一配樂指導/`
- Google Sheet 文案編輯介面（同步）：[260615_一對一配樂指導_報名頁文案編輯](https://docs.google.com/spreadsheets/d/1F0zl7ySEC29B6umma46_5ViLhZiMumuuvTWRsSzZcTg/edit)

## 修改流程

1. 在 Google Sheet 上修改 C 欄文案
2. 請 Claude 讀取 Sheet 並回填本機 HTML
3. 把本機 HTML 同步覆蓋此 repo 的 `index.html`
4. `git commit` + `git push` → GitHub Pages 自動部署

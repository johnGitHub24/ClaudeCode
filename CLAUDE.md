# CLAUDE.md — 專案規範

## 專案目的

這是「Claude Code 快速學習指南」的原始碼，一個用繁體中文撰寫的互動式學習教材。

## 技術棧

- 純 HTML/CSS/JavaScript 單頁應用
- 無需任何框架（React、Vue 等）或建置工具（Webpack、Vite 等）
- 無外部 CDN 依賴，完全離線可用

## 檔案結構

```
ClaudeCode/
├── index.html        # 主要（也是唯一）的應用程式檔案
├── README.md         # 專案說明
├── CLAUDE.md         # 本檔案，給 Claude Code 的專案規範
├── .gitignore
└── docs/
    └── TIPS.md       # 15 大技巧標題清單
```

## 編碼規範

- 語言：繁體中文（所有文案、說明、註解）
- 縮排：2 空格
- 程式碼區塊：保持語法高亮樣式一致（使用現有 CSS class）
- 顏色主題：深色系，使用 CSS 變數定義，勿硬編碼顏色值

## 禁止行為

- 不引入外部 CDN 依賴（字體、圖示庫、JS 框架等）
- 不將單頁拆分為多個 HTML 檔案
- 不加入建置流程或 package.json
- 不修改現有 CSS 變數命名規則

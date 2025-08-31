# Python 程式初探 - 課程投影片 🐍

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)
[![Made with Slidev](https://img.shields.io/badge/Made%20with-Slidev-16a34a?style=for-the-badge&logo=slidev)](https://sli.dev/)
[![Vue 3](https://img.shields.io/badge/Vue-3-4FC08D?style=for-the-badge&logo=vue.js)](https://vuejs.org/)
[![pnpm](https://img.shields.io/badge/pnpm-8.x-f69220?style=for-the-badge&logo=pnpm)](https://pnpm.io/)

這是一份專為 Python 初學者設計的課程投影片，內容涵蓋了程式設計的核心基礎概念。專案使用現代化的投影片框架 [Slidev](https://sli.dev/) 製作，讓學習過程更具互動性與趣味性！🥳

## 📜 課程大綱

這份投影片將帶您走過以下幾個重要的學習階段：

*   **💻 電腦是如何運作的** (`pages/computer.md`)
*   **🤔 什麼是程式設計** (`pages/programming-intro.md`)
*   **🗣️ 程式語言介紹** (`pages/language-intro.md`)
*   **🚀 如何學習程式語言** (`pages/learning-language.md`)
*   **🎉 總結與回顧** (`pages/conclusion.md`)

## ✨ 技術堆疊與特色

這個專案採用了一系列現代化的工具與技術，打造出專業又活潑的簡報體驗：

*   **[Slidev](https://sli.dev/)**: 為開發者而生的投影片製作工具，使用 Markdown 即可快速撰寫。
*   **[Vue.js](https://vuejs.org/)**: 漸進式 JavaScript 框架，提供強大的元件化能力。
*   **`@cxphoenix/slidev-theme-fhsh-aisp`**: 一款充滿風格的客製化 Slidev 主題。
*   **`@cxphoenix/slidev-addon-python-runner`**: 超酷的插件！可以直接在投影片中執行 Python 程式碼。 🏃‍♂️
*   **`slidev-addon-tldraw`**: 可以在投影片上自由繪圖、標記重點的互動式白板工具。 🎨

## 🚀 快速開始

想在您的本機電腦上啟動這份投影片嗎？請跟著以下步驟：

### 1. 複製專案

```bash
git clone https://github.com/cxphoenix/py-course-introduction.git
cd py-course-introduction
```

### 2. 安裝相依套件

我們強烈推薦使用 `pnpm` 來管理套件，速度飛快！

```bash
# 推薦使用 pnpm
pnpm install
```

### 3. 啟動開發伺服器

```bash
pnpm dev
```

執行後，它會自動在瀏覽器中開啟 `http://localhost:3030`，您就可以看到即時預覽的投影片了！

## 📤 如何匯出

Slidev 支援將投影片匯出成多種格式，方便您離線分享：

```bash
# 匯出為 PDF 格式 (最常用)
pnpm export

# 匯出為一張張的 PNG 圖片
pnpm export --format png
```

匯出的檔案會儲存在 `dist/` 資料夾中。

## 📄 授權條款

本專案的內容採用 **姓名標示 4.0 國際 (CC BY 4.0)** 授權條款。歡迎您在標明出處的前提下，自由分享與改作！

---

**Made with ❤️ and Python**
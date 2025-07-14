# 全球漢字字典 Global Hanzi Dictionary

這是一個收錄全球漢字體系（簡體、繁體、日文漢字、韓國漢字、越南喃字等）的網頁字典平台。

## 📦 功能特色
- 支援多語言檢索（拼音、訓讀、Unicode、喃字等）
- 響應式網頁介面，行動裝置與桌面皆可用
- 可部署至 GitHub Pages 自動上線

## 🚀 部署方式（GitHub Pages）

1. 建立 GitHub 倉庫（推薦名稱：global-hanzi-dictionary）
2. 上傳本專案所有檔案
3. 在本機執行以下命令：

```bash
npm install
npm run deploy
```

完成後即可透過網址：`https://你的用戶名.github.io/global-hanzi-dictionary` 查看網站。

## 🧠 資料格式範例
```json
{
  "char": "愛",
  "simplified": "爱",
  "japanese": "愛",
  "korean": "애",
  "nom": ["𡢘"],
  "pinyin": "ài",
  "kunyomi": "あい",
  "meaning": "愛；情感",
  "unicode": "611B",
  "origin": ["中國", "日本", "越南"]
}
```

---

未來將支援自動匯入 Unicode CJK 擴展漢字、喃字典籍、GlyphWiki 字形資料等。

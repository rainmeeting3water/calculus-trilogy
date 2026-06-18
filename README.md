# 微積分三部曲互動教材

這是一套給高中生使用的微積分互動教材，使用純 HTML / CSS / JavaScript 製作，不依賴外部套件。

## 檔案結構

* index.html：首頁與學習路徑
* 01-definite-integral.html：定積分模組
* 02-indefinite-integral.html：不定積分模組
* 03-fundamental-theorem.html：微積分基本定理模組

## 學習路徑

### 第一站：定積分

核心概念：

* 小矩形近似
* 有向貢獻
* 黎曼和
* 帶符號面積
* 定積分基本性質

### 第二站：不定積分

核心概念：

* 從微分倒著走
* 反導函數
* 函數族 F(x)+C
* 常數 C 的意義
* 微分檢查

### 第三站：微積分基本定理

核心概念：

* 面積函數 A(x)=∫[a 到 x]f(t)dt
* 新增面積
* 平均高度
* A'(x)=f(x)
* ∫[a 到 b]f(x)dx=F(b)-F(a)

## 教學使用建議

建議使用順序：

1. 先用定積分模組建立「累積量」直觀。
2. 再用不定積分模組理解「反導函數族」。
3. 最後用微積分基本定理模組連接「累積量」與「反導函數」。

可分成三節課使用，也可以作為一個完整探究活動。

## 技術說明

* 純前端
* 不使用外部套件
* 不使用 MathJax
* 可直接用瀏覽器開啟
* 可部署到 GitHub Pages、Netlify 或其他靜態網站平台

## 注意事項

請不要將三個模組合併成同一個 HTML，避免發生：

* canvas id 重複
* JavaScript 函數名稱衝突
* CSS 互相污染
* 測驗 feedback id 衝突
* window.onload 互相覆蓋

本教材建議維持「三個模組獨立、首頁負責導覽」的架構。

## 雙語版本說明

本教材採用「中文主概念 + 英文數學詞彙輔助」的雙語呈現方式，目的不是完全替換成英文，而是協助學生建立中文概念與英文術語之間的連結。

英文用語優先採用 IBDP Mathematics、國際高中數學教材與英美數學課堂常見表達，例如 anti-derivative、anti-differentiation、family of curves、gradient、accumulation function 與 signed area。完整詞彙請參考 BILINGUAL_GLOSSARY.md。

## STEP 導學版

本專案除了完整互動版，也提供 STEP 導學版。STEP 導學版使用可展開式步驟，讓教師或學生依序完成：

- 學生任務 Student Task
- 教師提問 Teacher Prompt
- 觀察重點 Key Observation

此版本適合教師導學、學生自學、課堂探究與補救教學。

## 部署方式

### GitHub Pages

1. 建立一個 GitHub repository。
2. 將本資料夾內所有檔案上傳。
3. 到 Settings → Pages。
4. Source 選擇 main branch。
5. 儲存後等待 GitHub Pages 產生網址。
6. 開啟網址並按照 TESTING.md 檢查。

### Netlify

1. 登入 Netlify。
2. 選擇 Add new site。
3. 上傳整個 calculus-trilogy 資料夾。
4. 部署完成後開啟網站網址。
5. 按照 TESTING.md 檢查所有頁面與互動功能。

### 本機測試

可以直接用瀏覽器開啟 index.html。

若想使用本機伺服器，也可以在資料夾中執行：

```bash
python -m http.server 8000
```

然後開啟：

[http://localhost:8000](http://localhost:8000/)

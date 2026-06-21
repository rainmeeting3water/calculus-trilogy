# 測試清單

## 本次測試紀錄

- 測試日期：2026-06-20
- 測試方式：人工本機測試
- 本機網址：http://localhost:8000/
- 瀏覽器：待補
- 桌面視窗尺寸：待補
- 窄螢幕尺寸：約 375px
- 測試結果：目前未發現問題

## 本次已通過項目

- [x] 首頁
- [x] 三個完整互動頁
- [x] 三個 STEP 導學頁
- [x] 詞彙表／BILINGUAL_GLOSSARY 內容或連結
- [x] 所有導覽連結
- [x] 函數選單與滑桿
- [x] Canvas 圖形更新與數值卡
- [x] 動畫與動態表格
- [x] 測驗互動與回饋
- [x] 桌面版顯示
- [x] 約 375px 窄螢幕顯示
- [x] `a=b`
- [x] `a>b`
- [x] 跨越 x 軸
- [x] 正負抵消
- [x] 不同 `C` 值
- [x] `Δx` 縮小

## 未測或待確認

- [ ] `404.html` 實際顯示
- [ ] GitHub Pages 或 Netlify 首頁
- [ ] 部署後所有頁面與導覽連結
- [ ] 部署後手機瀏覽器顯示
- [ ] 部署環境是否可在無外部套件下完整運作

> **部署狀態：**部署後測試尚未執行。必須另行取得部署核准並完成部署後，才能勾選上述部署項目；目前不得宣稱已完成正式發布驗收。

## 檔案結構

* [x] index.html 存在
* [x] 01-definite-integral.html 存在
* [x] 02-indefinite-integral.html 存在
* [x] 03-fundamental-theorem.html 存在
* [ ] README.md 存在
* [ ] 404.html 存在
* [ ] .nojekyll 存在

## 首頁測試

* [x] index.html 可以正常開啟
* [x] 首頁三張卡片正常顯示
* [x] 「進入定積分模組」可連到 01-definite-integral.html
* [x] 「進入不定積分模組」可連到 02-indefinite-integral.html
* [x] 「進入微積分基本定理模組」可連到 03-fundamental-theorem.html
* [x] 手機版或窄螢幕時，三張卡片可正常直排

## 定積分模組測試

* [x] 01-definite-integral.html 可以正常開啟
* [x] 函數選擇可正常切換
* [x] a、b、n 滑桿可正常運作
* [x] 取樣方式可正常切換
* [x] canvas 圖形可正常更新
* [x] n 越來越大的表格可正常產生
* [x] 小測驗可正常回饋
* [x] 底部「返回首頁」可連到 index.html
* [x] 底部「下一站：不定積分」可連到 02-indefinite-integral.html

## 不定積分模組測試

* [x] 02-indefinite-integral.html 可以正常開啟
* [x] 函數選擇可正常切換
* [x] C 滑桿可正常運作
* [x] canvas 圖形可正常更新
* [x] 不同 C 值表格可正常顯示
* [x] 小測驗可正常回饋
* [x] 底部「上一站：定積分」可連到 01-definite-integral.html
* [x] 底部「返回首頁」可連到 index.html
* [x] 底部「下一站：微積分基本定理」可連到 03-fundamental-theorem.html

## 微積分基本定理模組測試

* [x] 03-fundamental-theorem.html 可以正常開啟
* [x] 函數選擇可正常切換
* [x] x 滑桿可正常運作
* [x] Δx 滑桿可正常運作
* [x] canvas 圖形可正常更新
* [x] 自動讓 Δx 越來越小的表格可正常產生
* [x] 小測驗可正常回饋
* [x] 底部「上一站：不定積分」可連到 02-indefinite-integral.html
* [x] 底部「返回首頁」可連到 index.html

## 部署後測試

* [ ] GitHub Pages 或 Netlify 首頁可正常開啟
* [ ] 所有模組連結在部署後仍正常
* [ ] 手機瀏覽器可正常閱讀
* [ ] 不需要外部套件即可運作

## 雙語版本測試

* [x] 首頁標題與三張卡片有中英並列
* [x] 三個模組的主要標題有中英並列
* [x] 操作區標籤仍清楚可讀
* [x] 英文不會擠壓滑桿、按鈕與 canvas
* [x] 手機版英文不會造成版面破裂
* [x] 測驗功能仍正常
* [x] 動態產生的表格與數據卡片仍正常顯示

## STEP 導學版測試

* [x] step/01-definite-integral-step.html 可以正常開啟
* [x] step/02-indefinite-integral-step.html 可以正常開啟
* [x] step/03-fundamental-theorem-step.html 可以正常開啟
* [x] 每個 STEP 可以展開與收合
* [x] STEP 頁面連回首頁正常
* [x] STEP 頁面連到完整互動版正常
* [x] STEP 頁面之間上一個／下一個連結正常
* [x] 手機版 STEP 卡片不會破版

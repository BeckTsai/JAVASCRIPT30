# 06 Fetch 結合 filter 實現迅速配對地名

## 步驟

1. 使用 Fetch（） 來取得資料，之後轉換成 json 檔儲存到 cities 得空陣列裡。
2. 將要 match（） 的值用 RegExp 儲存到常數裡，之後把輸入的文字與 cities 裡的資料做 match（）
3. 把篩選過的資料丟回頁面，並且替 match 過的資料夾加上 class 更換顏色。
4. 監聽 input 並執行 function。

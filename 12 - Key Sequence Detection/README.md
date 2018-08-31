# 12 key sequence Detection

## 步驟

1. 宣告 pressed 作為儲存 keyup 變數，secretCode 則可輸入要做為密碼的字串。
2. 監聽整個視窗的 keyup 事件，將 keyup 的值 push 到 pressed 陣列。
3. pressed 陣列長度與 secrtCode 必須一樣，用 splice 刪除多餘的值，最後將 pressed 轉回字串。
4. 用 includes 確認是否符合 secrtCode。

# 14 JavaScript References VS Copying

## 步驟

1. 原始型別。
2. 物件型別。
3. Call by value：原始型別都是 Call by value，當複製時不影響彼此。
4. Call by refrence:當物件型別被複製使用時，是會被彼此改變的。
5. 陣列的複製
   -Array.prototype.Slice()
   -Array.prototype.concat()
   -Spread syntax ES6 的 Spread 語法
   -Array.from()
6. 物件的複製
   -Object.assign()
7. JSON.parse \* JSON.stringify

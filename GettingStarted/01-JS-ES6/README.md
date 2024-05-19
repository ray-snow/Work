# JavaScript ES6

### var,let,const

var 定義變數作用域均會是global variable
let 定義變數作用域會是當前區塊
const 定義變數作用域會是當前區塊,且不能重新宣告、指定值

### 解構賦值 Destructuring assignment

可將array、Object中的資料解開擷取成為獨立變數

### 箭頭函式運算式（arrow function expression）
簡化function語法
與function差別，this會指向上層，故要用e.target

### Function Default

Function 中傳入的餐數可設定未傳入時的預設值

### 字串模板 string template
取代字串拼接的方式，且支援換行
`xxx${str}`

### ES Module
模組化，可將Function、變數等，模組化，透過import引入

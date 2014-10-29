title: 資訊創意課程 Javascript 01
author:
  name: 課程 FB 社團
  url: https://www.facebook.com/groups/348522108647062/
output: slide.html
controls: true

--

# Javascript
## 開始學習程式語言

--

# 使用這個工具
## 打開瀏覽器，前往我們的開發環境：
## http://repl.it/languages/JavaScript

--

# 使用這個工具
## 打開瀏覽器，前往我們的開發環境：
## http://repl.it/languages/JavaScript
## DEMO

--

# 有啥可以輸入？
## 來介紹幾個 JS 基本型態

--

### 數字

直接打

```
9
```

--

### 數字

直接打，有小數點也行

```
9.2
```

--

### 字串

可以是一個字，用 `'` 或者 `"` 包起來  
&nbsp;

```
'塊'
```

--

### 字串

可以是一個字，用 `'` 或者 `"` 包起來  
既然是字'串'，就可以有多個字

```
"塊陶啊"
```

--

# 來做點變化吧

## 對上面的基本型態做些運算
## 從四則運算開始

-- 

### 從四則運算開始

加法 `+`  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

```
100 + 20
```

得到 `120`

-- 

### 從四則運算開始

加法 `+`  
減法 `-`  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

```
100 + 20 - 10
```

得到 `110`

-- 

### 從四則運算開始

加法 `+`  
減法 `-`  
乘法 `*`  
&nbsp;  
&nbsp;  
&nbsp;  

```
100 + 20 - 10 * 7
```

得到 `50`

--

### 從四則運算開始

加法 `+`  
減法 `-`  
乘法 `*`  
除法 `/`  
&nbsp;  
&nbsp;  

```
100 + 20 - 10 * 6 / 2
```

得到 `90`

--

### 從四則運算開始

加法 `+`  
減法 `-`  
乘法 `*`  
除法 `/`  
括弧內的先算 `()`  
&nbsp;  

```
(100 + 20 - 10 * 6) / 2
```

得到 `30`

--

### 從四則運算開始

加法 `+`  
減法 `-`  
乘法 `*`  
除法 `/`  
括弧內的先算 `()`  
One more ... 取餘數 `%`

```
(100 + 20 - 10 * 6) / 2 % 11
```

得到 `8`

--

### 從四則運算開始

加法 `+`  
減法 `-`  
乘法 `*`  
除法 `/`  
括弧內的先算 `()`  
One more ... 取餘數 `%`

```
(100 + 20 - 10 * 6) / 2 % 11
```

得到 `8`

DEMO

--

# 字串相加
## 試著 `"大家好！" + "我是西瓜！"`

--

# 字串相加
## 試著 `"大家好！" + "我是西瓜！"`
## DEMO

--

# 第一個非運算指令
## 離開純運算式

--

<pre style="margin-top: 150px"><code style="font-size: 50px">console.log( 數值 )</code></pre>
## 把 `數值` 印出來！

--

<pre style="margin-top: 150px"><code style="font-size: 50px">console.log( 數值 )</code></pre>
## 把 `數值` 印出來！
## 和 `printf` 很相近

--

<pre style="margin-top: 150px"><code style="font-size: 50px">console.log( 數值 )</code></pre>
## 把 `數值` 印出來！
## 和 `printf` 很相近

> 接下來的多行程式就會漸漸用到了  

--

### 把他們印出來！

```
console.log( 56 )
```

```
console.log( "大家好！" )
```


--

### 把他們印出來！

```
console.log( 56 )
```

```
console.log( "大家好！" + "我要宣布！" )
```

--

### 把他們印出來！

```
console.log( 56 )
```

```
console.log( "大家好！" + "我要宣布！" )
```

```
console.log( ((100 + 20 - 10 * 6) / 2 % 11 * 10) )
```

--

### 把他們印出來！

```
console.log( 56 )
```

```
console.log( "大家好！" + "我要宣布！" )
```

```
console.log( "這學期的成績為：" + ((100 + 20 - 10 * 6) / 2 % 11 * 10))
```

--

### 把他們印出來！

```
console.log( 56 )
```

```
console.log( "大家好！" + "我要宣布！" )
```

```
console.log( "這學期的成績為：" + ((100 + 20 - 10 * 6) / 2 % 11 * 10))
```

DEMO

--

### 練習 & 休息時間
#### 程式碼練習 1
#### 題目：

小頭今天出門去早餐店買了一份蛋餅和一杯奶茶，蛋餅一份 25 元，奶茶一份 15 元，不過今天蛋餅打 8 折，於是小頭開心地買了早餐回家。請問小頭買早餐一共花了多少錢。(用程式印出計算式和答案)

--

# 接著要有多 個/行 指令了
## 使用左邊！
## 使用方法介紹 DEMO

--

# 變數
## 程式執行的過程中，暫時存放資料的地方

--

### Javascript 的變數宣告

 * 關鍵字：`var`

--

### Javascript 的變數宣告

 * 關鍵字：`var`

![varies](http://i.imgur.com/C3Iyj9c.png)

--

### Javascript 的變數宣告

 * 關鍵字：`var`

![varies](http://i.imgur.com/C3Iyj9c.png)  
![variable](http://i.imgur.com/pWNJDbp.png)

--

### Javascript 的變數宣告

 * 關鍵字：`var`
 * `var 變數名稱`

--

### Javascript 的變數宣告

 * 關鍵字：`var`
 * `var 變數名稱`

```
var name
var grade
```

--

# 空間出來了，
## 放東西進去才有用

--

### 空間出來了，放東西進去才有用

```
var name = "西瓜"
var grade = 3
```

--

### 空間出來了，放東西進去才有用

```
var name = "西瓜"
var grade = 3
```

 * `=` 的意思是把東西從右邊丟到左邊
 * 意思是使之相等，而不是數學的等於

--

### 空間出來了，放東西進去才有用

```
var name = "西瓜"
var grade = 3
```

 * `=` 的意思是把東西從右邊丟到左邊
 * 意思是使之相等，而不是數學的等於

```
name = "妹子"
```

 * 功能就是用來改變變數的值

--

### 空間出來了，放東西進去才有用

```
var name = "西瓜"
var grade = 3
```

 * `=` 的意思是把東西從右邊丟到左邊
 * 意思是使之相等，而不是數學的等於

```
name = "妹子"
```

 * 功能就是用來改變變數的值

DEMO

--

# 使用變數
## 把剛剛存進去的東西拿來使用
## 命名好的變數名稱即代表那個值

--

### 使用變數

```
console.log( name )
console.log( grade )
```

--

### 使用變數做運算

```
console.log( "我是" + name )
console.log( "我" + grade + "年級" )
```

--

### 使用變數做運算

```
console.log( "我是" + name )
console.log( "我" + grade + "年級" )

var decrease = 2;
console.log( "我被降了" + decrease + "級" )
grade = grade - decrease
console.log( "我" + grade + "年級" )
```

--

### 使用變數做運算

```
console.log( "我是" + name )
console.log( "我" + grade + "年級" )

var decrease = 2;
console.log( "我被降了" + decrease + "級" )
grade = grade - decrease
console.log( "我" + grade + "年級" )
```

DEMO

--

# 在變數上做運算

--

### 在變數上做運算

```
grade += 1
console.log( grade )

grade -= 1
console.log( grade )

grade *= 2
console.log( grade )

grade /= 2
console.log( grade )

name += "西瓜"
console.log( name )
```

--

### 在變數上做運算

```
grade += 1
console.log( grade )

grade -= 1
console.log( grade )

grade *= 2
console.log( grade )

grade /= 2
console.log( grade )

name += "西瓜"
console.log( name )
```

DEMO & 講解

--

### 在變數上做運算，更看不懂的寫法

```
grade ++
console.log( grade )

grade --
console.log( grade )
```

--

### 在變數上做運算，更看不懂的寫法

```
grade ++
console.log( grade )

grade --
console.log( grade )
```

就更簡短這樣，DEMO & 講解

--

### BTW

 * 這是動態語言，不需要先把型態說好，一個 `var` 通吃所有型態
 * 沒有 `var` 事先宣告也不會出錯，但可能出問題
 * 而且在 JS 中 `;` 分號是不見得必要的

> 大一的朋友請注意:  
> 系上教的Ｃ語言
> 字串要用 `"` 包，字元用 `'` 包  
> 而且要先宣告型態...  
> 並且每個敘述結束一定要`;`  
> `printf` 也要把型態搞清楚...  

--

# 程式常常不是只是要跑而已
## 讓別人看得懂也是很重要的

--

# 程式常常不是只是要跑而已
## 讓別人看得懂也是很重要的
## 剛剛那些運算如果我不講應該沒有人知道在幹嘛吧 (?)

--

<pre style="margin-top: 150px"><code style="font-size: 50px">// 我是註解，會被當成黑畫面跳過</code></pre>
## 可以放置一些非程式碼的東西在裡面

--

```
grade += 1
// grade = grade + 1

grade -= 1
// grade = grade - 1

grade *= 2
// grade = grade * 2

grade /= 2
// grade = grade / 2

name += "西瓜"
// name = name + "西瓜"
```

## 大概可以這樣用

--

```
grade += 1
// grade = grade + 1

grade -= 1
// grade = grade - 1

grade *= 2
// grade = grade * 2

grade /= 2
// grade = grade / 2

name += "西瓜"
// name = name + "西瓜"
```

## 大概可以這樣用
## DEMO

--

```
/* 
我是也是註解
你看不到我
你看不到我
你看不到我
你看不到我
你看不到我
你看不到我
你看不到我
你看不到我
你看不到我
 */
```

## 這種註解方式可以一次註解很多行

--

### 練習 & 休息時間
#### 程式碼練習 2 ，題目：

宣告一個變數，指定其初始值為 pomelo，並使用 console.log 印出以下圖案。

![Imgur](http://i.imgur.com/qvuId2O.png)  

--

### 練習 & 休息時間
#### 程式碼練習 3 ，題目：

請依照以下程式碼的指示在 [<kbd>repl.it</kbd>](http://repl.it/languages/JavaScript) 網站執行。

```
var a;
console.log('a = ' + a);

// Step 1: 複製這段程式碼到 repl.it
// Step 2: 執行這段程式碼
// Step 3: 直接在右側黑黑的視窗輸入 a = 10
// Step 4: 然後再執行一次這個程式碼
// Step 5: 直接在右側黑黑的視窗輸入 a = 'A plain text'
// Step 6: 在執行一次
```

--

### 練習 & 休息時間
#### 程式碼練習 4 ，題目：

定義兩個不同的變數 `a`、`b`，請寫一個程式，讓 `a`、`b` 的值互相交換。你的程式必須先印出 `a` 和 `b` 的資料，然後將 `a` 和 `b` 的資料進行交換，最後在印出一次 `a` 和 `b` 的資料。

--

### 其實還有一種每個語言都有的型態

--

### 其實還有一種每個語言都有的型態
![boolean](http://i.imgur.com/BBAZRvq.png)  

--

### 其實還有一種每個語言都有的型態

![boolean](http://i.imgur.com/BBAZRvq.png)  
 * 這種型態只有 `是` 和 `否` 兩種值
 * `true` or `false`

--

# 產生布林值

--

### 產生布林值

 * 請問 `689` 是否比 `609` 大？

--

### 產生布林值

 * 請問 `689` 是否比 `609` 大？
 * `689 > 609`

--

### 產生布林值

 * 請問 `689` 是否比 `609` 大？
 * `689 > 609` => `true`

--

### 產生布林值

 * 請問 `689` 是否比 `609` 大？
 * `689 > 609` => `true`
 * `>`, `<`, `>=`, `<=`, `==`,`!=`

--

### 產生布林值

 * 請問 `689` 是否比 `609` 大？
 * `689 > 609` => `true`
 * `>`, `<`, `>=`, `<=`, `==`,`!=`
 * 請問 `馬` 與 `鹿` 是否一樣？

--

### 產生布林值

 * 請問 `689` 是否比 `609` 大？
 * `689 > 609` => `true`
 * `>`, `<`, `>=`, `<=`, `==`,`!=`
 * 請問 `馬` 與 `鹿` 是否一樣？
 * `'馬' == "鹿"` => `false`, 電腦不會指鹿為馬的ㄎㄎ

--

# 布林可以幹麻？

--

# 布林可以幹麻？
## 常常拿來做流程控制，`if`, `else`...

--

### 基本流程控制

```
if(true){
    console.log("我會被顯示")
}
```

--

### 基本流程控制

```
if(false){
    console.log("我不會被顯示")
}
else{
    console.log("我才會被顯示")
}
```

--

# 產生布林值，並運用之

--

### 產生布林值，並運用之

 * 若 `689` 比 `609` 大，請說 `!!`，否則說 `??`

--

### 產生布林值，並運用之

 * 若 `689` 比 `609` 大，請說 `!!`，否則說 `??`

```
var b = 689, g = 609;
if(b > g)
    console.log("!!")
else
    console.log("??")
```

--

### 產生布林值，並運用之

 * 若 `馬` 與 `鹿` 一樣，請說 `指鹿為馬中...` ，否則說 `你很誠實`

--

### 產生布林值，並運用之

 * 若 `馬` 與 `鹿` 一樣，請說 `指鹿為馬中...` ，否則說 `你很誠實`

```
var h = '馬', d = "鹿";
if(h == d)
    console.log("指鹿為馬中...")
else
    console.log("你很誠實")
```

--

# 再用布林產生布林

--

# 再用布林產生布林
## `&&`, `||`
## `且`, `或`

--

### 再用布林產生布林

 * 語句話一點

--

### 再用布林產生布林

 * 語句話一點
 * 如果 ( (若 `馬` 與 `鹿` 一樣) 且 (`689` 比 `609` 大) )

--

### 再用布林產生布林

 * 語句話一點
 * 如果 ( (若 `馬` 與 `鹿` 一樣) 且 (`689` 比 `609` 大) )
 * `var and_op = (h == d) && (b > g);`

--

### 再用布林產生布林

 * 語句話一點
 * 如果 ( (若 `馬` 與 `鹿` 一樣) 且 (`689` 比 `609` 大) )
 * `var and_op = (h == d) && (b > g);`
 * `console.log(and_op)` => `false`

--

### 再用布林產生布林

* 語句話一點
* 如果 ( (若 `馬` 與 `鹿` 一樣) 或 (`689` 比 `609` 大) )

--

### 再用布林產生布林

* 語句話一點
* 如果 ( (若 `馬` 與 `鹿` 一樣) 或 (`689` 比 `609` 大) )
* `var or_op = (h == d) || (b > g);`

--

### 再用布林產生布林

* 語句話一點
* 如果 ( (若 `馬` 與 `鹿` 一樣) 或 (`689` 比 `609` 大) )
* `var or_op = (h == d) || (b > g);`
* `console.log(or_op)` => `true`

--

### 練習 & 休息時間
#### 程式碼練習 5 ，題目：

首先，定義一個名為 `q` 的變數，並指定其初始值為 `5`。讓變數 `q` 每次加 `1`，連續加到 `q` 等於 `16` 為止。在 `q` 的值介於 `12` 到 `15` 之間時，印出 `q=?` 的資料。

--

### 練習 & 休息時間
#### 程式碼練習 6 ，題目：

有一台計程車計費方式為：里程數在 `1500` 公尺以下皆為 `70` 元，超過之里程數則以 `500` 公尺加價 `5` 元計算。請寫一程式計算車費。

```
console.log("請輸入里程數:");
var meter = prompt();
```

這樣來取得里程數喔

--

### 練習 & 休息時間
#### 程式碼練習 7 ，題目：

宣告一個變數 `score`，當 `score` 為 `0`~`59` 時顯示 `Bad`，當 `score` 為 `60`~`100` 之間時顯示 `Good`，其餘則輸出 `Oops!`。

```
console.log("請輸入分數:");
var score = prompt();
```

這樣來取得分數喔

--

# 我們來點情境
## 情境一

--

### 我們來點情境，情境一

走在路上時，遇到一個人  
如果是學妹，則...  
如果是學弟，則...  
如果是這學期教你的教授，則...  
如果是之前當過你的教授，則...  
&nbsp;  
&nbsp;  
把下面這個輸入，他會隨機幫你遇到一個人

```
function meet_a_people(){
    return ['學妹','學弟','這學期教你的教授','之前當過你的教授'][Math.floor(Math.random()*4)];
}
```

--

### 我們來點情境，情境一

走在路上時，遇到一個人  
如果是學妹，則...  
如果是學弟，則...  
如果是這學期教你的教授，則...  
如果是之前當過你的教授，則...  

```
the_people_you_meet = meet_a_people();
if(the_people_you_meet == '學妹')
    console.log("學妹你好啊～最近怎麼樣啊～？");
else if(the_people_you_meet == '學弟')
    console.log("...");
else if(the_people_you_meet == '這學期教你的教授')
    console.log("教授好！");
else if(the_people_you_meet == '之前當過你的教授')
    console.log("(ﾉ｀⊿´)ﾉ");
```

--

# 面對這種情況
## 有另一種流程控制的方法
## `switch` ... `case` ...

--

### 面對這種情況，另一種流程控制的方法

```
the_people_you_meet = meet_a_people();switch(the_people_you_meet) {
    case '學妹':
        console.log("學妹你好啊～最近怎麼樣啊～？");
        break;
    case '學弟':
        console.log("...");
        break;
    case '這學期教你的教授':
        console.log("教授好！");
        break;
    case '之前當過你的教授':
        console.log("(ﾉ｀⊿´)ﾉ");
        break;
    default:
        console.log("╮(╯_╰)╭...你誰啊");
}
```

或許沒有比較短啦，不過很多編輯器可以幫你生程式碼

--

# 我們來點情境
## 情境二

--

### 我們來點情境，情境二

走在路上時，遇到一百個人  
要分別對每個人做情境一做的事情  

--

### 我們來點情境，情境二

走在路上時，遇到一百個人  
要分別對每個人做情境一做的事情  

![needsLoop](http://i.imgur.com/nP2GIt3.png)

--

# 迴圈
## 你可以簡單地叫電腦幫你做一件事情數千甚至數萬次

--

### 第一種迴圈，key word `for`

 * 歷久不衰的語法，`for` 迴圈有三格
 * 第一格為進入時會進行的
 * 第二格為每次執行 `{}` 內的程式碼之前會檢查的，為 `False` 的話會跳出這個迴圈
 * 第三格為每次執行完 `{}` 內的程式碼之後會執行的事情

```
for(i = 0 ; i <= 100 ; i++){
    // do something...
}
```

--

### 第一種迴圈，key word `for`

```
for(i = 0 ; i <= 100 ; i++){
    the_people_you_meet = meet_a_people();
    if(the_people_you_meet == '學妹')
        console.log("學妹你好啊～最近怎麼樣啊～？");
    else if(the_people_you_meet == '學弟')
        console.log("...");
    else if(the_people_you_meet == '這學期教你的教授')
        console.log("教授好！");
    else if(the_people_you_meet == '之前當過你的教授')
        console.log("(ﾉ｀⊿´)ﾉ");
}
```

--

### 第二種迴圈，key word `while`

* 只有一格，只要那格為 `true` 就會不斷執行

```
var i = 0
while(i <= 100){
    the_people_you_meet = meet_a_people();
    if(the_people_you_meet == '學妹')
        console.log("學妹你好啊～最近怎麼樣啊～？");
    else if(the_people_you_meet == '學弟')
        console.log("...");
    else if(the_people_you_meet == '這學期教你的教授')
        console.log("教授好！");
    else if(the_people_you_meet == '之前當過你的教授')
        console.log("(ﾉ｀⊿´)ﾉ");

    i++;
}
```

--

# 我們來點情境
## 情境三

--

### 我們來點情境，情境三

走在路上時，遇到一百個人  
要分別把每個人的身份記下來...  
(越來越不像正常人了啊)  

--

# 陣列
## 簡單來說就是一大堆變數
## 用編號串起來

--

### 陣列

* 用 `[]` 表示

```
var array = [];
var array = ['學妹','學弟','這學期教你的教授','之前當過你的教授'];
```

--

### 陣列

* 用 `[]` 表示
* 變數名稱後面加上 [<編號>] 來存取值

```
var array[0]; => '學妹'
var array[2]; => '這學期教你的教授'
var array[3]; => '之前當過你的教授'
```

--

### 陣列

* 用 `[]` 表示
* 變數名稱後面加上 [<編號>] 來存取值

```
var peoples = [];
for(i = 0 ; i <= 100 ; i++){
    peoples[i] = meet_a_people();
}
console.log(peoples);
```

--

### 關於一些陣列要注意的地方

 * 去找拿不到的編號的時候，會得到 `undefined`，JS 不會對此噴錯

--

# 謝謝！
## 其實自學是很重要的，因為自己最瞭解自己學到哪裡！
## 所以有 回家作業

--

### 第一題

富翁堯堯有一天到賭場小試身手，他總共骰了十次骰子，請身為賭場管理員的你隨機產生十組整數，範圍為０～１００，數字可重複！並將此十組整數存入一陣列，此陣列名稱為rich，最後請印出這十組整數！  
（需用到 `while` 迴圈及亂數產生 `Math.random()` ）  

--

### 第二題（承上題）

因為富翁堯堯覺得骰子的值排列沒有規則，所以請你將rich陣列的值由小到大排列，並印出值  
（使用for迴圈）  

--

### 第三題（承上題）

龜毛的富翁堯堯非常喜歡偶數，所以請將排列好的rich陣列內是偶數的值印出  
（使用switch）

--


### 第四題（承上題）

討厭的富翁堯堯指定將rich陣列奇數索引值的值平方後相加，再減去偶數索引值的值，並印出值

(平方可使用 `Math.pow(x,y) //Returns the value of x to the power of y` ）

--

### 第五題

令 i=-3, j=2, k=0  

 1. 先分別試試 && 運算子和 || 運算子對運算式做判斷（ex. print 出 i<0 && j>0 的結果, etc），並整理出這兩的運算子的規律（在什麼狀況下會為 true、什麼狀況為 false），那麼你知道 i<0 || j==1 && k!=0 的結果為什麼是 true 嗎？

 2. 接著我們來試試直接對變數做運算，請把 i&&j, i&&k, j&&k 印出來，並將變數前後位置對調，請用 || 作上述動作，你知道為什麼印出來結果會是這樣嗎？

--

### 第五題，提示

```
補充:  
在JavaScript進行邏輯運算時，運算式中的 "參數值" 會被當作布林值作判斷，  
若參數值未設定，或是參數值為 0, -0, null, false, NaN, undefined, 空字串""，則當作false；參數為其它值或是物件，則為 true。  
值得一提的是，在進行邏輯運算之後，運算式將根據下列規則作數值的回傳:  
```

```
在 && 運算中，有2個規則:
如果運算式轉為布林值為false，則回傳該數值。(例如0, null, undefined, NaN和空字串)如果為true，則回傳右邊運算式的數值；換言之，當全部成立時，回傳最右邊運算式的數值。
ex. 在上述題目中，i&&j的結果，由於i=-3, j=2，在進行邏輯運算時，兩個參數皆為true，故 &&  運算後的結果為true。根據第2個規則，結果將回傳右邊的運算式的數值2。
```

```
此外，假如左邊的運算式結果為true時，將不會執行右邊的運算式。  

類似於&&，在 || 運算中，也有2個規則:
如果運算式轉為布林值為true，則回傳該數值。
如果為false，則回傳右邊運算式的數值；如果全部為false，則回傳false。
```

--

### 第六題

宣告一個變數 `name`，並將其指定為你自己的英文名字並印出，然後在底下使用 `if` 進行判斷，如果 `name` 的長度大於 `5`，則印出 `Longer than five.`；否則，印出 `Shorter than six.`。

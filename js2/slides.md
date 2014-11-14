Javascript 2
====

Slide Link: [nchusg.org/~cjhwong/js2](http://nchusg.org/~cjhwong/js2)

Created by Chuan-Jhe Hwong

Email: [CJHwong@gmail.com](mailto://CJHwong@gmail.com)

Function
----

> 函數簡介

#### f(x) = x + 1

  -  x + 1: main structure of the function
  -  f(x): name and parameters of the function
  -  f(1), f(2)...: return value of the function

#### 使用函數的優點

  -  簡化重複的程式碼
  -  增加程式碼的再利用性
  -  適當切割程式功能可以便利維護
  -  好的函數命名能使程式語言更像在說話


#### 何時使用函數
```javascript
var nums = [10, 3, 16, 8, 20, 13, 11];

var max = 0;

var i;
for (i = 0; i < nums.length; i++) {
  if (nums[i] > max) {
    max = nums[i];
  }
}

console.log(max);
```

#### how to make this better?
```javascript

var nums = [10, 3, 16, 8, 20, 13, 11];

var max = 0; // Record the max number

// Find the max number
var i;
for (i = 0; i < nums.length; i++) {
  if (nums[i] > max) {
    max = nums[i];
  }
}

console.log(max);
```

#### 使用函數包裝的程式碼
```javascript

function max(nums) {
  //Return the max number of an array
  var max = 0;
  var i;
  for (i = 0; i < nums.length; i++) {
    if (nums[i] > max) {
      max = nums[i]
    }
  }
  return max;
}

var nums = [10, 3, 16, 8, 20, 13, 11];

console.log(max(nums));
```

#### Functional scope
```javascript

function f(n) {
  n += 10;
  console.log(n);
}

n = 1;
f(n);
console.log(n);
```

#### DEMO
建立一接收兩個數字的函數 f(n1, n2)，並使用函數印出 n1 到 n2 中間的數

First-class function
----

> 一級函數

#### 在 JS，宣告一個函數就相當於宣告一個變數
```javascript

function addOne(n) {
  return n + 1;
}
```

#### 你可以傳遞函數
```javascript

function addOne(n) {
  return n + 1;
}

var f = addOne;
console.log(f(10));
```

#### 什麼是一級函數？
當函數可被視為一級成員(變數……)傳遞時，稱為一級函數


#### for example
```javascript

function calc(n1, n2, f) {
  return f(n1, n2);
}

function plus(n1, n2) {
  return n1 + n2;
}

function multiply(n1, n2) {
  return n1 * n2;
}

var n1 = 10, n2 = 20;
console.log(calc(n1, n2, plus));
console.log(calc(n1, n2, multiply));
```

Anonymous function
----

> 匿名函數

#### 建立一個匿名函數
```javascript

(function(name) {
  console.log("Hi I am " + name);
})("CJHwong");
```


#### 如何使用匿名函數
```javascript

var n1 = 10, n2 = 20;
console.log(calc(n1, n2, function(n1, n2) {
  return n1 + n2;
}));

console.log(calc(n1, n2, function(n1, n2) {
  return n1 * n2;
}));
```


#### 替匿名函數命名
```javascript

var introduce = function(name) {
  console.log("Hi I am " + name);
};

introduce("CJHwong");
```


#### demo
實作 calc 函數，並使用匿名函數完成加減乘除四種運算

Closure
----

> 閉包

#### 什麼是閉包？
若建立函數時，函數內的狀態能夠被儲存，則稱為閉包


#### 閉包由兩個以上的函數組成
```javascript

function increase() {
  var n = 0;
  return function() {
    n += 1;
    return n;
  }
}

var f = increase();
console.log(f());
console.log(f());
```

#### demo
使用 Closure 實作 Fibonacci Series（每執行一次函數生成數列的下一項）

Object
----

> 物件

#### 在 JS，物件是一種資料型態(data type)
```javascript

var obj = {
  foo: "I am foo",
  bar: "I am bar"
};
```


#### How to use objects?
```javascript

console.log(obj);

console.log(obj.foo);

console.log(obj.foo);
console.log(obj["bar"]);
//the same effect!
```


#### DEMO
宣告一個物件 people，使 people 有屬性 name, age, sex，並分別印出來

Object-oriented Programming
----

> 物件導向語言

#### what is an object?
![image](http://upload.wikimedia.org/wikipedia/commons/1/1c/Smiling_Dog_Face.jpg)

#### how?

  -  Dog is a kind of animal
  -  Dogs have diffrent hair colors
  -  Dogs have names


#### how to implement a dog object
```javascript

var Dog = {
  name: "Doge",
  color: "Yellow"
};

console.log(Dog.name);
console.log(Dog.color);
```

Methods
----

> 方法

means something objects can do


#### implementation
```javascript

var Dog = {
  name: "Doge",
  color: "Yellow",
  say: function() {
    console.log("Bow wow! I am " + this.name);
  }
};
```


#### DEMO
建立兩個物件，提供屬性 name 以及 age，並建立方法 hi，印出兩個屬性

common objects
----

> 相同物件

#### console

> 主控台（chrome 中文）

What is CONSOLE?
Press F12 on your keyboard

#### common console methods
```javascript

console.log("Hi"); // pass a string and console will display it
console.error("Error occurred!");
console.warn("Warnning!");
```

Math
----

> 數學函數

#### common math methods
```javascript

Math.random(); // Generates a random number between 0 and 1
Math.floor(0.1); // Returns 0
Math.ceil(0.1); // Returns 1
Math.abs(-10); // Returns 10
Math.sqrt(4) // Pass an integer and get its squre root
```

#### DEMO
生成十個範圍由 0~10 的隨機數，使用 log 印出小於等於三的數，使用 warn 印出小於等於七大於三的數，使用 error 印出小於等於十大於七的數
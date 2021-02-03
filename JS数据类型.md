# JS 数据类型

## number 数字
* 特殊值
  
  （1）正负都等于0
  
  （2）无穷大：Infinity、+Infinity、-Infinity
  
  （3）无法表示的数字NAN

## string 字符串
* 写法
   
  （1）单引号：'你好'
  
  （2）双引号："你好"

  （3）反引号:在``里写你好
* 字符串的长度
 ````
string.length

 ````
* 通过下标读取字符
````
string[index]

````
* 注意：引号不属于字符串的一部分
  
## bool 布尔
* 否定运算：!value
* 相等运算:1==2、1!=2、3===4、3!=4
* 比较运算：1>2、1>=2、3<4、3<=4
* 五个falsy值：undefined、null、0、NaN、'' 

*  undefined和null区别:
    
    （1）如果一个变量声明了，但没有赋值，那么默认值就是undefined，而不是null
     
     （2）如果一个函数，没有写return，那么默认值就是undefined，而不是null

##  symbol符号

## 变量声明
* 三种声明方式
````
var a = 1
let a = 1
const a = 1

````
* var和let和const区别：
  
  （1）var是以前的声明方式
  （2）let是新的方式
  （3）const是声明时必须赋值且不能改的方式

* let 声明 
  
  （1）遵循块作用域，即使用范围不能超过{}

  （2）不能重复声明，可以赋值，也可以不赋值

  （3）先声明再使用否则报错

## 类型转换
* number=>string
 
 ````
String(n)
n+"

 ````

* string=>number

 ````
 Number(s)
 parseInt(s)/parseFloat(s)
 s-0

 ```` 

* x=>boll
  
````
 Boolean(x)
 !!x

````
* x=>string

````
 String(x)
 x.toString()

````
以上是我理解的简单数据类型。


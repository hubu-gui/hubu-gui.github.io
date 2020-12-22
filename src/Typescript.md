### 简化方式：声明变量的同时就赋值
> age: number = 20
>console.log(age)
## 变量1：
>let num1: number = 33
>// 变量2：
>let num2: number = 2

>// 思路：
>let temp: number
>temp = num1 // 33
>num1 = num2 // num1 => 2
>num2 = temp // num2 => 33

>console.log(num1)
>console.log(num2)
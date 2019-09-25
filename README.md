## GitHub Pages

You can use the [editor on GitHub](https://github.com/pioneer22/pioneer22.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### Sort
1.quickSort
```markdown
快速排序，分而治之，将数组一分为三，再递归排序。
1.将数组分成三部分，left，piovt，right，使right > piovt， left <= piovt
2.递归处理left
3.递归处理right
4.合并结果
```
![ukSRN4.png](https://s2.ax1x.com/2019/09/24/ukSRN4.png)

2.BubbleSort
```markdown
冒泡排序，循环比较相邻两个数的大小，将较大的数换到最后。
```
[![ukmsJ0.png](https://s2.ax1x.com/2019/09/24/ukmsJ0.png)](https://imgchr.com/i/ukmsJ0)

3.SelectionSort
```markdown
选择排序，循环比较相邻两个数的大小，将较小数的下标保存起来，循环完一轮再进行交换位置。
```
[![uknQ6U.png](https://s2.ax1x.com/2019/09/24/uknQ6U.png)](https://imgchr.com/i/uknQ6U)

4.insertionSort
```markdown
插入排序，将前面的数据排好序，拿后面的数据来从后向前进行比较插入。
```
[![ukuEjO.png](https://s2.ax1x.com/2019/09/24/ukuEjO.png)](https://imgchr.com/i/ukuEjO)

5.MergeSort
```markdown
归并排序，自上而下的递归，自下而上的迭代
```
[![ukKoYn.png](https://s2.ax1x.com/2019/09/24/ukKoYn.png)](https://imgchr.com/i/ukKoYn)

### ES6
```markdown
1.立即执行的函数，应该写成箭头行数的形式
(()=>{ })()

2.let不存在变量提升,使用let来替代var,要先声明let变量后面才能使用，不然会出现暂时性死区。
  let不允许在相同作用域内，重复声明同一个变量。同时存在块级作用域。
  
3.从数组和对象中提取值，对变量进行赋值，这被称为解构，提取值后按照对应位置，对变量赋值。
  对象解构也可以指定默认值。字符串也可以解构。
```
[![uV7B26.png](https://s2.ax1x.com/2019/09/25/uV7B26.png)](https://imgchr.com/i/uV7B26)

```markdown
4.字符串 新增方法：
includes()：返回布尔值，表示是否找到了参数字符串。
startsWith()：返回布尔值，表示参数字符串是否在原字符串的头部。
endsWith()：返回布尔值，表示参数字符串是否在原字符串的尾部

repeat()：返回一个新字符串，表示将原字符串重复n次。

字符串补全长度的功能
padStart()：用于头部补全。
padEnd()：用于尾部补全。
```
[![uZBede.png](https://s2.ax1x.com/2019/09/25/uZBede.png)](https://imgchr.com/i/uZBede)

```markdown
5.数值 
Number.isInteger()：用来判断一个数值是否为整数。
Math.trunc()：用于去除一个数的小数部分，返回整数部分。
Math.sign()：用来判断一个数到底是正数、负数、还是零。对于非数值，会先将其转换为数值。
Math.cbrt()：用于计算一个数的立方根。
Math.hypot()：返回所有参数的平方和的平方根。
Math.expm1(x)：返回 ex - 1，即Math.exp(x) - 1。
Math.log1p(x)：返回1 + x的自然对数，即Math.log(1 + x)。如果x小于-1，返回NaN。
Math.log10(x)：返回以 10 为底的x的对数。如果x小于 0，则返回 NaN。
Math.log2(x)：返回以 2 为底的x的对数。如果x小于 0，则返回 NaN。
新增了一个指数运算符（**）
2 ** 3 // 8
```

```markdown
6.数组
扩展运算符是三个点（...）
扩展运算符还可以将字符串转为真正的数组。
Array.from()：用于将两类对象转为真正的数组：类似数组的对象（array-like object）
和可遍历（iterable）的对象（包括 ES6 新增的数据结构 Set 和 Map）。
Array.of方法用于将一组值，转换为数组。
find()：用于找出第一个符合条件的数组成员。
findIndex()：返回第一个符合条件的数组成员的位置，如果所有成员都不符合条件，则返回-1。
fill()：使用给定值，填充一个数组。
数组实例的 entries()，keys() 和 values() 
```
[![uZsIO0.png](https://s2.ax1x.com/2019/09/25/uZsIO0.png)](https://imgchr.com/i/uZsIO0)

```markdown
7.对象
Object.is()：用来比较两个值是否严格相等，与严格比较运算符（===）的行为基本一致。
Object.assign()：用于对象的合并，将源对象（source）的所有可枚举属性，复制到目标对象（target）。
```

### Vue
```markdown


```

### 微信小程序
```markdown


```

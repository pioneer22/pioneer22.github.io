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
[![ueRtU0.png](https://s2.ax1x.com/2019/09/26/ueRtU0.png)](https://imgchr.com/i/ueRtU0)

```markdown
8.set 和 Map
Set本身是一个构造函数，用来生成 Set 数据结构。它类似于数组，但是成员的值都是唯一的，没有重复的值。

Set.prototype.add(value)：添加某个值，返回 Set 结构本身。
Set.prototype.delete(value)：删除某个值，返回一个布尔值，表示删除是否成功。
Set.prototype.has(value)：返回一个布尔值，表示该值是否为Set的成员。
Set.prototype.clear()：清除所有成员，没有返回值。
Array.from方法可以将 Set 结构转为数组。

Map提供“键值对”的数据结构，“键”的范围不限于字符串，各种类型的值（包括对象）都可以当作键。
Map 结构提供了“值—值”的对应，是一种更完善的 Hash 结构实现。

Map.prototype.keys()：返回键名的遍历器。
Map.prototype.values()：返回键值的遍历器。
Map.prototype.entries()：返回所有成员的遍历器。
Map.prototype.forEach()：遍历 Map 的所有成员。
```
[![ueWsSS.png](https://s2.ax1x.com/2019/09/26/ueWsSS.png)](https://imgchr.com/i/ueWsSS)

```markdown
9.Proxy
Proxy 用于修改某些操作的默认行为，等同于在语言层面做出修改，所以属于一种“元编程”
（meta programming），即对编程语言进行编程。

Proxy在目标对象之前架设一层“拦截”，外界对该对象的访问，都必须先通过这层拦截，因此提供了一种机制。
可以对外界的访问进行过滤和改写。由它来“代理”某些操作，可以译为“代理器”。

var proxy = new Proxy(target, handler);
target参数表示所要拦截的目标对象，handler参数也是一个对象，用来定制拦截行为。
要使得Proxy起作用，必须针对Proxy实例进行操作，而不是针对目标对象进行操作。

get(target, propKey, receiver)：拦截对象属性的读取，比如proxy.foo和proxy['foo']。
set(target, propKey, value, receiver)：拦截对象属性的设置，比如proxy.foo = v
或proxy['foo'] = v，返回一个布尔值。

has(target, propKey)：拦截propKey in proxy的操作，返回一个布尔值。
deleteProperty(target, propKey)：拦截delete proxy[propKey]的操作，返回一个布尔值。
ownKeys(target)：拦截Object.getOwnPropertyNames(proxy)、Object.getOwnPropertySymbols(proxy)、
Object.keys(proxy)、for...in循环，返回一个数组。该方法返回目标对象所有自身的属性的属性名，
而Object.keys()的返回结果仅包括目标对象自身的可遍历属性。
getOwnPropertyDescriptor(target, propKey)：拦截Object.getOwnPropertyDescriptor(proxy, propKey)，
返回属性的描述对象。
defineProperty(target, propKey, propDesc)：拦截Object.defineProperty(proxy, propKey, propDesc）、
Object.defineProperties(proxy, propDescs)，返回一个布尔值。
preventExtensions(target)：拦截Object.preventExtensions(proxy)，返回一个布尔值。
getPrototypeOf(target)：拦截Object.getPrototypeOf(proxy)，返回一个对象。
isExtensible(target)：拦截Object.isExtensible(proxy)，返回一个布尔值。
setPrototypeOf(target, proto)：拦截Object.setPrototypeOf(proxy, proto)，返回一个布尔值。
如果目标对象是函数，那么还有两种额外操作可以拦截。
apply(target, object, args)：拦截 Proxy 实例作为函数调用的操作，比如proxy(...args)、
proxy.call(object, ...args)、proxy.apply(...)。
construct(target, args)：拦截 Proxy 实例作为构造函数调用的操作，比如new proxy(...args)。
```
[![uehjxO.png](https://s2.ax1x.com/2019/09/26/uehjxO.png)](https://imgchr.com/i/uehjxO)

```markdown
10.Promise
Promise 是一个对象，从它可以获取异步操作的消息。
Promise对象代表一个异步操作，有三种状态：pending（进行中）、fulfilled（已成功）和rejected（已失败）。
只有异步操作的结果，可以决定当前是哪一种状态，任何其他操作都无法改变这个状态。
Promise实例生成以后，可以用then方法分别指定resolved状态和rejected状态的回调函数。
Promise.all()：用于将多个 Promise 实例，包装成一个新的 Promise 实例。
```
[![ueICCt.png](https://s2.ax1x.com/2019/09/26/ueICCt.png)](https://imgchr.com/i/ueICCt)

```markdown
11.async
async就是Generator 函数的语法糖。
async函数就是将 Generator 函数的星号（*）替换成async，将yield替换成await
async表示函数里有异步操作，await表示紧跟在后面的表达式需要等待结果。
async函数的返回值是 Promise 对象，可以用then方法指定下一步的操作。

await命令后面是一个 Promise 对象，返回该对象的结果。如果不是 Promise 对象，就直接返回对应的值。
```
[![ueo5f1.png](https://s2.ax1x.com/2019/09/26/ueo5f1.png)](https://imgchr.com/i/ueo5f1)

```markdown
12.class
实例的属性除非显式定义在其本身（即定义在this对象上），否则都是定义在原型上（即定义在class上）。
在“类”的内部可以使用get和set关键字，对某个属性设置存值函数和取值函数，拦截该属性的存取行为。
类的所有实例共享一个原型对象。
ES6 为new命令引入了一个new.target属性，该属性一般用在构造函数之中，返回new命令作用于的那个构造
函数。如果构造函数不是通过new命令或Reflect.construct()调用的，new.target会返回undefined。
子类继承父类时，new.target会返回子类。

Object.getPrototypeOf方法可以用来从子类上获取父类。
super这个关键字，既可以当作函数使用，也可以当作对象使用。
super作为函数调用时，代表父类的构造函数。
super虽然代表了父类A的构造函数，但是返回的是子类B的实例，即super内部的this指的是B的实例

super作为对象时，在普通方法中，指向父类的原型对象；在静态方法中，指向父类。
由于super指向父类的原型对象，所以定义在父类实例上的方法或属性，是无法通过super调用的。

#类的 prototype 属性和__proto__属性
A.子类的__proto__属性，表示构造函数的继承，总是指向父类。
B.子类prototype属性的__proto__属性，表示方法的继承，总是指向父类的prototype属性。
```
[![ue7WGR.png](https://s2.ax1x.com/2019/09/26/ue7WGR.png)](https://imgchr.com/i/ue7WGR)

[![ueL9eK.png](https://s2.ax1x.com/2019/09/26/ueL9eK.png)](https://imgchr.com/i/ueL9eK)

```markdown
13.Module
ES6 模块不是对象，而是通过export命令显式指定输出的代码，再通过import命令输入。
模块功能主要由两个命令构成：export和import。export命令用于规定模块的对外接口，import命令用于输入其他模块提供的功能。
export输出的变量就是本来的名字，但是可以使用as关键字重命名。

export default命令，为模块指定默认输出。
使用export default时，对应的import语句不需要使用大括号；
不使用export default时，对应的import语句需要使用大括号。
```
[![uevZ4S.png](https://s2.ax1x.com/2019/09/26/uevZ4S.png)](https://imgchr.com/i/uevZ4S)

```markdown
14.Module加载实现
浏览器允许脚本异步加载，下面就是两种异步加载的语法。
defer与async的区别是：defer要等到整个页面在内存中正常渲染结束（DOM 结构完全生成，以及其他脚本执行完成），
才会执行；async一旦下载完，渲染引擎就会中断渲染，执行这个脚本以后，再继续渲染。一句话，defer是“渲染完再执行”，
async是“下载完就执行”。另外，如果有多个defer脚本，会按照它们在页面出现的顺序加载，而多个async脚本是不能保证加载顺序的。

浏览器加载 ES6 模块，也使用<script>标签，但是要加入type="module"属性。
  
浏览器对于带有type="module"的<script>，都是异步加载，不会造成堵塞浏览器，即等到整个页面渲染完，再执行模块脚本，等同于打开了<script>标签的defer属性。
```
[![uexIy9.png](https://s2.ax1x.com/2019/09/26/uexIy9.png)](https://imgchr.com/i/uexIy9)

### Vue
```markdown


```

### 微信小程序
```markdown


```

### Node.js
```markdown
1.什么是node.js
node.js不是一门语言，不是库，不是框架，是一个JavaScript运行时的环境。
可以解析和执行JavaScript代码。
node.js中的JavaScript没有BOM,DOM。

2.node.js执行
创建编写JavaScript脚本文件。
打开终端定位脚本文件所在目录。
输入node 文件名执行文件。

3.node.js特性
A.事件驱动
B.非阻塞I/O模型(异步)
C.轻量和高效

require是一个方法，用来加载模块
在node中，模块有三种：
A.具名的核心模块，如fs,http.path
B.用户自己编写的文件模块，相对路径必须加./，可以省略后缀名，相对路径中省略./会报错。
C.在node中没有全局作用域，只有模块作用域，外部访问不到内部，内部也访问不到外部。

require方法有两个作用
A.加载文件模块并执行里面代码。
B.拿到被加载文件模块导出的接口对象。

在node.js中利用fs.readFile()来读取文件。用fs.writeFile()来写入文件。
```

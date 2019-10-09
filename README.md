## GitHub Pages

You can use the [editor on GitHub](https://github.com/pioneer22/pioneer22.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### Sort
**1.quickSort**
```markdown
快速排序，分而治之，将数组一分为三，再递归排序。
1.将数组分成三部分，left，piovt，right，使right > piovt， left <= piovt
2.递归处理left
3.递归处理right
4.合并结果
```
![ukSRN4.png](https://s2.ax1x.com/2019/09/24/ukSRN4.png)

**2.BubbleSort**
```markdown
冒泡排序，循环比较相邻两个数的大小，将较大的数换到最后。
```
[![ukmsJ0.png](https://s2.ax1x.com/2019/09/24/ukmsJ0.png)](https://imgchr.com/i/ukmsJ0)

**3.SelectionSort**
```markdown
选择排序，循环比较相邻两个数的大小，将较小数的下标保存起来，循环完一轮再进行交换位置。
```
[![uknQ6U.png](https://s2.ax1x.com/2019/09/24/uknQ6U.png)](https://imgchr.com/i/uknQ6U)

**4.insertionSort**
```markdown
插入排序，将前面的数据排好序，拿后面的数据来从后向前进行比较插入。
```
[![ukuEjO.png](https://s2.ax1x.com/2019/09/24/ukuEjO.png)](https://imgchr.com/i/ukuEjO)

**5.MergeSort**
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

类的 prototype 属性和__proto__属性
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

每个模块都提供一个对象：'exports',默认是一个空对象。
把需要被外部访问的成员手动挂载到'exports'接口对象中。
谁来require这个模块，谁就可以得到模块内部的exports接口对象。

4.补分号
当一行代码是以'(','[','`'这三种开头的时候则在前面补上一个分号用于避免一些语法解析错误。
```
[![u3ZfxS.png](https://s2.ax1x.com/2019/09/29/u3ZfxS.png)](https://imgchr.com/i/u3ZfxS)

```markdown
5.使用模板引擎art-template
安装 npm install art-template
在需要使用的文件模块中加载art-template
只需要使用require方法加载：require('art-template')
art-template是下载的包的名字，下载什么就require什么。
查文档使用模板引擎API
http://aui.github.io/art-template/zh-cn/docs/api.html

通过readFile默认读取到的data是二进制数据，而模板引擎的render方法需要接收的是字符串，才能给模板引擎使用。
render方法读取data.toString()就可以了。

6.服务端渲染与客户端渲染的区别
A.客户端渲染不利于SEO搜索引擎优化。
B.服务端渲染可以被爬虫抓取到，客户端异步渲染很难被爬虫抓取到。
真正的网站并不是纯异步和纯服务端渲染出来的，而是两者结合。

7.服务端渲染的流程
在服务端中，文件的路径不要去写相对路径，这时候所有的资源都是通过url标识来获取的。
一般服务器开发/public/目录，所以请求路径都写成 /public/xxx。
/ 是url根路径的意思，浏览器真正发请求的时候会把 http://127.0.0.1:XXX拼上
带有src或者是href(link) 属性标签的时候，浏览器会自动对这些资源发起请求。
```
[![u3nYUs.png](https://s2.ax1x.com/2019/09/29/u3nYUs.png)](https://imgchr.com/i/u3nYUs)

```markdown
8.如何通过服务端让客户端重定向？
A.状态码设置为302临时重定向，statusCode。
B.在响应头中通过Location告诉客户端重定向到哪里去，setHeader。

客户端发现服务端的响应状态码是302的时候就会自动去响应头中找Location,所以可以看到客户端自动跳转。
302临时重定向。
301永久重定向，浏览器会记住。

res.statusCode = 302
res.setHeader('Location','/')
```

```markdown
Node中的模块系统
1.EcmaScript 
  和浏览器不同，在Node中没有BOM,DOM
2.核心模块
  文件操作的fs
  http服务的http
  url路径操作模块
  path路径处理模块
  os系统操作模块
3.第三方模块
  art-template
  必须通过npm来下载才可以使用
4.个人模块
  自己创建的文件
5.CommonJS模块规范
  模块系统：
  A.模块作用域。
  B.使用require方法来加载模块。
  C.使用exports接口对象来导出模块中的成员。
  
  加载require
  var 自定义变量名 = require （‘模块’）
  作用：执行被加载模块中的代码。得到被加载模块中的exports导出接口对象。
  
  导出exports
  A.Node中是模块作用域，默认文件中的所有成员只在当前文件模块有效。
  B.希望可以被其它模块访问的成员，需要把这些公开的成员都挂载到exports接口对象中。
  导出多个成员（必须在对象中）
```
[![u8ZWlT.png](https://s2.ax1x.com/2019/09/29/u8ZWlT.png)](https://imgchr.com/i/u8ZWlT)

```markdown
导出单个成员（拿到的就是:函数、字符串）
当使用多次module.exports 时，后面的会覆盖前面的，以最后一个为准。
```
[![u8mexK.png](https://s2.ax1x.com/2019/09/29/u8mexK.png)](https://imgchr.com/i/u8mexK)

```markdown
exports 和 module.exports的区别
A.每个模块中都有一个module对象。
B.modules对象中有一个exports对象。
C.可以把需要导出的对象都挂载到module.exports接口对象中。即 module.exports.xxx = xxx
D.Node为了方便，在每一个模块中都提供了一个成员叫：exports, exports === module.exports 为true
E.对于module.exports.xxx = xxx,完全可以使用exports.xxx = xxx
F.当一个模块需要导出单个成员的时候，这个时候必须使用，module.exports = xxx,使用exports = xxx 无效。
每个模块最终向外return的是module.exports,exports只是module.exports的一个引用。所以为exports = xxx
重新赋值，也不会影响 module.exports,但是如果通过 exports = module.exports来重新建立引用关系则会生效。
```

```markdown
第三方模块：
A.都必须通过npm来下载。
B.通过require('包名')的方式来进行加载才可以使用。
C.一个项目有且只有一个node_modules,放在根目录下。

模块的查找机制
优先从缓存加载
核心模块
路径形式的文件模块
第三方模块
最后找不到则会报错: Can not found module xxx

package.json中最有用的是dependencies，它可以为我们保存第三方包的依赖信息。
删除了node_modules,z则可以通过npm install ,自动把package.json中的dependencies中的所有依赖下载回来。

建议执行npm install 包名的时候都加上--save这个选项，目的是用来保存依赖信息。
```

```markdown
npm
A.npm网站（npmjs.com）
B.只要安装了node就已经安装了npm。
C.升级npm,npm install --global npm

npm命令
1.npm init   (npm init -y) 跳过向导，快速生成。
2.npm install  一次性把dependencies选项中的依赖全部安装
3.npm install --save 包名  下载并且保存依赖项（package.json文件中的dependencies选项）
4.npm uninstall --save 包名  删除的同时也会把依赖信息去除
5.npm 命令 --help 查看指定命令的使用帮助。

安装淘宝的cnpm
1.在任意目录执行都可以。
2.--global 表示安装到全局。
npm install --global cnpm

不安装cnpm使用淘宝服务器下载
npm install XXX --registry=https://registry.npm.taobao.org

每次手动添加参数会很麻烦，我们可以把这个选项加入配置文件中
npm config set registry https://registry.npm.taobao.org

查看npm 配置信息
npm config list 
```

```markdown
修改完代码自动重启
使用nodemon, nodemon是一个基于node.js开发的一个第三方命令行工具，使用的时候需要独立安装
npm install nodemon

使用nodemon, 当文件发生变化的时候自动重启。
nodemon XXX.js

基本路由
路由器
A.请求方法
B.请求路径
C.请求处理函数

// get方法请求
app.get('' ,function(req, res){
  res.send()
})

// post方法请求
app.post('', function(req, res){
  res.send()
})

静态服务
// public资源
app.use(express.static('public'))

// files资源
app.use(express.static('files'))

// /public/xxx
app.use('/public/', express.static('./public/'))

使用art-template模板引擎
A.第一个参数，当渲染以 XXX结尾的文件的时候，使用art-template模板引擎
B.express-art-template是专门用来在Express中把art-template整合到Express中
C.虽然外面不需要加载art-template,但是也必须安装，因为express-art-template依赖了art-template
app.engine('XXX',require('express-art-template'))

Express为response相应对象提供了一个方法render
render方法默认是不可以使用，但是如果配置了模板引擎就可以使用
res.render('html模板名'，{模板数据})
第一个参数不能写路径，默认会去项目中的views目录查找该模板文件
Express有一个约定，开发人员把所有的视图文件都放到views目录中。

// 修改默认的views目录
app.set('views',render函数的默认路径)

Express中配置使用art-template模板引擎
npm install --save art-template
npm install --save express-art-template

使用：
app.get('/',function(req,res){
  // express默认会去项目中的views目录找index.html
  res.render('index.html',{
    title: 'hello world!'
  })
})

在Express中获取表单GET请求参数
Express内置了一个API,可以直接通过req.query来获取

在Express中获取表单POST请求数据
通过第三方包： body-parser
安装：
npm install --save body-parser

配置：
```
[![uWFSpR.png](https://s2.ax1x.com/2019/10/07/uWFSpR.png)](https://imgchr.com/i/uWFSpR)

[![uWFF0O.png](https://s2.ax1x.com/2019/10/07/uWFF0O.png)](https://imgchr.com/i/uWFF0O)

```markdown
callback
是一种数据类型
参数
返回值
一般情况下，把函数作为参数的目的就是为了获取函数内部的异步操作结果
callback就是回调函数
```
[![u4ZJrd.png](https://s2.ax1x.com/2019/10/09/u4ZJrd.png)](https://imgchr.com/i/u4ZJrd)

[![u4ZhGT.png](https://s2.ax1x.com/2019/10/09/u4ZhGT.png)](https://imgchr.com/i/u4ZhGT)

```markdown
package.json 和 package-lock.json
npm5以前不会有package-lock.json这个文件，npm5之后才加入它。
当你安装包的时候，npm都会生成或者更新package-lock.json这个文件。
  npm5以后的版本安装包都不需要加 --save这个参数，他会自动保存依赖信息。
  安装包的时候，会自动创建或者更新package-lock.json这个文件。
  package-lock.json会保存node_modules中所有包的信息（版本、下载地址）
    这样重新 npm install的时候速度就可以提升。
  从文件来看，有一个lock称之为锁
    这个lock是用来锁定版本的
    这个package-lock.json这个文件的另一个作用就是锁定版本号，防止自动升级新版。

```

```markdown
MongoDB
非关系型数据库
MongoDB是长得最像关系型数据库的非关系型数据库
数据库 =》 数据库
数据表 =》 集合（数组）
表记录 =》 （文档对象）

MongoDB不需要设计表结构
可以任意往里面存数据，没有结构性一说

启动
mongoDB默认使用执行mongod命令所处盘符根目录下的/data/db作为自己的数据存储目录
所以第一次执行该命令之前要手动创建一个 /data/db
修改默认的数据存储目录：
mongod --dbpath = 数据存储目录路径

停止
直接Ctrl+C
或者直接关闭服务的控制台

连接和退出数据库
默认连接本机mongoDB服务
mongo

在连接状态输入exit 退出连接
exit



```

```markdown


```

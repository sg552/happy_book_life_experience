# 如何转行从业IT

转行目前来看分3个方向：

1. 传统web开发 (必会): 这个必会，无论要不要做后面2个，这个都永远绕不开。32岁之后就失业了，青春饭。
2. 区块链开发( web3 智能合约): 这个是新形势的开发。基本都是远程工作，工资很高。3W起步吧。
3. 网络安全. 这个就不细说了，财富自由之路。

## 可以先买本书

《软件开发之殇》 这里涵盖了软件领域的方方面面， 很适合想转行的同学看。

传统的软件开发职业包括：web前端，web后端，android, ios, UI, 产品经理，测试，运维。我们这里只说 web 前后端吧。

## 传统web开发 路径

### 1.学习基本的html

学习路径就是：

HTML(一天） ->  CSS （一天）  -> javascript （一天）.

这样就可以做静态网页了。 （做几个DEMO， 耗时一周）

### 2.学习 数据库（SQL）， 1天



### 3.学习一门后端语言(go语言, 推荐这个，以后可以使用ruby语言 )    2天

建议从go开始学习，不要学习动态语言。

理由是：Go语言是传统的编译型语言，从教学的角度看，特别适合新手，下面的这些概念务必要学习完整；

- 变量的类型,定义，调用
- 方法的类型，定义，调用, 参数的各种形式，意义
- class的 声明，啥是一个instance
- 变量的作用域，方法的作用域
- 变量的 shadow
- 复杂类型的clone , 深拷贝，浅拷贝
- 熟悉 Array (数组), Map (或者叫Hash), 这样的基本数据结构，

然后去leetcode 做算法题目。 做20道题目，培养一下编程的感觉。

这个对于新手特别重要。

### 4.学习该语言的框架(Gin + gorm, 以后可以使用rails 框架)   1~2周

Go语言的web框架是Gin,  操作数据库的框架是Gorm, 跟Rails几乎一样。 特别好上手。

然后做个DEMO(2  周）

就可以做后端开发了。

### 5.reactjs 或者vuejs

等前端会了，后端会了之后，再用一天的时间学习react.js 或者vue.js , 并且做几个小项目，你就算是后端小全栈的入门了。

这个状态保持一年左右。 你就不错了。（需要经历真实的项目磨练才行，经历赶进度，被批评等等，否则慢慢哟哟的肯定不行）

你也可以在2,3个月的时候，转入网络安全方向。到时候我可以带你入门。 网路安全，就是俗称黑客。需要个几年的时间，前景比开发好。

HTML,CSS 的简单教程：http://js_book.siwei.me/

html, css ,javascript的教程：  可以baidu, w3school啥的。

ruby ， rails的简单教程： http://rails_book.siwei.me/


### 学习原则：

1. 不求一步学习到位，但是需要：混个脸熟。学习的时候，囫囵吞枣，但是用的时候，现用现查。（例如查baidu，查谷歌）
2. 不要只用眼睛看，必须必须必须动手敲代码（跟背单词 要动手写是一样的。）

### 学习细节：

1.把本机配置好 开发环境（特别重要）， 大师会陪着你陪。

2.HTML: http://js_book.siwei.me/web_front_end/html.html   把这个页面的提到的HTML标签，记住就行

细节学习：https://www.runoob.com/html/html-tutorial.html  （注意不需要学习左侧菜单的所有内容，把重点内容敲一遍到2遍即可。）

3.CSS:

http://js_book.siwei.me/web_front_end/css.html   把这个页面提到的CSS 样式，记住就行（起码混个脸熟）

细节学习： https://www.runoob.com/css/css-tutorial.html    （注意不需要学习左侧菜单的所有内容，把重点内容敲一遍到2遍即可。）

4.javascript : 运行在浏览器上的编程语言，可以与 网页互动。

细节学习： https://www.runoob.com/js/js-tutorial.html   （注意不需要学习左侧菜单的所有内容，把重点内容敲一遍到2遍即可。）

重点内容：  声明方法， for 循环， if 判断， 定义和使用：数据(Array) ,  Hash .

需要本地配置好开发环境：

1. sublime  编辑器
2. （以后）使用vim 作为编辑器，使用git作为版本控制工具，使用linux 作为开发环境。
3. 配置好fanqiang工具。这样就可以查询guge的内容了。

（长期学习，等学习完HTML, CSS, JS之后，立刻就开始用）

使用vim： http://vim_book.siwei.me/lesson1.html

使用git:   https://edu.51cto.com/course/8363.html


## 区块链智能合约开发

先至少干一年传统web前后端开发。

### 1.对区块链，数字货币，Token， 转账有了解：

下载个Metamask

注册个交易所（例如binance.com )

买点币，例如 BSC, 然后转到自己的metamask钱包上， 再转回去

使用钱包进行签名

知道啥是gas price

知道每个转账都有留言

知道 啥是contract, 啥是token ,

可以进行查询，知道每一笔账的来龙去脉， 知道账户的每一笔款的来龙去脉。

### 2.搭建一个ETH节点

使用Geth, 然后使用轻模式（lightmode) 搭建一个ETH节点， 进行下面的操作：

创建钱包地址

使用metamask 往这个地址转账

使用json-rpc / web3 把账从这个地址转出来, （知道web3的签名，send raw transaction等)

知道当前节点的区块高度，知道当前的gas price

最好知道如何转账contract token (可选)

### 3.学习 solidity相关

下载metamask, 并链接到remix

根据demo，在inject web3的模式下部署一个最简单的hello word contract

知道如何使用remix 调用contract的 方法（getter, setter 等)

开始从头到尾的学习 solidity语法

写几个contract, 要有setter, getter ,view 方法， 知道如何调用这些方法

知道event log, 写对应的方法

### 4.使用web3.js 来调用contract

首先要熟悉javascript

然后创建一个普通的nodejs 项目，然后使用web3.js

使用web3.js 调用智能合约的各种方法，签名，查询余额

使用web3.js 调用event log

基本就可以了。

## 网络安全路径

财富自由之路。但是不要搞自己国家语言的网站。

必须先干一年web开发， 然后再弄这个。学习的先后顺序是：

### SQL 注入 .  必会

熟悉mysql, mssql server, 等

一般要使用sqlimap

### XSS 必会

一般需要找个XSS网站，然后注册，使用。

也可以自行搭建一个，特别简单。

### 安卓反编译  必会

用到的工具；

android sdk

apktools

root过的安卓设备

adb

frida

burpsuite 抓包

### kali

这是个工具包， 汇合了几十种常用的工具，

### metasploit

还是一个工具包，市面上流通的漏洞的集合


### 社工技术

注册个小飞机, 然后加群，社工技术太NB了。网络安全，正面强上是技术的提现，侧面迂回是头脑灵活的表现。能解决问题就行。

### 翻墙

这个不细说了。要么花钱买，要么自己弄。

### IP地址池

要找一个。学会使用。

最好的办法是，抓取目标网站的数据，每次请求都变换一次IP地址。

有很多渠道，自行搜索吧。


### 其他

自行学习。这个是一辈子的事情。

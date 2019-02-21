# 转行半年的前端的三次面试

### 离职

2018.12.25 从上家公司离职，离职前薪资 8-9k，总计半年 web 前端开发经验，坐标上海。

### 离职后的学习

2019.1.1 博客整理的差不多，花了两个礼拜过了遍 React 全家桶的文档，又花了一个礼拜给酷狗音乐加了 [React 实现](https://segmentfault.com/a/1190000017999756)，然后在简历上加了一句

> 了解 React

### 自我估值

2019.1.21 开始找工作，自己估值 11k，[当时的简历](https://github.com/xianshenglu/career/blob/master/resume/%E7%AE%80%E5%8E%86-%E9%99%86%E5%85%88%E7%94%9F-%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B%E5%B8%88.MD)。

#### 总体情况

|       | boss | 拉钩 | 前程无忧 | 智联 |
| ----- | ---- | ---- | -------- | ---- |
| 面试  | 2    | 1    | 1        | 1    |
| offer | 1    | 1    | -        | 1    |

不过前程无忧和智联都是后期才开始投的，感觉职位质量和数量都要好于 boss，而且筛选功能还不错，值得点赞。拉钩真的差。

**注释**：

- [ ] 表示没答出来或答错
- [x] 表示应该答对了。

#### 2019.1.24 某人数众多的公司（boss，15-25k）

**一面：未来的同事面**

- [x] translate, scale
- [ ] translate3D （笔试）
- [x] css3 盒模型
- [x] flex: auto 有什么表现
- [x] 跨域 有哪些方式
- [x] jsonp 为什么不能 post 请求
- [x] cors 后端要改哪个响应头
- [x] 讲一下 js 的数据类型
- [x] 讲一下 es5 原型链和 es6 class
- [x] 作用域链中变量的覆盖（笔试）
- [x] 讲一下深拷贝浅拷贝
- [x] JSON.parse 有什么问题（我引出来的）
- [ ] setTimeout 的一道题（口述的代码，然后又口述改代码，结果估计大家都弄晕了）
- [x] apply/call 作用与区别
- [x] webpack output 字段中有个 chunkHash 干什么用的
- [x] v-for 的用法 （笔试）
- [x] 讲一下 vue 生命周期
- [x] vue 的双向绑定原理 （我回答的是 v-model 原理，其实面试官问的是 defineProperty，然后我又解释了 defineProperty）
- [x] vue 如何动态添加响应式属性

**二面: 未来的上司面**

- [ ] 讲讲你平常做的性能优化（我提到了请求缓存和懒加载，然后说大部分的优化脚手架帮忙做了）
- [x] 脚手架帮你做了哪些优化呢
- [ ] treeShake 有用过么
- [ ] 你对缓存有哪些了解（因为我前面提到了请求缓存）
- [ ] <keep-alive> 用过么（因为我前面提到了请求缓存）
- [ ] \$addRouter 用过么
- [x] $router 和 $route 区别，（我说 $router.currentRoute === \$route，但是面试官好像不太满意，，，）
- [x] post 请求与 get 请求的区别（我多说了一句，post 比 get 慢）
- [ ] post 请求为什么比 get 请求慢（我说，因为 post 可能会多发一个 options 请求，他说不对，但又引出了下一个问题）
- [x] 什么情况下会有 options 请求
- [x] css 你有什么研究么，css 垂直居中

**总结**：一面没有摸到我的底，二面暴露了我的弱项（webpack 和性能优化），总体还是蛮有收获的。不过就是二面完美跳过了我的长处（javascript），诶。。。

**加班**：不加班（在填表时，有一个是否愿意加班一项，我选了 **否**，哈哈哈哈哈哈哈哈哈）。

**结果**：技术面过了，12K，年终奖 1 个月。

#### 2019.2.15 某中小金融公司（boss，15-30k）

**总监面？**

- [x] 你都用过哪些框架
- [x] Vue 和 jQuery 对于 DOM 的操作有什么不同
- [ ] cordova 安卓有了解么
- [ ] React Native 有做过么
- [ ] 网页有嵌入过 APP 么
- [ ] 双方怎么通信交互的原理，知道么
- [ ] webSocket 有用过么
- [ ] Echarts 有用过么？
- [x] 那你知道 Echarts 是干什么的么

**结果**：挂了
**总结**：需求不匹配，招聘信息估计是复制粘贴的。

#### 2019.2.20 某区块链创业公司（拉钩，8-15k）

**CTO 面（在华为做了十几年，写底层代码）**

**总结**：无关技术，更偏 HR 面（不过 hr 姐姐真的好让人心动啊啊啊啊啊）。

**加班**：通常 40h，紧急情况下 40-60h，一般不加班。

**结果**：过了，11-12k。

#### 2019.2.21 某无特征中小公司（智联，8-15k）

**未来的同事（组长）面**

- [x] 讲一讲盒模型
- [x] 讲一讲 position 的几个值
- [x] rem 什么意思，值有几种设法
- [x] vw 布局
- [x] 通过什么方式把 px 转 rem/vw
- [x] 水平垂直居中怎么实现
- [x] 响应式布局怎么实现
- [x] css 动画有几种实现方式，分别是怎么写的
- [x] js 数据类型
- [x] 基本类型和引用类型的区别
- [x] es6 新增的语法(非 api)
- [x] let const 区别，let 和 var 的区别
- [x] 箭头函数和普通函数区别
- [x] 讲一讲闭包
- [x] 闭包的优点和缺点
- [x] 举一个内存泄露的例子
- [x] 绑定事件的几种方式
- [x] 如果已经有一个 on 绑定的事件处理程序，后面仍然要用 on 绑定，如何保证前面的事件处理程序不被覆盖
- [x] 事件委托怎么实现
- [x] 事件委托为什么会有效
- [x] 为什么要用事件委托
- [x] jQuery 怎么绑定事件只触发一次
- [x] jQuery 链式调用的原理
- [x] React/Vue 怎样修改状态
- [x] Vue 父子兄弟组件通信
- [x] React 兄弟组件通信
- [x] 一个 html，有三张图片，那么访问这个 html，会发几个请求
- [x] jsonp 原理
- [x] 怎么解决跨域的问题
- [x] 如果发现页面内容没有渲染出来，怎么去 debug

**总结**：比较简单基础

**加班**：通常 40h，紧急情况下会需要加班，但是面试官 2 年内也没有加班到晚上 12 点，通常都是 40h。

**结果**：过了，11-12k，年终奖 2 个月。

### 我问面试官的问题

我有为自己准备一张[面试问题列表](https://github.com/xianshenglu/career/blob/d1fddb5832fcae5c96296bf329f89ce21b9b89ba/interview/interview.md)。如果面试还可以，通常我都会按照这个列表来问。

### 目前结果

准备去第一个。

### 旁白

- 我有点~~特立独行~~（独立思考）。
- 我的简历应该没有水分，或许还有些低估。虽然拿到的面试比较少，但如果拿到了，通常都有 offer。
- 我目前还没有刷面试题的习惯，因为即使在求职期，我也在按自己的规划在学习。我觉得基础打得好，绝大多数的面试题都是纸老虎。不过，要是在网上看到别人分享面试题，我倒是很乐意去看看，兴许有些题很有意思。
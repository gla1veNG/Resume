# 朱懋南的简历

## 个人信息

- 姓名：朱懋南 | 男 | 惠州
- 教育水平：本科 | 广东东软学院 | 软件工程
- 联系电话 & 微信：+86 132 4619 9667
- Email: 2993078435@qq.com
- Gitee: https://gitee.com/T1R
- Github: https://github.com/gla1veNG

## 掌握技术

#### 前端

- 熟练使用 HTML(5) + CSS(3)，具备处理复杂布局的能力；
- 熟练使用 Sass / Scss 等 CSS 预处理器协助组织样式；
- 熟悉 JavaScript 基本特性及原型，熟练掌握 ES6+ 的语法 和 DOM 操作，懂得使用 TypeScript；
- 熟练使用 jQuery 工具库，熟悉 jQuery 中的设计模式；
- 熟练使用 Vue 前端开发框架,掌握 Vue-router 和 Vuex 的使用，了解 Vue3 的性能；
- 熟悉 Webpack, Cmder, Vue CLI, Npm, Yarn 和 Parcel 等主流工程化工具；

#### 后端

- 熟悉部分 Node.js 的核心模块，能够简单的使用 Node.js；
- 熟悉 SQL 语句及用法,会使用 MySQL 数据库；

## 个人作品

#### Css　+　Js　实现皮卡丘

- 作品介绍 `Css` `JavaScript`

  皮卡丘动态演示是基于我用 Css 实现皮卡丘之后，通过添加 Js 的定时器实现的。我先用字符串存放皮卡丘的 Css 代码，然后分别准备一个 style 标签 和 div 标签，用定时器把 Css 代码同时写进这两个标签里，做到了代码和样式同步形成的动态演示，接着我还添加了几个可以控制播放速度的按钮，通过改变定时器时间来实现动态展示的速度由我自己控制。最后我重构了代码，使其简洁美观。

- 源码部分：https://gitee.com/T1R/PiKaChu

- 效果演示：https://t1r.gitee.io/pikachu/dist/

- 皮卡丘动态源码部分：https://gitee.com/T1R/PiKaChu-Dynamic

- 皮卡丘动态效果演示：https://t1r.gitee.io/pikachu-dynamic/dist/test.html

#### Js 实现 Canvas 画板

- 作品介绍 `JavaScript`

  Canvas 画板我首先的思路是先在页面画出点，然后再画线。

1. 画点 ：我先用监听一个点击事件，log 获取到我鼠标点击的位置（clientX，clientY），然后创建一个 div 写好样式，把 div 放到父元素里，在页面点击就出现点了。
2. 画线：刚开始我的想法是把点击事件改为鼠标移动事件，改了之后发现，移动的时候在不断画点，页面很卡顿，原因是 Js 操作 Dom 是很慢的，这么改动的话太频繁操作 Dom 了。我后面通过搜索 MDN 了解到了 canvas 。用 fillRect方法 画线就不会卡顿了，但是快速画线条时线条不够圆滑。最后用 lineTo方法 绘画直线，用 lineCap方法 解决了线条不圆滑的问题并且监听触屏事件实现了手机的Canvas。

- 源码部分：https://gitee.com/T1R/canvas
- 效果演示：http://t1r.gitee.io/canvas-demo-1/

#### 南瓜导航

- 作品介绍 `Flex布局` `JavaScript`

  “南瓜导航”是我一个人使用 CDN 引入 jQuery 实现的，我优先选择移动端着手，然后再做PC端，我使用 Figma 进行导航设计。搜索框我用 form 表单进行构造请求，我通过用百度搜索发现我查询的东西都在 `https://www.baidu.com/s？` 之后，于是我把 form 的 aciton 设置为 `https://www.baidu.com/s`，把 input 的 name 改为wd，完成了搜索功能。添加的网页模块,我是用哈希表组成的数组放到 localStorage 里面，然后我发现我可以不用把网页模块写死，我直接通过哈希表就可以进行渲染，我还监听了键盘事件，根据输入字母直接进入匹配的网页。最后我用媒体查询优化 PC 和 手机样式。

- 源码部分：https://gitee.com/T1R/Nav

- 效果演示：https://t1r.gitee.io/nav/dist/

#### 马内记账

- 作品介绍 `Vue CLI` `Vue` `vue-property-decorator` `TypeScript` `Webpack`

  “马内记账”是一款极简的记账应用，是基于Vue、VueRouter、Vuex 和 TypeScript 的单页面应用。 “马内记账”是由本人独立设计及实现，期间又碰到很多 webpack、TypeScript方面的问题，我把解决方法写在了[博客](https://www.yuque.com/u5007739/os13zh/sm6x5p0aeik33q9u)。 本代码是完全用TypeScript实现，用Vuex做了全局数据管理。

- 源码部分：https://gitee.com/T1R/Ma-nei

- 效果演示：http://t1r.gitee.io/manei/#/money

## 自我评价

Persistent. 热爱写代码，喜欢挖掘新知识和新技术。不害怕遇到困难，有着遇到问题必解决的执着，善于寻找解决问题的办法，有较强的自学能力，享受决解问题的过程。

Detail. 注重细节，对前端开发有热情，有良好的问题解决能力。关注代码质量，重视测试和调试，以确保高质量的代码，喜欢与不同背景和技能的团队成员协作，以实现共同的目标。

Standard. 一直坚持着 “拒绝重复” 的原则，主动进行代码重构，以消除重复，提高代码结构，减少复杂性，从而确保代码的可维护性和可扩展性。对变量和文件的命名严谨，确保代码准确地反映其功能和用途，能够与团队协作和代码维护。

Humor. 性格活泼开朗，幽默风趣。时间观念强，善于分配任务和设定优先级，不拖拉，能够在限定时间内完成任务。对新事物和挑战充满好奇心，具备很强的适应能力，永远怀揣着向别人学习的心态。


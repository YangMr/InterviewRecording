# InterviewRecording
面试录音



## 吴康佳面试录音 -  外包到南京国家电网

### 1. 自我介绍 (目前使用的技术栈、做过什么项目)

面试官,您好, 我叫王旭, 今年24岁, 老家来自河北承德, 目前从事前端开发已经有2年多时间,在这个期间我经历过的项目类型有 电商、 医疗、 直播、....等类型的项目.我所开开发过的项目有后台管理系统、小程序、h5端. 我目前掌握的技术栈有 vue、elementui、webpack、es6、uni-app 以及前端的一些基础技术栈.   在工作中我具有较强的抗压能力、学习能力.   能够接受适当的加班以及出差. 以上就是我的自我介绍



### 2. 项目的开发周期是多久? 

项目分为三期、第一期主要进行环境搭建以及一些基础功能 大概用时2周左右, 不到三周

第二期 商品管理 规格管理 图库



### 3. 在开发这个项目中你负责了哪些内容?

#### 前期

1. 在服务器上面创建项目仓库
2. 在本地使用vue脚手架创建项目
3. 将项目进行版本控制
4. 创建开发分支
5. 进行基础性的配置
   1. eslint配置
   2. pertter配置
   3. 配置使用git cz进行提交
   4. 配置message信息检测以及代码格式化检测
   5. git提交时代码修复
6. 配置项目跨域
7. 封装axios、api、本地存储、 以及公共的方法
8. 创建路由以及创建对应的组件

#### 开发

1. 负责用户管理、角色管理、权限管理等模块的开发
2. 负责登录、退出登录、修改个人信息、菜单渲染、布局等功能的开发
3. ....





### 4. 按钮权限如何实现? 

`vue自定义指令`

1. 登录之后会将按钮的权限数据存储到vuex
2. 定义权限指令
3. 在权限指令获取存储到vuex里面的按钮权限数据
4. 获取指令按钮定义的权限
5. 将按钮定义的权限字段在vuex里面存储的按钮权限列表中进行查询
6. 如果查到不到的话,说明当前的按钮没有对应的权限
7. 这个时候我们需要移除当前的按钮



### 5. 自定义指令配置? 

- 全局
- 局部
- 如何实现





### 6. 小程序的页面跳转都有哪些方式?



### 7. Vue3.0相较于2.0增加了哪些内容?

Es6 proxy代码 --- 

ref reactive



### 8. ref 与 reactive?

1. 定义数据层面:
2. 原理方面:



### 9. 类型转换

```
let str = "123"

0.1 + 0.3 

Number()
parseInt()
parseFlot()
运算符
str - 1 = 122 1231

// number类型转字符串   js基础

let num = 1

// 1

num + ''


// 2

num.toString()

// 3
String(num)

```

## 吴康佳面试录音 -  武汉盛聚祥物物联科技
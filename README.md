# Frontend Practice · JavaScript 练习集

本仓库用于记录前端 JavaScript 学习过程中的代码练习，涵盖 ECMAScript 核心语法、Web APIs 操作以及 JS 进阶相关实践。

## 📚 知识点范围

### 一、ECMAScript 基础与核心
- 变量声明（`let`、`const`）、数据类型、类型转换
- 运算符、流程控制（`if`、`switch`、循环）
- 函数：声明、表达式、参数默认值、返回值、作用域（全局/局部）、闭包
- 数组：遍历（`for`、`forEach`）、高阶方法（`map`、`filter`、`reduce`、`join`）
- 对象：属性访问、增删改查、方法定义、`for...in` 遍历
- 字符串：模板字符串、`padStart`/`padEnd`、`trim`
- 常用内置对象：`Math`（随机数、取整）、`Date`（时间戳、格式化）

### 二、Web APIs 与 DOM 操作
- DOM 元素获取：`querySelector`、`querySelectorAll`
- 元素内容与属性操作：`innerText`、`innerHTML`、`classList`、`dataset`、样式修改
- 事件监听：`addEventListener`，事件类型（`click`、`change`、`submit`、`input`、键盘/鼠标事件）
- 事件对象（`e.target`、`e.preventDefault`、`e.stopPropagation`）
- 事件委托（动态元素事件绑定）
- 节点操作：创建、添加、删除、克隆
- 定时器：`setTimeout`、`setInterval`、`clearTimeout`、`clearInterval`

### 三、BOM 与浏览器相关
- `window` 对象：全局作用域、`location`（页面跳转、刷新、`hash`）、`navigator`（浏览器信息）、`history`（前进/后退）
- 本地存储：`localStorage`（永久）、`sessionStorage`（会话）
- JSON 序列化与反序列化：`JSON.stringify`、`JSON.parse`
- 事件循环（Event Loop）理解：同步/异步、宏任务/微任务

### 四、JS 进阶与综合应用
- 数据持久化方案（本地存储 + 对象数组管理）
- 数组 `map` + `join` 动态渲染表格（无框架）
- 表单数据收集、校验与重置
- 基于事件委托的增删改查（添加、删除、编辑）
- 动态生成唯一 ID（基于现有数据最大 ID + 1）
- 时间格式化（手动补零、`toLocaleString`）
- 模块化思想：数据层、视图层、控制层分离（简单 MVC 实践）

## 🛠️ 运行方式
所有练习均为纯前端实现，无需安装依赖。克隆仓库后，直接用浏览器打开任意 `.html` 文件即可查看效果。

## 📦 仓库结构
- 根目录包含独立练习文件（如本地存储访问记录、表单验证等）
- 子文件夹按功能模块组织（如学生信息管理、组件化练习等）

## 🧪 后续计划
- 加入 `fetch`/`axios` 与后端 API 交互
- 学习正则表达式进行高级表单验证
- 引入 `class` 语法重构代码
- 使用 `try/catch` 进行错误处理
- 探索 `localStorage` 封装成工具类

## 📧 联系
欢迎交流学习，可通过 GitHub Issues 提出建议。

**持续更新中…**
#questions

from video static blog with next js and markdown

### 主题

react 中 app.js, index.js

### 描述

react 中 app.js, index.js 分别干什么的，有啥区别

### 我的理解

index.js：通常只 export 一个 function ; can import name.module.css files but not globals.css;

而 global.css 用在\_app.js 中

但是为什么是\_app，不是 app?

### 主题

let

### 描述

在方程中有的时候用 let, 有的时候不用 let 来 new 一个新东西。在我看来都应该 new.
例如：

```javascript
for (let i = 0; i < 3; i++) {}

cat.map((post, index) => <Post key={index} post={post} />);
```

### 我的理解

Na

### 主题

fs

### 描述

import fs from 'fs'
调用文件有其他用法吗？

### 我的理解

fs 模块是 nodejs 官方提供的，用来操作文件的模块。它提供了一系列的方法和属性，用来满足用户对文件的操作需求

fs.redaFile() 用来读取文件中的内容
fs.writeFile() 用来向指定文件中写入内容

### 主题

className

### 描述

视频 22:20
html 里面的 className 写作 class = ‘card’

### 我的理解

直接不是说不这么写吗

### 主题

fallback

### 描述

视频里 30:45

```javascript
return {
  res,
  fallback: false,
};
```

### 我的理解

If fallback is false , then any paths not returned by getStaticPaths will result in a 404 page. 就是说 false 会返回 404. 那么 true / blocking 会返回什么。404 还有其他写法吗

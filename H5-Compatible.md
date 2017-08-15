## Meta

### 设值缩放
```<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no" />```
- width：设值 viewport 宽度（或 device-width）
- height：设值 viewport 高度（通常情况下，设值宽度会自动解析高度，故可不设值）
- initial-scale：设值初始化缩放比例
- minimum-scale：设值最小缩放比例
- maximum-scale：设值最大缩放比例
- user-scalable：是否允许手动缩放

### 隐藏地址栏（IOS Safari）
<meta name="apple-mobile-web-app-capable" content="yes" />

### 状态栏样式（IOS Safari：default、black、black-translucent）
<meta name="apple-mobile-web-app-status-bar-style" content="black" />

### 禁用数字识别（IOS：电话；Android：邮箱）
<meta name="format-detection"content="telephone=no, email=no" />

### 360浏览器启用极速模式
<meta name="renderer" content="webkit">

### IE浏览器使用最新模式
<meta http-equiv="X-UA-Compatible" content="IE=edge">

### Win Phone 点击无高光
<meta name="msapplication-tap-highlight" content="no">

### 手持设备 viewport 优化
<meta name="HandheldFriendly" content="true">

### 微软老式浏览器
<meta name="MobileOptimized" content="320">

### UC浏览器应用模式
<meta name="browsermode" content="application">

### QQ浏览器应用模式
<meta name="x5-page-mode" content="app”>

### UC浏览器强制竖屏
<meta name="screen-orientation" content="portrait">

### QQ浏览器强制竖屏
<meta name="x5-orientation" content="portrait">

### UC浏览器强制全屏
<meta name="full-screen" content="yes">

### QQ浏览器强制全屏
<meta name="x5-fullscreen" content="true”>


## 电话、短信、邮件

### 电话
<a href=“tel:13855667788">拨打电话</a>

### 短信
<a href="sms:10086">发送短信</a>

### 邮件
<a href="mailto:joenix@qq.com">发送邮件</a>

### 邮件的复合使用
1. 多个收件人
<a href=“mailto:joenix@qq.com;example@qq.com">发送邮件</a>
2. 抄送与密件抄送
<a href=“mailto:joenix@qq.com?cc=example@qq.com&bcc=example@qq.com">发送邮件</a>
3. 主题邮件
<a href="mailto:joenix@qq.com?subject=theme">发送邮件</a>
4. 内容体邮件（HTML自动识别，包括链接、图片等）
<a href="mailto:joenix@qq.com?body=<img src='img/theme.jpg' />http(s)://joenix.com/">发送邮件</a>

###

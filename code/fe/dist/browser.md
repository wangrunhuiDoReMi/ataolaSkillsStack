# 浏览器

## 传递数据的媒体类型

* 互联网媒体类型

* 内容类型

* MIME 类型


## URL

* URL 的全称是通用资源标识符


## SQL注入

* 曾在某浏览器插件测试，你若用form表单去提交可以进行SQL注入，但若是你没有form表单而是通过Ajax提交，那它就不能进行SQL注入。这里表单到底在哪种情况下需要呢？还是由于历史原因。

* 知乎的登陆注册，百度的搜索也还是有表单的，并不完全是Ajax。


## Cookie

* 一个没有被阉割的cookie

    * 名称

    * 内容

    * 域

    * 原始大小

    * 路径

    * 过期时间

    * 仅Http

    * 安全



## 代码

* 判断用户浏览器

```js
 var is = {
        ie: navigator.appName == 'Microsoft Internet Explorer',
        java: navigator.javaEnabled(),
        ns: navigator.appName == 'Netscape',
        ua: navigator.userAgent.toLowerCase(),
        version: parseFloat(navigator.appVersion.substr(21)) ||
            parseFloat(navigator.appVersion),
        win: navigator.platform == 'Win32'
    };

    is.mac = is.ua.indexOf('mac') >= 0;
    if (is.ua.indexOf('opera') >= 0) {
        is.ie = is.ns = false;
        is.opera = true;
    }
    if (is.ua.indexOf('gecko') >= 0) {
        is.ie = is.ns = false;
        is.gecko = true;
    }
```



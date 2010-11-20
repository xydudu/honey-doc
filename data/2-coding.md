# 开始编码

## 打开调试模式

    HN.openDevMode()

* 当页面调用上面函数时，则将引入source文件，并且打开debug;
* 调试时请使用 *HN.debug()* 函数

        
## HN.debug
调试函数，直接传要显示的信息。如有console则调用console显示，如没有则在页面上显示。

## HN.go
这是一个开始的函数，开发人员请把自己的代码写在此函数里。调用如下：
    
    HN.go($files, $fun);

* $files 为需要引入的框架，模块，文件
* $fun 执行函数，引入文件载入后执行的函数


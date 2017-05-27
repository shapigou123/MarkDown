### Welcome to use MarkDown

# 标题

**加粗**

- 列表

## 内嵌式链接
- 外部链接：[百度](https://www.baidu.com)

- 内部链接：连接仓库的其他文件[demo1](demo1.md)


- 内部链接2：链接到本文档的其他部分[代码块demo](demo2.md#代码块-demo)


## 引用式链接
- 外部链接：[百度](https://www.baidu.com)

- 内部链接：连接仓库的其他文件[demo1](demo1.md)


- 内部链接2：链接到本文档的其他部分[代码块demo](demo2.md#代码块-demo)


# 图片 demo

- 图片的markdown语法  
```
![alt](url text)
```
- 外部图片 demo  
![baidu][baidu_logo]
![baidu](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png "baidu")

- 仓库内的图片  
![][images]
![](images/0print.jpg "images")

# 引用 demo
单次引用  
> 这是一个引文
  
出自《出处》  

多次引用  
>> 这是多重引用  

# 代码块 demo

- 行内代码  
这个代码用来声明变量是`var a = 10;`,打印变量的内容是`console.log(a)`

- 块式代码  
```javascript
var a = 10;
console.log(a);
```


<!--- 下面是本文档中用到的链接 -->
[百度]: https://www.baidu.com
[baidu]: https://www.baidu.com
[demo1]: demo1.md
[代码块 demo]: demo2.md#代码块-demo

[baidu_logo]: https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/bd_logo1_31bdc765.png
[images]: images/0print.jpg


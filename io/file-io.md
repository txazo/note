[http://blog.csdn.net/u014686399/article/details/71247437](http://blog.csdn.net/u014686399/article/details/71247437)
[https://wenku.baidu.com/view/4cd353fcfab069dc502201c6?pcf=2&re=view&utm_medium=social&utm_source=qq](https://wenku.baidu.com/view/4cd353fcfab069dc502201c6?pcf=2&re=view&utm_medium=social&utm_source=qq)

#### 文件I/O

#### 文件读

* 系统调用read()
* 内核查找页缓存
    * 页缓存命中，直接返回
    * 页缓存未命中，触发缺页异常，挂起
* 数据从内核空间拷贝到用户空间

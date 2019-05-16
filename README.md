# static
用于存放一些静态资源。这些资源只是测试用，不能太过于频繁的请求。

## 使用方式

`http://raw.githack.com/xiafl/static/master/` 作为根路径，  
项目中的其它资源，则相对于这个路径就好了  
  
如 项目中的 `markdown/local_self.css`:
```
<link rel="stylesheet" type="text/css" href="http://raw.githack.com/xiafl/static/master/markdown/local_self.css" />
```
## 原理
可以参考 [http://raw.githack.com] 网站的说明。

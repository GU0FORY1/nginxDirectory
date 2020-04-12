## nginx配置


```
location   /book {
    autoindex on;
    autoindex_exact_size on;
    charset utf-8,gbk;
    autoindex_localtime on;
    autoindex_format json;  # 返回信息为josn格式
}
```

## 路径配置

代码中`path`变量改为目录路径

```
-book       //目录浏览资源位置 这里默认是book 可自行修改
-index.html //目录文件
```


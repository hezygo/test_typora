####  解析Typora序列号

> 位置: 阿里云/工具库/Window/Typora

```shell
> pip install -r requirements.txt
> python typora.py "Path:....\Typora\resources\app.asar" cache_dir
> cp .\example\License.js cache_dir\dec_app\License.js 
> python typora.py -u  cache_dir\dec_app output\app.asar
> cp output\app.asar Path:....\Typora\resources\app.asar
> node example/keygen.js
```

[参考]: https://www.cnblogs.com/wangchuanxiansheng/p/15810168.html


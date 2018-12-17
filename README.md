# char-layout

字框实验项目，可用于字框算法实验，前端基于 jQuery+Raphael，后端基于 Python+Tornado。

## 运行

```
pip install -r requirements.txt
python main.py
```

如果遇到端口被占用的错误，可结束端口上的进程
```sh
sudo lsof -i:8001
sudo kill -9 PID号
```

## 参考资料

- [Bootstrap 3 中文文档](https://v3.bootcss.com)
- [Tornado 官方文档中文版](https://tornado-zh.readthedocs.io/zh/latest/)
- [Raphael.js 图形库文档](http://dmitrybaranovskiy.github.io/raphael/)

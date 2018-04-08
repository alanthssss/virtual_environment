# 创建、使用、退出虚拟环境

---

## 创建虚拟环境

### 此处注意创建虚拟环境的版本

此处以web开发中Flask、Django对应的虚拟环境为例，如需创建Tornado的web开发、Scrapy的爬虫开发等环境，可以类推。
```
# 创建Python2虚拟环境
mkvirtualenv -p python2.7 flask_py2
     # 以Flask为例，虚拟环境名称自取，此处为了给Flask使用起名为flask_py2
# 创建Python2虚拟环境
mkvirtualenv -p python3 django_py3
     # 以Django为例,起名原因同上
```

### 虚拟环境创建成功后，会自动工作在这个环境上

```
deactivate  # 退出虚拟环境
```

## 使用虚拟环境

没有工作在虚拟环境上的时候

```
# 命令
workon
```

`workon 虚拟环境名称  # 工作到对应的虚拟环境上`

`workon + 两次tab  # 显示可以选用的虚拟环境`


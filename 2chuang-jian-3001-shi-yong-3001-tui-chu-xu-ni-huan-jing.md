# 创建、使用、退出虚拟环境

---

## 创建虚拟环境

### 此处注意创建虚拟环境的版本


此处以web开发中Flask、Django对应的虚拟环境为例。
如需创建web开发中的Tornado、爬虫开发中的Scrapy等环境，可以类推。

**小白特别注意此处：虚拟环境名仅是一个名字，需要使用的模块还要后续配置，创建虚拟环境时重要的是python版本选择,虚拟环境名能够见名知意并方便选择即可。**

```
# 创建Python2虚拟环境
mkvirtualenv flask_py2
     # 以Flask为例，虚拟环境名称自取，此处为了给Flask使用起名为flask_py2
# 创建Python2虚拟环境
mkvirtualenv -p python3 django_py3
     # 以Django为例,起名原因同上
```
**此处虚拟环境名仅作举例，Flask、Django使用不用版本python时注意Python版本**

如新经资讯项目使用Python3的Flask：

```
mkvirtualenv -p python3 f3pyinfo
```


### 虚拟环境创建成功后，会自动工作在这个环境上

命令行前面有`(虚拟环境名)`表示在这个虚拟环境中

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


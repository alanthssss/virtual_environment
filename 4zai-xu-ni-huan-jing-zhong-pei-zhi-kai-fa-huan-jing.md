# 配置虚拟开发环境

---

## 获取配置需要的文件

在配置好的虚拟环境中执行命令  
**注意目录（可自选，此处放在了桌面）**

```
pip freeze > ～/Desktop/requirements.txt
```

## 在当前虚拟环境中进行配置

```
pip install -r ～/Desktop/requirements.txt
```

## 配置成功,其他常见虚拟环境命令

常用  
列举虚拟环境用`workon+两次tab`  
查看虚拟环境中的包，可在虚拟环境下`pip list`或者`pip freeze`

不常用

```
lsvirtualenv    # 列举所有的环境。
cdvirtualenv    # 导航到当前激活的虚拟环境的目录中，比如说这样您就能够浏览它的 site-packages。
cdsitepackages   # 和上面的类似，但是是直接进入到 site-packages 目录中。
lssitepackages     # 显示 site-packages 目录中的内容。
```




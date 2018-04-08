# Windows创建虚拟环境
---

将文件拖拽到命令行窗口可以快速得到文件路径（在windows系统中更常用）。 
##虚拟环境包安装配置

###配置内部命令pip2、pip3

* 安装Python解释器时自动配置环境变量，pip即是内部命令； 
* 如果提示pip不是内部命令，把python文件下的Scripts的文件路径加入计算机环境变量。

既有Python2又有Python3时为pip对应最后安装的python解释器。

###安装虚拟环境包
```
pip2 install virtualenv
pip3 install virtualenv
```

###区分Python2和Python3的virtualenv
将python2目录下的Scripts目录里的virtualenv.exe改为virtualenv2.exe，在保证python的环境变量都加到了计算机环境变量的情况下。
我们就可以
使用’virtualenv2 虚拟环境名’ 来创建py2的虚拟环境，
用’virtualenv 虚拟环境名’ 创建py3的虚拟环境了。

**建议将python3目录下的Scripts目录里的virtualenv.exe改为virtualenv3.exe
以严格区分防止误操作。**
## 创建存放虚拟环境的文件夹并切换到该目录

 - `md [盘符:\][路径\]新目录名` 或者 `mkdir [盘符:\][路径\]新目录名`
 - `cd [盘符:\][路径\]新目录名`
 
 可以在窗口中完成上面的创建及打开目录的操作，并在该目录下`shift+右键`选择进入power shell进行命令操作。
 
## 创建虚拟环境



```
virtualenv2 虚拟环境名  # 创建Python2解释器对应的虚拟环境
virtualenv3 虚拟环境名  # 创建Python3解释器对应的虚拟环境

```

 - Windows中创建虚拟环境之后没有自动工作在这个虚拟环境中。
 - 在虚拟环境中工作前需要激活。

## 激活虚拟环境

 - cd进入虚拟环境下的Scripts文件夹
 - activate 激活虚拟环境 
- 命令行前面有`(虚拟环境名)`表示在这个虚拟环境中

## 在虚拟环境中pip安装要使用的模块


```
pip install -r requirements.txt
```


## 退出虚拟环境
`deactivate`退出虚拟环境







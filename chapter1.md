# 虚拟环境包安装配置

## 虚拟环境包安装

```text
sudo pip install virtualenv
sudo pip install virtualenvwrapper
sudo easy_install virtualenvwrapper  # Mac（用上一条不成功时用这一条）
```

## 虚拟环境包配置

1、创建目录用来存放虚拟环境

```text
mkdir $HOME/.virtualenvs
```

2、打开~/.bashrc\(Mac下为.bash\_profile\)文件，并添加如下：

```text
export WORKON_HOME=$HOME/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh
```

**注意**： Mac的`virtualenvwrapper.sh`不在上面代码对应的目录下时：

* 用`which virtualenvwrapper.sh`找到`virtualenvwrapper.sh`的路径；
* 在上面的代码中写在相应的位置。

3、加载配置

```text
 source ~/.bashrc 
 source ~/.bash_profile  # Mac
```


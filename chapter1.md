# 虚拟环境包安装配置

---

## 虚拟环境包安装

```
sudo pip install virtualenv
sudo pip install virtualenvwrapper
sudo pip easy_install virtualenvwrapper  # Mac
```

## 虚拟环境包配置

```
1、创建目录用来存放虚拟环境
mkdir $HOME/.virtualenvs

2、打开~/.bashrc(Mac下为.bash_profile)文件，并添加如下：
export WORKON_HOME=$HOME/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh

3、运行
source ~/.bashrc
source ~/..bash_profile  # Mac
```




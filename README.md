# 虚拟开发环境配置by知鱼

---

## 虚拟环境
虚拟环境 virtual environment
### 介绍
使用虚拟环境安装开发环境，可以避免包的混乱和版本的冲突。
虚拟环境是Python解释器的副本，在虚拟环境中你可以安装扩展包，为每个程序单独创建的虚拟环境，可以保证程序只能访问虚拟环境中的包。
不会影响系统中安装的Python解释器，从而保证解释器的整洁。

### 单独说明
本文档主要说明以Ubuntu为例的Liunx系统以及Mac OS系统下Python虚拟开发环境的配置。
Windows下命令略有不同，故单独说明。
### 学习要求
掌握Ubuntu、Mac系统中的Python虚拟开发环境配置使用即可，原因如下：
 * 实际开发中，用远程调试，服务器为Linux系统。
 * 课程学习中
  - 可以在Ubuntu、Mac系统中进行学习。
  - 可以在Windows系统中：
     - 通过Xshell连接Ubuntu虚拟机进行终端操作；
     - 通过Pycharm连接Ubuntu虚拟机进行远程调试。
   
---

## 复习

### 1.pip
####安装Python的包
```
pip install 包名称
pip3 install 包名称
```
####查看当前环境下安装的Python包
`pip list` 或者 `pip freeze`

### 2.查看当前使用Python解释器的路径
#### Pycharm中
在运行结果上方可以看到
* 当前使用的Python解释器的路径
* 当前运行的Python程序的路径
![](/assets/屏幕快照 2018-04-07 下午9.29.13.png)

#### 终端/命令行/控制台中

* 可以在终端直接输入`which python`查看

* 在Python环境中执行如下命令查看
```
import sys
sys.executable
```
此处要求区分以下两条命令：
  * `sys.executable`查看解释器路径 
  * `sys.path`查看包路径
  
###3.重定向

* `>`将输出结果写在目标文件中，新建或覆盖目标文件
* `>>`将输出结果追加在目标文件末尾





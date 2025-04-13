# note

## 25/04/14 用现有的 docker image 运行

Linux开发环境完全搞不明白，考虑用WSL共享文件夹？但是WSL和ubuntu等系统也不太一样。

slim版本并没有什么用，因为不包含内嵌模型。

一种配置的思路是：

* WSL运行linux系统，安装python
* pycharm使用WSL的环境创建python解释器
* 使用WSL虚拟机运行
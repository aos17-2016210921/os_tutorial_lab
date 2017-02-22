# 高级操作系统 OS demo

### 1 下载、配置流程

#### 1.1 安装虚拟机

​	这个随意，只要装一个合适的Linux就行。在win10的VMware和Mac的Parallel都测试通过。

#### 1.2 安装Git

​	虽然这里不一定要用Git，从网页直接下载.zip也行，不过以后会常用，最好一起学习了。

#### 1.3 从Git获取这个repo

```shell
$ git clone https://github.com/chyyuu/os_tutorial_lab.git
```

#### 1.4 一个可能出现的问题

 ![q1](https://github.com/lighttime0/pictures/blob/master/q1.png)

​	疑似是在64位电脑进行32位编译时，有的库不一样。解决方案：

```shell
$ sudo apt-get install gcc-multilib
```

#### 1.5 试用

![run_helloworld](https://github.com/lighttime0/pictures/blob/master/run_helloworld.png)






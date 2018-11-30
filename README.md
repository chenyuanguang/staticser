# staticser 
> 版本 `@staticser` 1.0.4.

## 介绍：

>可以实现服务的启动,静态服务器；


## 作者：

>陈元广


## 查看node版本：

    "必须保证node在9.0以上版本"

## 下载安装

检查是否安装过staticser

```bash
    staticser -V
```
### 初次安装

```bash
    npm install -g staticser
```

### 版本更新

#### 命令方式

```bash
    npm update -g staticser
```

#### 笨拙有效的方式（windows权限问题很恶心）

##### windows

>1、先找到全局npm和npm-cache(一般都在C:\Users\用户名\AppData\Roaming)
>
>2、删除npm-cache(防止从缓存中读取staticser)
>
>3、打开npm文件夹
>
>4、把如下文件删除：staticser
>
>5、打开npm/node_modules文件夹：删除staticser
>
>6、再次进行全局安装
>

```bash
    npm install -g staticser
```
##### mac

>1、先找到命令所在的文件夹(一般都在/usr/local/bin/)
>
>2、打开文件夹
>
>3、把如下文件删除：staticser
>
>4、打开/usr/local/lib/node_modules文件夹：删除staticser
>
>5、再次进行全局安装
>

```bash
    npm install -g staticser
```


## 创建项目：

```bash

    cd [project-name]   #项目根目录

    staticser

```
example：

```bash
    
    cd projectTest

    staticser

```



# gitbook 安装

本文主要记录 `gitbook` 安装步骤



## 1. 安装 npm

这里使用 `nvm` 来安装和管理版本

首先下载和安装 nvm 

```
https://github.com/coreybutler/nvm-windows/releases
```

安装完成以后，打开命令行判断是否安装成功

```
nvm -v
```

获取可安装的node版本

```
nvm ls available
```

安装对应版本的node，这里我们安装 `12.18.1` 的版本

```
nvm install 12.18.1
```

安装完成之后指定使用的node版本

```
nvm use 12.18.1
```

这个时候就会切换到对应的node版本

```
node -v
npm -v
```



## 2. 安装 gitbook

执行以下命令安装 `gitbook`

```
npm install -g gitbook-cli
```
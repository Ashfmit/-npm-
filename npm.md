## npm

### 初始化(package.json文件)

```shell
# 创建package.json
# 让用户输入项目相关信息
npm init
# 使用默认参数创建 package.json
npm init -y
```



### 下载包

```shell
npm install 包名
# 简化写法
npm i 包名
# 根据 package.json 文件里面的记录下载对应的包
npm i
# 下载指定版本包
npm i 包名@版本号
```



### 卸载包

```shell
npm uninstall 包名
# 简化命令
npm uni 包名
```



### 运行简化后的命令(package.json中scripts的命令)

```shell
npm run 简化命令
```

## 查看当前的下包镜像

```node
npm config get registry
```

## 将下包的镜像源切换为淘宝镜像源

```
npm config set registry=https://registry.npm.taobao.org/
```

## 检查镜像源是否下载成功

```
npm config get registry
```

## 检查生产依赖

```
cnpm -v
```

## nrm下载

```
npm i nrm -g
```

## 查看所有可用的镜像源

```
nrm ls
```

## 将下包的镜像源切换为淘宝镜像

```
nrm use taobao
```










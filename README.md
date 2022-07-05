# enn-sqlite3-binary

## Description
因为追求项目中node_modules的文件大小缩减，只存放适配项目中不同平台，不同架构的二进制文件,减少体积大小。

## 用法
[node-sqlite3](https://github.com/TryGhost/node-sqlite3)

## 文件说明
相关对应版本如下
|  platform   | arch  |sqlite3|
|  ----  | ----  |----|
| linux  | arm | ^5.0.2|
| win32  | x64 |^5.0.2|

## 如何添加新的平台或者架构的二进制文件
原仓库 (node-sqlite3)[https://github.com/TryGhost/node-sqlite3]  


### 查看目标环境相关配置
napi-v{napi_build_version}-{platform}-{libc}-{arch} 
```
  const  process = require("process");
  console.log(`napi-v${process.versions.napi}-${process.platform}-{libc}-${process.arch}`);
```

https://github.com/OctoberCity/NeteaseCloudMusicApi/releases/download/v4.0.1/linux-arm.tar.gz


 


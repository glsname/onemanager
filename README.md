<p align="center">
  <img height="100px" src="./logo.png" center />
</p>

# [Onemanager-php](https://github.com/qkqpttgf/OneManager-php)

onemanager是一款OneDrive（国际版、个人版、世纪互联版）目录列表程序，可实现上传下载文件，文件永久直链，文件目录加密等功能。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&tdl_anchor=github&tdl_site=0&appUrl=https://github.com/glsname/onemanager/tree/main)


### 依赖

- CFS：需要使用 CFS 持久化配置数据（挂载数据盘的配置目录）

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`

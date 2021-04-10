<p align="center">
  <img height="100px" src="./logo.png" center />
</p>

# [Onemanager-php](https://github.com/qkqpttgf/OneManager-php)

onemanager是一款OneDrive（国际版、个人版、世纪互联版）目录列表程序，可实现上传下载文件，文件永久直链，文件目录加密等功能。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&tdl_anchor=github&tdl_site=0&appUrl=https://github.com/glsname/onemanager/tree/main)


### 依赖

- CFS：需要使用 CFS 持久化配置数据（挂载数据盘的配置目录）[标准存储0.35元/GB,配置文件通常在10kb左右，白嫖]

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
2. 部分文件路径可能存在空格或者其他特殊字符，导致无法正常链接


## 成本计算

#### 云托管

为2020年09月21日及之后开通云托管的新用户提供1个月的免费体验，具体额度见下表。免费时间以**创建第一个云托管服务**当日计起，有效期1个月。
**注：在09月21日之前的用户，每月均可享有免费额度，之后的用户，仅有1个月**

| 资源细项 | 资源量              |
| -------- | ------------------- |
| CPU      | 720（核 × 小时）    |
| 内存     | 1440 （GiB × 小时） |
| 流量     | 500GB               |
| 构建     | 600分钟             |

 免费额度可支持您体验：
- 1个1核2GiB的实例常驻运行30天。
- **2个0.5核1GiB的实例常驻运行30天。**
- 1个2核4GiB的实例常驻运行15天。

#### 文件存储(cfs)
|资源项|存储最大值区间|收费标准|
| -------- | ------------------- | ------------------- |
|标准存储|0-10TB|0.35元/GB/月|

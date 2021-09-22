<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [Discuz! Q](https://gitee.com/Discuz/Discuz-Q)

全新Discuz! 开源版本，一款私域流量经营工具。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-DZQ&branch=dzq-v3.0.210917)

### 配置
- `MysqlHost`: 数据库地址
- `MysqlPort`: 数据库端口
- `MysqlUsername`: 数据库用户
- `MysqlPassword`: 数据库用户密码
- `MysqlDatabase`: 数据库名称
- `AdminAccount`: 管理员账号
- `AdminPassword`: 管理员密码


### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- Cfs：使用 Cfs 持久化存储静态资源，日志等

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`

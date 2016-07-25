# OStorage Swift Deployment Tools
---
[TOC]


---
## 前言
    安装脚本主要实现Swift、Keepalived与ELK的安装功能，包括一些常用的命令脚本，如远程执行命令、拷贝文件以及部署ssh无密码访问等等，具体的使用说明，参见doc目录详细说明文档。

## 目录说明
    |---|/                  根目录
    |------|bin             脚本文件
    |------|conf.d          配置文件
    |------|data            运行产生的数据
    |------|doc             安装工具详细文档
    |------|error_log       脚本运行时日志文件
    |------|expect_script   expect脚本，实现人机交互
    |------|export_userinfo 导出用户环境变量模板
    |------|sample-conf     配置文件模板
    |------|tools           工具命令脚本
    |------|install.sh      单节点安装脚本
    |------|install_all.sh  集群安装脚本
    |------|README.md       说明文档
## 1. Swift安装
        Swift的安装目前分为两种情况，单节点安装与集群安装，分别运行不同的脚本。安装之前需要修改配置文件，根据安装需求不一样，修改的配置也各不相同，如使用keystone的时候，需要修改conf.d/localrc.sh中对应的参数，在下面详细安装时会有具体介绍。
### 1.1 使用keystone安装
        使用Keystone安装时，首先需要确定使用哪一种接口，当前版本支持v2.0和v3的接口，在具体的配置项进行配置。
#### 1.1.0 通用配置

#### 1.1.1 v2.0 接口
    
#### 1.1.2 v3 接口
### 1.2 不使用Keystone安装
#### 1.2.1 Swift v1.0接口
## 2. Keepalived安装
## 3. ELK安装
## 4. FAQ









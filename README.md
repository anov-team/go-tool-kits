# go-tool-kits

## 介绍
anov-go平台功能增强工具包

## 功能
- [x] 私有化部署-快速一键预览
- [x] 支持anov-ds服务器代理请求(解决跨域问题)
- [x] anov-api可视化接口服务(仅限内网支持)
- [ ] anov-go数据转换服务
- [ ] 本地代理服务，快速启动本地mock服务，支持http/https和websocket接口
- [ ] go-tool-kits版本升级热更新
- [ ] ...

## 示例DEMO
<p align="left">    
    <img src="/public/go-tool-kits.gif" width="600" />
</p>

[go-tool-kits视频演示](https://gitee.com/anov/go-tool-kits/raw/master/public/go-tool-kits.mp4)

<video src="/public/go-tool-kits.mp4" controls="controls" width="600" loop  autoplay></video>

### 下载地址
推荐地址：[国内源-安装包下载](https://gitee.com/anov/go-tool-kits/releases/)  

备用地址：[通用源-安装包下载](https://www.github.com/anov-team/go-tool-kits/releases/)


## 安装教程
### 1. 环境检查
- 系统环境：Linux/Mac/Windows
- 系统版本：Ubuntu 16.04+/Mac OS X EI Capitan/Windows 8.1+
- 系统架构：x86_64/x86/arm64/arm/ppc64le/s390x

### 2. 安装包下载
下载地址在上面:point_up:，可以点击[下载地址](#下载地址)
### 3. 本地安装
执行安装包，按提示进行安装


## 使用说明

### 1. 项目包预览：

#### 私有化部署包预览方式

1. 自建服务-技术研发人员
安装http代理服务器，如：Apache/Lighttpd/Tomcat/WebSphere/IIS/Nginx/Caddy/OpenLiteSpeed/NodeJS等。      
需自行安装，并进行站点配置，再启动服务。

2. go-tool-kits工具-非技术人员    
使用anov-go平台工具包，快速一键预览，与宿主机环境隔离，安全无污染，即关即停。
#### 使用步骤
1. 在平台生成并下载【私有化部署包】
2. 解压私有化部署包
3. 拖拽或点击解压后的私有化部署包到上传区域
<p align="left">    
<img src="https://gitee.com/anov/go-tool-kits/raw/master/public/kit1.png" width="600" />
</p>

4. 启动服务，自动打开预览

### 2. ANOV-API可视化接口服务【仅限内网】
ANOV-API 是高效、易用的可视化接口管理 API Mock 服务，通过简单配置生成动态接口，并支持项目下所有接口统一管理维护，让团队协作更高效。

#### 适用场景 
1、快速生成动态mock接口数据    
2、根据不同入参，返回定制化数据   
3、支持动态入参，返回动态响应数据    
4、多人协同管理同一项目接口   





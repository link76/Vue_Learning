# Vue项目初始化步骤
## 前端初始化
- 安装Vue脚手架
- 使用Vue脚手架创建项目
- 配置Vue路由
- 配置Element-UI组件库
- 安装axious库

### 安装Vue脚手架
  可参考官网安装教程：https://cli.vuejs.org/zh/guide/installation.html  
  Vue CLI 4.x 需要 Node.js v8.9 或更高版本 (推荐 v10 以上)。故首先需要下载或更新Node  
  Node在官网（ http://nodejs.cn/download/ ）下载对应版本  
  安装完成Node后，打开命令行输入 `npm install -g @vue/cli` 即可下载Vue脚手架  
  因为npm的仓库服务器地址在国外，当下载速度较慢时，可以使用以下命令转换为淘宝镜像：  
  `npm install -g cnpm --registry=https://registry.npm.taobao.org`  
  然后再使用命令 `cnpm install -g @vue/cli` 进行安装
  安装完成后，重新打开命令行通过 `vue -V` 命令查看版本，无误即安装完成。  
### 使用Vue脚手架创建项目
  可直接使用命令行用图形界面创建项目 使用命令：`vue ui`  进入图形界面创建项目  
  ![Vue_ui.](https://github.com/link76/Vue_Learning/blob/main/photoSrc/Vue_ui.png)  
### 配置Vue路由
   在创建项目中，需勾选Router  
  ![Vue_Router.](https://github.com/link76/Vue_Learning/blob/main/photoSrc/Vue_Router.png)  
### 配置Element-UI组件库
  项目创建完成后，进入插件/添加插件，搜索vue-cli-plugin-element并添加  
  ![Vue_elementUI.](https://github.com/link76/Vue_Learning/blob/main/photoSrc/Vue_elementUI.png)  
### 安装axious库
  然后进入依赖项，点击安装依赖，在运行依赖中搜索axios并添加  
  ![Vue_axious.](https://github.com/link76/Vue_Learning/blob/main/photoSrc/Vue_axios.png)  
  
## 后端初始化
- 安装MYSQL数据库
- 配置项目相关信息
- 启动项目
- 使用postman测试接口

### 安装MYSQL数据库
  可在官网下载安装mysql，或者使用提供mysql服务的软件  
### 配置项目相关信息
  在命令行下执行nmp install 安装相关依赖项  
  设置配置文件等信息  
### 启动项目
  在命令行下执行node .\app.js(对应的文件)启动项目，若无报错则表明项目正常启动  
### 使用postman测试接口
  打开postman，根据接口文档中所提供的接口，进行post/get等请求进行功能测试  

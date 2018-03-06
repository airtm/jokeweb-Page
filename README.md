#项目名称 20180305
## jokeweb-Page
woaixiaaiwo/jokeweb-page

#项目说明
1、jokeweb（https://github.com/woaixiaaiwo/jokeweb）的前端页面，技术选型目前是html5 + vue2.0（es6）+ nodejs

2、环境准备：
	* 本地node环境搭建，安装nodejs，node.js的官方地址为：https://nodejs.org/en/download/ 国内地址为http://nodejs.cn/download/
	* 安装cnpm（淘宝镜像服务器），由于许多npm包都是在国外，安装起来特别慢。安装命令：npm install -g cnpm --registry=https://registry.npm.taobao.org
	* 安装webpack 安装命令：cnpm install webpack -g
	* 安装全局的vue-cli脚手架,用于帮助搭建所需的模板框架 安装命令：cnpm install -g vue-cli    安装完后，可以输入vue，然后回车，如果出现vue的信息，则说明安装成功了。
	这些会默认安装在该目录下 C:\Users\shaoming.hu\AppData\Roaming\npm\node_modules
3、创建项目：
	* 在项目文件夹内，右键git bash here，输入:vue init webpack my-vue(项目文件夹名)，回车，等待一小会儿
	* cd my-vue 进入此文件夹，在利用命令：cnpm install，回车，等待一小会儿，回到项目文件夹，会发现项目结构里，多了一个node_modules文件夹（该文件里的内容就是之前安装的依赖）。
	* 在命令行里继续输入 cnpm run dev来测试环境是否搭建成功  默认访问地址http://localhost:8080

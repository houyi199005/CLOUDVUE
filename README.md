一、运行
第一次运行，需要下载依赖包，执行avicit-platform6-cloud-vue目录下的

1. Install Yarn.bat
2. Install Package.bat

以后每次启动直接运行

3. Server Build.bat

二、配置项
avicit-platform6-cloud-vue\vue.config.js

'/api': {
        target: 'http://117.36.76.70:8239'           //演示数据地址
        
        target: 'http://10.64.21.247:10001'          //开发地址，需要连接VPN

三、开发功能页面的路径，按照功能建立文件夹

avicit-platform6-cloud-vue\src\views\avic\pt\cloud

四、菜单配置地址
http://localhost:3000/menu/manage

菜单授权配置，登录平台页面

系统==》vue菜单授权        
角色==》容器云Vue开发者  授权容器云菜单



五、代码合并

由于不能使用统一的代码仓库，暂定每周五下午4点，将本周开发内容提交给任旭


项目的演示页
avicit-platform6-cloud-vue\src\views\avic\pt\demo

学习资料：

https://cn.vuejs.org/v2/guide/

https://www.antdv.com/docs/vue/introduce-cn/




推荐开发工具使用VS Code开发

# 安装环境
第一步: 指向淘宝镜像
        npm config set registry https://registry.npm.taobao.org/

第二步:	全局安装 vue-cli
        npm install vue-cli -g

第三步: 新建目录 vue-resume
        cd Desktop
	      mkdir vue-resume
	      cd vue-resume
        
第四步: 初始化项目
        vue init webpack .
	      npm install
	      npm run dev 【跑起来，自动打开默认浏览器】

第五步: 安装依赖代码高亮库
        npm install marked prismjs --save-dev

第六步: 找到src/App.vue
        修改fullStyle和fullMarkdown即可
 

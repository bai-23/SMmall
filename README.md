# 商城项目1.0

## Project setup

```
npm install
```

### Compies and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```



## 目录结构

```javascript

┌- 
├-	public/
    ├-  favicon.ico			// ico
    ├-	index.html
├-	src/
    ├-	assets/				// 项目资源
           ├- css/			
           ├- img/
    ├-	components			// 公共组件
           ├- common/		// 纯公共组件（扩展其他项目）
           ├- content/		// 当前项目公共组件
    ├-	common/    			// 公共js文件
    ├-  network/			// 网络请求文件
    ├-	router/				// 路由文件
    ├-  store/				// 状态管理文件
    ├-	views/				// 主页面视图
           ├- category/
           ├- home/			// 主页视图
    ├-	App.vue				// root组件
    ├- 	main.js				// 入口
├-	.gitignore				
├-	babel.config.js
├-	package.json	
├-	package-lock.json		
├-	LICENSE					// 许可
├-	README.md
└-	
```


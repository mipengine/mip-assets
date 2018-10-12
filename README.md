# mip cache 非组件静态资源文件

## 各文件用途说明

- az.gif：0像素图片，用于优化cdn的预链接时请求；
- mip404.html：Cache页面404时，，与容器交互进行原网页跳转返回的页面；
- mipfallback.html：MIP 未通过校验，发生302跳转返回的页面；
- prefetch-v2.html：MIP V2版本静态资源预取
- prefetch.html：MIP V1版本静态资源预取
- oob：out of band文件交互使用（支持跨域）
- deps：jquery、zepto等静态文件

以上静态文件存放于Cache的/static/(例如：https://c.mipcdn.com/static/）路径下。

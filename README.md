# Meting-API

## 写在前面

之前的版本解决了一些部署上的问题，但可能还有一些问题，比如：

- 后端php与js依旧不易自行部署
- 新的音乐源扩展、维护困难
- 即使在国内访问，如果后端部署在国外，腾讯系音乐仍然无法解析

## 尝试解决

- [x] 后端采用js重写，仅保留aplyer必要api
- [x] 轻量框架，可简单部署到vercel/cloud workers 等平台
- [x] 模块化插件系统，轻松添加音乐源以及各种类型
- [x] 采用了我也不知道怎么想到的jsonp，在浏览器端解析，腾讯系音乐理论上不会有地域限制了

缓慢开发中
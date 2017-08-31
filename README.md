# CORS跨域

## 本地模拟AJAX跨域请求

- 修改 hosts 文件模拟两个不同的域名(xx.com和yy.com)
- xx.com 域名下文件向 `http://yy.com`发起AJAX请求
- 通过添加 Access-Control-Allow-Origin 响应头字段实现跨域
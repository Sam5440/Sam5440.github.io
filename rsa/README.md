# 在线rsa加密密码

## 为用户提供在线使用公钥加密密码的网页

公密固定为

```js
var PUBLIC_KEY='MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQCsVuv5GHoiyScnofgJ28cJPNsw9iuqgnEdAkXiCHciPrF0ZthT2acwe3qRT63TklzO89EkY6EgEmUBbj4av9juZrwTIiyjS1y8kmnXBsRw+W0FPNoCf7FmPEE/vX2hlUVo9DX+cit6t8fvNGiR4bj3Jz7KupnjSa9MB2hLVgMg8QIDAQAB';
```

> 网页设计参考 [html网页中js使用RSA非对称性加密请求字符串_我爱女神李忠英的博客-CSDN博客_html rsa](https://blog.csdn.net/ed679ed/article/details/120883026)

> 使用js `<script src="https://cdn.bootcss.com/jsencrypt/3.0.0-beta.1/jsencrypt.js"></script>`

## 未来

* [ ] 从url处获得public_key,动态公钥
* [ ] 动态公钥时候接入短网址系统
* [ ] 更好的ui设计

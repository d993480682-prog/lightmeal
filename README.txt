轻食管家 PWA 手机网页应用

文件：
- index.html：应用主程序
- manifest.webmanifest：添加到主屏幕配置
- sw.js：离线缓存
- icon-192.png / icon-512.png：应用图标

如何在 iPhone 上使用：
1. 将整个 lightmeal_pwa 文件夹部署到支持 HTTPS 的静态网站托管服务，不能只上传 index.html，必须保留所有文件的相对路径。
2. 在 iPhone 的 Safari 打开部署后的网址。
3. 点击 Safari 的分享按钮，选择“添加到主屏幕”。
4. 从主屏幕图标打开，即可像独立 APP 一样使用。

也可以先直接打开 index.html 预览核心功能；但 PWA 安装和离线缓存需要 HTTPS 网站环境。

数据说明：体重、饮食、饮水和采购勾选数据保存在当前浏览器的 localStorage。清除浏览器网站数据可能导致记录丢失。当前版本不提供云同步。

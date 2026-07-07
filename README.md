# wenqusec.com

问渠安全实验室官网源码归档。

> 问渠清如许，安全活水来。

## 内容

本仓库当前内容同步自阿里云服务器线上目录：

```text
/www/wwwroot/wenqusec.com
```

包含首页 HTML、CSS、JavaScript、字体、图片、站点运行配置与静态资源文件。

外部链接与外部图床资源保持原样，例如：

- 微信公众号文章
- CSDN 页面
- Bilibili 页面
- `img.anheng.tech` / `pic.anheng.tech` 等外部图片资源

## 目录

```text
.
├── index.html
├── css/
├── js/
├── images/
├── fonts/
├── .well-known/
└── .user.ini
```

## 本地预览

静态页面可直接用任意本地 HTTP 服务预览：

```bash
python3 -m http.server 8080
```

然后打开：

```text
http://127.0.0.1:8080/
```

## 后续同步

后续如需更新，以服务器线上目录为准重新同步后提交：

```bash
rsync -a --delete --exclude '.git' --exclude 'README.md' --exclude '.nojekyll' \
  /path/to/wenqusec.com/ ./
```

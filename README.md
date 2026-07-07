# wenqusec.com

问渠安全实验室官网静态源码归档。

> 问渠清如许，安全活水来。

## 内容

本仓库当前内容来自 `https://wenqusec.com/` 公开站点的静态资源镜像，包含首页 HTML、CSS、JavaScript、字体和同域图片资源。

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
└── fonts/
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

如果需要从阿里云服务器同步原始工程目录，请使用服务器上的真实源码目录覆盖本仓库后重新提交。当前本地可见 SSH 记录为：

```text
ssh peiyimiao@39.107.90.4 -p 4257
```

但本机没有可用的免密身份，因此本次先提交公开站点静态镜像。

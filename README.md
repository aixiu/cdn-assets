# cdn-assets

[![](https://data.jsdelivr.com/v1/package/gh/aixiu/cdn-assets/badge?style=rounded)](https://www.jsdelivr.com/package/gh/aixiu/cdn-assets)

> 精于心，简于形

## 使用方法

```html
直接引用使用方法：https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径
```

```html
https://cdn.jsdelivr.net/gh/zngw/cdn@1.0/copyright.js
```

```html
https://cdn.jsdelivr.net/gh/aixiu/cdn-assets/placeholder/d570170f4f12.svg
```

jsdelivr路径： https://www.jsdelivr.com/package/gh/aixiu/cdn-assets

## 其它使用方法

版本号不是必需的，是为了区分新旧资源，如果不使用版本号，将会直接引用最新资源，除此之外还可以使用某个范围内的版本，查看所有资源等，具体使用方法如下：

```html
// 加载任何Github发布、提交或分支
https://cdn.jsdelivr.net/gh/user/repo@version/file

// 加载 jQuery v3.2.1
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/dist/jquery.min.js

// 使用版本范围而不是特定版本
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2/dist/jquery.min.js
https://cdn.jsdelivr.net/gh/jquery/jquery@3/dist/jquery.min.js

// 完全省略该版本以获取最新版本
https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js

// 将“.min”添加到任何JS/CSS文件中以获取缩小版本，如果不存在，将为会自动生成
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js

// 在末尾添加 / 以获取资源目录列表
https://cdn.jsdelivr.net/gh/jquery/jquery/

```

## 具体简单使用方法

```html
https://cdn.jsdelivr.net/gh/aixiu/cdn-assets/placeholder/文件名
```

例如：

```html
https://cdn.jsdelivr.net/gh/aixiu/cdn-assets/placeholder/d570170f4f12.svg
```

<details>
<summary>使用注意事项</summary><br>
<p>使用前请看下面的使用政策</p>
https://www.jsdelivr.com/terms/acceptable-use-policy-jsdelivr-net

第4条写明禁止的使用行为其中就包括存放视频、文件备份或者其他大量的文件。所以不要试图在jsdelivr存放太大的媒体文件！随时会被阻断连接！

上面一条还有一条禁止的行为是说开设一个图床并且使用jsdelivr存储上传的图片。所以也不要当图床用！

此外，第5条也强调在国内使用jsdelivr一定要遵纪守法。违规内容会被不警告直接封停！

</details>

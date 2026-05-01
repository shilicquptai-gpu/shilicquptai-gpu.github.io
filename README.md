# 我的个人博客

这是一个可以直接托管到 GitHub Pages 的静态个人博客起点。

## 文件结构

```text
.
├── index.html
├── about.html
├── styles.css
├── assets/
│   └── blog-mark.svg
└── posts/
    ├── index.html
    └── hello-world.html
```

## 本地预览

可以直接双击 `index.html` 打开，也可以在这个目录运行：

```bash
python3 -m http.server 8000
```

然后访问：

```text
http://localhost:8000
```

## 发布到 GitHub Pages

1. 在 GitHub 新建仓库，仓库名建议为 `你的用户名.github.io`。
2. 把这些文件上传或推送到仓库的 `main` 分支。
3. 打开仓库 `Settings` -> `Pages`。
4. 在 `Build and deployment` 里选择从 `main` 分支发布。
5. 等待几分钟后访问 `https://你的用户名.github.io`。

## 下一步可以改什么

- 把 `我的个人博客` 改成你的博客名。
- 修改 `about.html` 里的自我介绍。
- 复制 `posts/hello-world.html` 来创建新文章。
- 在 `posts/index.html` 和 `index.html` 里添加新文章链接。

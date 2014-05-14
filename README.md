本简历 fork 自 David Hamp-Gonsalves 的 [Resume][r]。

## 准备环境

1. 安装 Node.js 模块：
   `npm install`
2. 将本目录中的 CSS 文件复制到 `node_modules/markdown-resume/assets/css`：
   `cp *.css node_modules/markdown-resume/assets/css`

## 生成简历

```shell
node node_modules/markdown-resume/bin/md2resume resume.md       # 生成 HTML 格式
node node_modules/markdown-resume/bin/md2resume --pdf resume.md # 生成 PDF 格式
```

[r]: https://github.com/davidhampgonsalves/resume

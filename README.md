# Gnorimía 个人主页

单文件静态站点，直接托管在 GitHub Pages。

## 文件

| 文件 | 说明 |
| --- | --- |
| `index.html` | 站点本体（HTML + CSS + JS 全内嵌，无外部资源依赖） |
| `.nojekyll` | 关闭 Jekyll 处理，让 Pages 原样托管 |
| `gnorimia.html` | 本地源文件（未纳入版本库） |

## 更新流程

```bash
cp gnorimia.html index.html
git add index.html
git commit -m "更新页面"
git push
```

推送后 GitHub Pages 会在约一分钟内重新构建。

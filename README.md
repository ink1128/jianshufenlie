# GitHub Pages 发布说明

这个文件夹已经整理成可直接上传到 GitHub Pages 的静态站点结构：

- `index.html`
- `images/`

## 上传步骤

1. 在 GitHub 新建一个仓库
2. 打开终端并进入这个文件夹
3. 执行下面命令

```powershell
cd "C:\Users\Administrator\Desktop\test\github-pages-meiosis"
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<你的GitHub用户名>/<你的仓库名>.git
git push -u origin main
```

## 开启 Pages

1. 打开仓库页面
2. 进入 `Settings`
3. 打开 `Pages`
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`，目录选择 `/root`

几分钟后访问：

`https://<你的GitHub用户名>.github.io/<你的仓库名>/`

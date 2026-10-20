# 个人主页

一个无需安装依赖、可直接在浏览器打开的单页个人主页。

## 个性化

打开 `index.html`，把“你的名字”、介绍、技能、邮箱和 GitHub 地址换成自己的内容。

## 本地预览

直接用浏览器打开 `index.html` 即可。

## 上传到 GitHub

在 GitHub 新建一个空仓库（先不要勾选创建 README），然后在项目文件夹的终端运行：

```bash
git init
git add .
git commit -m "Create personal homepage"
git branch -M main
git remote add origin https://github.com/你的用户名/仓库名.git
git push -u origin main
```

之后每次修改后，可以运行：

```bash
git add .
git commit -m "Describe your changes"
git push
```

若想把主页公开成网站，可在仓库的 **Settings → Pages** 中选择 `main` 分支和根目录作为发布来源。
# codex-1

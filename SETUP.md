# 发布说明

## 当前目录

这个文件夹已经连接到个人主页仓库：

`https://github.com/Sunshine-1023/Sunshine-1023`

新版主页包含：

```text
Sunshine-1023/
├── README.md
├── .gitignore
├── assets/
│   ├── header.svg
│   ├── footer.svg
│   ├── miku-hero-wide.jpg
│   ├── miku-01.jpg ... miku-05.jpg
│   └── SOURCES.md
└── .github/
    └── workflows/
        └── profile-3d.yml
```

## 发布命令

先在当前目录检查改动：

```bash
cd "/Users/sunshine/Documents/Codex/2026-08-03/new-chat/outputs/github-profile"
git status
git diff -- README.md SETUP.md assets/header.svg assets/footer.svg
```

确认后发布：

```bash
git add README.md SETUP.md .gitignore .github assets
git commit -m "style: refresh profile with Miku theme"
git push origin main
```

## 3D 贡献图

`.github/workflows/profile-3d.yml` 会每天更新 3D 贡献图。首次使用时，在 GitHub 仓库的 **Actions** 页面手动运行一次 `GitHub-Profile-3D-Contrib`。

生成成功后，在 `README.md` 中删除下面两个注释标记即可显示：

- `<!-- 3D CONTRIBUTION START`
- `3D CONTRIBUTION END -->`

## 主页建议

- Bio：`Undergraduate Student · Applied ML & Recommender Systems`
- 将推荐系统、手机成瘾预测和数据管理系统设为 Pinned repositories。
- 公开仓库中可能存在姓名或学号样式的文件名，发布前建议再检查一次隐私信息。

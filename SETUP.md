# 安装说明

## 1. 创建个人主页仓库

在 GitHub 新建公开仓库：

- Owner：`Sunshine-1023`
- Repository name：`Sunshine-1023`
- Visibility：Public
- 建议勾选 “Add a README file”

仓库地址最终应为：

`https://github.com/Sunshine-1023/Sunshine-1023`

## 2. 上传本文件夹中的内容

仓库根目录应包含：

```text
Sunshine-1023/
├── .gitignore
├── README.md
├── assets/
│   ├── header.svg
│   ├── current-focus.svg
│   ├── anime-student.svg
│   └── campus-night.svg
└── .github/
    └── workflows/
        └── profile-3d.yml
```

注意：GitHub 网页上传文件时不方便创建以点开头的 `.github` 文件夹。最简单的办法是先上传 `README.md` 和 `assets`，3D 工作流可稍后通过本地 Git 或 GitHub 网页的 “Create new file” 添加。

## 3. 启用 3D 贡献图

1. 打开主页仓库的 **Actions**。
2. 选择 **GitHub-Profile-3D-Contrib**。
3. 点击 **Run workflow**。
4. 等待运行完成，仓库会出现 `profile-3d-contrib` 文件夹。
5. 编辑 `README.md`，删除：
   - `<!-- 3D CONTRIBUTION START`
   - `3D CONTRIBUTION END -->`

之后工作流每天凌晨自动更新。公开贡献通常不需要额外 Token。

## 4. 建议顺手完善

- 给 4 个仓库补充简短 Description 和 Topics。
- 在个人资料中添加一句 Bio，例如：`ML & Recommender Systems Learner · Python / Vue / Django`。
- 推荐的学生身份 Bio：`Undergraduate Student · Applied ML & Recommender Systems`。
- 将推荐系统项目和数据管理系统设为 Pinned repositories。
- 主页稳定后，可按需要添加邮箱或社交链接；不要公开不想被搜索到的个人信息。

## 5. 隐私检查

你的公开数据管理仓库目前存在包含姓名和学号样式的文件名。建议确认这些信息是否希望长期公开；若不希望，应在仓库中清理文件，并留意 Git 历史仍可能保留旧版本。

## 6. 第三方卡片说明

统计卡片来自公共服务，偶尔可能因限流短暂加载失败。主页的核心介绍、项目和本地 SVG 不受影响。

# 如何将此仓库设置为私有 / How to Make This Repository Private

[中文](#中文说明) | [English](#english-instructions)

---

## 中文说明

### 将GitHub仓库设置为私有的步骤

如果您想要将此仓库设置为私有，以限制访问权限，请按照以下步骤操作：

#### 方法一：通过GitHub网页界面

1. **登录GitHub账户**
   - 访问 [github.com](https://github.com) 并登录您的账户

2. **进入仓库设置**
   - 导航到您的仓库：`https://github.com/shuyuanwang1030/rnaseq`
   - 点击仓库顶部的 **Settings（设置）** 选项卡

3. **更改可见性设置**
   - 在设置页面中，滚动到底部找到 **Danger Zone（危险区域）**
   - 点击 **Change repository visibility（更改仓库可见性）**
   - 选择 **Make private（设为私有）**
   - 按照提示输入仓库名称以确认更改
   - 点击确认按钮

4. **验证更改**
   - 仓库现在应该显示为私有状态
   - 只有您和您授权的协作者才能访问此仓库

#### 方法二：使用GitHub CLI

如果您已经安装了 [GitHub CLI](https://cli.github.com/)，可以使用命令行：

```bash
gh repo edit shuyuanwang1030/rnaseq --visibility private
```

### 私有仓库的注意事项

- **访问控制**：将仓库设为私有后，只有您和被明确授予访问权限的协作者才能查看和访问仓库内容
- **协作者管理**：您可以在 Settings → Collaborators 中添加或删除协作者
- **GitHub Actions**：私有仓库在GitHub Actions中有不同的免费额度限制
- **公共分叉**：任何现有的公共分叉将保持公开，除非所有者单独将其设为私有

### 添加协作者

如果您需要与特定人员共享私有仓库：

1. 进入仓库的 **Settings → Collaborators and teams**
2. 点击 **Add people（添加人员）**
3. 搜索并选择要添加的GitHub用户
4. 选择适当的权限级别（读、写或管理员）
5. 发送邀请

---

## English Instructions

### Steps to Make This GitHub Repository Private

If you want to make this repository private to restrict access, follow these steps:

#### Method 1: Via GitHub Web Interface

1. **Log into Your GitHub Account**
   - Visit [github.com](https://github.com) and sign in to your account

2. **Navigate to Repository Settings**
   - Go to your repository: `https://github.com/shuyuanwang1030/rnaseq`
   - Click on the **Settings** tab at the top of the repository page

3. **Change Visibility Settings**
   - In the Settings page, scroll down to the **Danger Zone** section
   - Click on **Change repository visibility**
   - Select **Make private**
   - Follow the prompts to type the repository name to confirm the change
   - Click the confirmation button

4. **Verify the Change**
   - The repository should now show as private
   - Only you and authorized collaborators can access this repository

#### Method 2: Using GitHub CLI

If you have [GitHub CLI](https://cli.github.com/) installed, you can use the command line:

```bash
gh repo edit shuyuanwang1030/rnaseq --visibility private
```

### Important Considerations for Private Repositories

- **Access Control**: Once private, only you and explicitly granted collaborators can view and access the repository
- **Collaborator Management**: You can add or remove collaborators in Settings → Collaborators
- **GitHub Actions**: Private repositories have different free tier limits for GitHub Actions
- **Public Forks**: Any existing public forks will remain public unless their owners make them private separately

### Adding Collaborators

If you need to share your private repository with specific people:

1. Go to **Settings → Collaborators and teams** in your repository
2. Click **Add people**
3. Search for and select the GitHub user you want to add
4. Choose the appropriate permission level (Read, Write, or Admin)
5. Send the invitation

---

## Additional Resources / 其他资源

- [GitHub Documentation: Setting repository visibility](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility)
- [GitHub Documentation: Managing access to your repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/managing-teams-and-people-with-access-to-your-repository)

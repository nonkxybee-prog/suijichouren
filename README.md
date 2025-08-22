# 随机抽取工具

一个简洁高效的随机抽取工具，适用于活动抽奖、随机选人等场景。支持自定义名单、防重复抽取等功能。

## 功能特点

- 自定义名单设置，支持逗号或顿号分隔
- 随机抽取动画效果
- 防重复抽取选项
- 已抽取人员记录
- 响应式设计，适配各种设备

## 本地开发

### 环境要求

- Node.js 14+
- pnpm

### 安装依赖

```bash
pnpm install
```

### 启动开发服务器

```bash
pnpm dev
```

访问 http://localhost:3000 查看应用

## 构建项目

```bash
pnpm build
```

构建后的文件将保存在 `dist` 目录中

## 部署到GitHub Pages

### 准备工作

1. 将代码推送到GitHub仓库
2. 确保已完成项目构建

### 部署步骤

#### 方法一：手动部署

1. 构建项目:
   ```bash
   pnpm build
   ```

2. 进入构建目录:
   ```bash
   cd dist
   ```

3. 创建一个新的Git仓库并提交:
   ```bash
   git init
   git add .
   git commit -m "Deploy to GitHub Pages"
   ```

4. 推送到GitHub仓库的gh-pages分支:
   ```bash
   git push -f https://github.com/你的用户名/你的仓库名.git main:gh-pages
   ```

5. 在GitHub仓库设置中:
   - 进入 Settings > Pages
   - 在 Source 部分，选择 gh-pages 分支
   - 点击 Save

#### 方法二：使用GitHub Actions自动部署

(详细步骤略，可参考GitHub Pages官方文档设置自动部署工作流)

## 许可证

本项目采用MIT许可证
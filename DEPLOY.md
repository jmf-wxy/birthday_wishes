# 部署到 GitHub Pages 指南

## 步骤 1: 创建 GitHub 账号
1. 访问 https://github.com
2. 点击 "Sign up" 注册账号
3. 验证邮箱完成注册

## 步骤 2: 创建新仓库
1. 登录后点击右上角 "+" → "New repository"
2. Repository name 填写: `birthday-wishes` (或你喜欢的名字)
3. 选择 "Public" (公开仓库才能用 GitHub Pages)
4. 点击 "Create repository"

## 步骤 3: 上传文件
1. 在仓库页面，点击 "uploading an existing file"
2. 把这两个文件拖拽上传:
   - `index.html`
   - `SPEC.md`
3. 点击 "Commit changes"

## 步骤 4: 启用 GitHub Pages
1. 在仓库页面，点击 "Settings" (设置)
2. 滚动到 "GitHub Pages" 部分
3. Source 下拉菜单选择: "Deploy from a branch"
4. Branch 下拉菜单选择: "main"，文件夹选择 "/ (root)"
5. 点击 "Save"

## 步骤 5: 获取你的网址
1. 等待 1-2 分钟部署完成
2. 回到仓库主页面
3. GitHub Pages 链接格式: `https://你的用户名.github.io/birthday-wishes/`

## 如何让朋友访问:
1. 先在网站设置寿星名字
2. 点击"分享"按钮复制链接
3. 把链接发给朋友

## 注意事项:
- 祝福数据仍然存储在各自浏览器中
- 不同设备访问看到的是同一份祝福墙（因为都用同一个 localStorage key）
- 如果需要真正的数据共享，需要添加后端服务

---

**或者更简单的方式**: 如果你只是想临时分享，可以用 https://surge.sh 或 https://netlify.com 的 drag & drop 功能，直接拖拽文件夹即可获得链接。

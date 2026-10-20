# GitHub 发布保姆级步骤（照做即可，约 10 分钟）

> 目标：把「装修ERP-求职作品集」变成任何人点开就能看的公开网页链接。
> 你需要：一个 GitHub 账号（免费注册，2 分钟）。

---

## 第 1 步：注册 / 登录 GitHub

1. 浏览器打开 https://github.com
2. 没有账号 → 点右上角 **Sign up**，用邮箱注册（邮箱验证一下即可）
3. 有账号 → 点 **Sign in** 登录

## 第 2 步：新建仓库（Repository）

1. 登录后，点右上角 **+** 号 → 选 **New repository**
2. 仓库名（Repository name）填：`erp-portfolio`
3. **Public** 保持选中（Public = 公开，别人能看）
4. 其他选项全部不动，直接点底部绿色按钮 **Create repository**
5. 创建后会进入一个空白页面，**先别关**，往下看第 3 步

## 第 3 步：上传文件

1. 在空白页面中间，点 **uploading an existing file**（上传已有文件）
2. 把「装修ERP-求职作品集」文件夹里的 **全部内容** 拖进上传区
   - 要拖的内容 = index.html、README.md、LICENSE、assets 文件夹（共 4 项）
   - 注意：**是拖文件夹里面的内容，不是拖文件夹本身**
3. 页面底部 Commit changes 下面，点绿色按钮 **Commit changes**
4. 等待几秒，文件列表出现就说明上传成功

## 第 4 步：开启 Pages（生成公开链接）

1. 回到仓库首页，点顶部菜单 **Settings**（设置）
2. 左侧菜单往下找，点 **Pages**（在左侧菜单的 Code and automation 分组里）
3. 在 **Branch** 那里：下拉框选 `main`，旁边文件夹选 `/ (root)`，点 **Save**
4. 页面顶部会显示：`Your site is live at https://你的用户名.github.io/erp-portfolio/`
5. 第一次部署需要 **1~3 分钟**，稍等后刷新即可访问

## 第 5 步：验证并分享

1. 打开上面的链接，确认页面正常显示（有图片、有联系方式）
2. 把这个链接发给招聘方即可 —— **任何人点开就能看，无需登录**

---

## 常见问题

| 问题 | 解决 |
|------|------|
| 打开链接显示 404 | 刚部署还没生效，等 1-3 分钟再刷新；或确认 Settings → Pages 里 Branch 选的是 main |
| 图片显示不出来 | 确认上传时 **assets 文件夹** 整个上传了，且里面 3 张图都在 |
| 忘记网址 | 进仓库 Settings → Pages，顶部就有你的链接 |
| 想改内容 | 本地改完 index.html，重新上传覆盖同名文件，Pages 会自动更新（约 1 分钟生效） |

## 你的链接长这样

```
https://你的用户名.github.io/erp-portfolio/
```

> 例：用户名是 `tanyongxing`，链接就是 `https://tanyongxing.github.io/erp-portfolio/`

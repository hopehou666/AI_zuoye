# 发布到 GitHub Pages（关机也能打开链接）

本地 `127.0.0.1` / localtunnel 需要电脑开着。用 **GitHub Pages** 后，链接长期有效。

仓库已在本地完成首次提交（`main` 分支），按下面做即可。

## 一、网页操作（约 3 分钟）

1. 打开 https://github.com/new ，登录你的账号  
2. Repository name 填：`jiaoyu-ai-zuoye`（可改）  
3. 选 **Public** → 点 **Create repository**  
4. 创建后，页面会显示推送命令。在本机 PowerShell 进入作业目录执行（把 `你的用户名` 换成自己的）：

```powershell
cd "$env:USERPROFILE\Desktop\作业"
git remote add origin https://github.com/你的用户名/jiaoyu-ai-zuoye.git
git push -u origin main
```

5. 打开仓库页面 → **Settings** → 左侧 **Pages**  
6. **Source** 选 `Deploy from a branch`  
7. Branch 选 `main`，文件夹选 `/ (root)` → **Save**  
8. 等 1～2 分钟，刷新 Pages 设置页，会出现站点地址，形如：

```text
https://你的用户名.github.io/jiaoyu-ai-zuoye/
```

## 二、提交用的三个链接（把用户名和仓库名替换掉）

```text
https://你的用户名.github.io/jiaoyu-ai-zuoye/
https://你的用户名.github.io/jiaoyu-ai-zuoye/01-智能体/agent.html
https://你的用户名.github.io/jiaoyu-ai-zuoye/02-多维表/table.html
https://你的用户名.github.io/jiaoyu-ai-zuoye/03-交互网页/index.html
```

中文路径一般可直接打开；若打不开，把路径段做 URL 编码后再试。

## 三、以后改了文件怎么更新

```powershell
cd "$env:USERPROFILE\Desktop\作业"
git add -A
git commit -m "Update homework pages"
git push
```

推送后等约 1 分钟，线上链接自动更新。

## 需要我代你 push 时

回复我这两样即可：
1. 你的 GitHub 用户名  
2. 仓库是否已建好（或让我用 `gh` 登录后自动建）

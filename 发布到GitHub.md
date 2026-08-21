# 发布到 GitHub Pages（关机也能打开链接）

仓库已推送：https://github.com/hopehou666/AI_zuoye

## 还差一步：打开 Pages

1. 打开 https://github.com/hopehou666/AI_zuoye/settings/pages  
2. **Source** 选：`Deploy from a branch`  
3. **Branch** 选：`main` ，文件夹选：`/ (root)`  
4. 点 **Save**  
5. 等 1～2 分钟，刷新本页，会出现站点地址

## 发布成功后的链接（可直接交作业）

```text
https://hopehou666.github.io/AI_zuoye/
https://hopehou666.github.io/AI_zuoye/01-agent/agent.html
https://hopehou666.github.io/AI_zuoye/02-table/table.html
https://hopehou666.github.io/AI_zuoye/03-web/index.html
```

## 以后改了文件怎么更新

```powershell
cd "$env:USERPROFILE\Desktop\作业"
git add -A
git commit -m "Update homework pages"
git push
```

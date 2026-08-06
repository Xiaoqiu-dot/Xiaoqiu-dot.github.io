# Xiaoqiu-dot.github.io

个人主页，通过 GitHub Pages 部署，访问地址：https://Xiaoqiu-dot.github.io

## 部署步骤

1. 在 GitHub 新建一个仓库，名字必须是 `Xiaoqiu-dot.github.io`（用你的真实用户名替换 `Xiaoqiu-dot`），保持为空仓库（不勾选 README/.gitignore/license）。
2. 在本目录执行：
   ```bash
   git remote add origin https://github.com/Xiaoqiu-dot/Xiaoqiu-dot.github.io.git
   git push -u origin main
   ```
3. 进入仓库 Settings → Pages，Source 选 `main` 分支、根目录 `/`，保存。
4. 等 1–2 分钟，访问 https://Xiaoqiu-dot.github.io 即可看到。

## 修改内容

直接编辑 `index.html`，改完 `git add . && git commit -m "update" && git push` 即可自动更新网站。

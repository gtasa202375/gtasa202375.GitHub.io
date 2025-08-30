# 关于 AI 的博客与我的故事 这是一个个人博客项目，托管于 GitHub Pages，分享与 AI 相关的内容，以及我自己的学习与生活故事。 ## 站点预览 - 访问：https://blog.ieshacv.dpdns.org/ 这是我博客的主页，欢迎访问查看更多内容。 ## 项目概览 - **仓库名称**：gtasa202375.GitHub.io - **生成模板**：基于 `Meekdai/Gmeek-template` 生成。 - **主要内容**：包括 AI 技术文章、学习经验分享与个人故事。 - **目录结构示例**： - `.github/`：CI/CD 或工作流配置 - `docs/`：博客内容存放目录 - `CNAME`：绑定自定义域名（如有） - `README.md`：仓库说明（即本文件） - `blogBase.json`、`config.json`：站点配置文件 ## 功能特性 - **支持博客内容管理**：通过 `docs/` 目录维护博客文章内容。 - **页面生成模板**：使用 Gmeek 模板快速生成页面风格与结构。 - **配置灵活**：可根据 `config.json` 自定义主题、导航、SEO 等设置。 ## 启动指南（本地预览） 1. **克隆仓库** ```bash git clone https://github.com/gtasa202375/gtasa202375.GitHub.io.git cd gtasa202375.GitHub.io 
# 观音保佑


本指南记录了如何克隆本仓库、在本地运行，以及如何部署到常见的三大平台。

---

## 一、如何克隆仓库

1. 打开终端（或命令提示符）。  
2. 输入以下命令克隆仓库：  
   ```bash
   git clone https://github.com/gtasa202375/gtasa202375.GitHub.io.git
   cd gtasa202375.GitHub.io

3. 仓库即下载完成。




---

二、本地化部署

1. 安装依赖（如项目有构建工具）

npm install


2. 运行本地预览

npm run serve

或者

npm run dev


3. 打开浏览器，访问 http://localhost:xxxx 查看效果。



> 如果项目不需要构建工具，直接修改 docs/ 文件夹内容即可，推送后 GitHub Pages 会自动更新。




---

三、三大平台部署方法

1. GitHub Pages

进入 GitHub 仓库 Settings → Pages。

在 Source 选择 main 分支，根目录或 /docs 目录。

保存后，稍等片刻即可通过 https://username.github.io/ 访问。

如果需要自定义域名，将域名写入 CNAME 文件并在 DNS 配置里 CNAME 到 username.github.io。



---

2. Vercel 部署

1. 登录 Vercel 官网。


2. 点击 New Project，导入 GitHub 仓库。


3. 根据项目选择框架（如 Next.js / 静态导出）。


4. 部署完成后，系统会生成一个 *.vercel.app 域名。


5. 可在 Vercel 中绑定自定义域名。




---

3. Netlify 部署

1. 登录 Netlify 官网。


2. 点击 New Site from Git → 选择 GitHub → 导入仓库。


3. 设置构建命令（如 npm run build）和输出目录（如 dist/ 或 build/）。


4. 点击部署，完成后系统会生成一个 *.netlify.app 域名。


5. 也可以绑定自己的域名并配置 HTTPS。




---

四、总结

克隆仓库：git clone

本地化部署：安装依赖 → 运行本地服务

三大平台：

GitHub Pages：简单、免费

Vercel：适合动态/静态站点，自动构建

Netlify：静态站点友好，免费 HTTPS


🙏 南无观世音菩萨，愿一切顺利。  
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

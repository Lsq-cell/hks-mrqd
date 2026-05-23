<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# 小摩放松

这是一个基于 React + Vite + Express 的 AI Studio 应用。

View your app in AI Studio: https://ai.studio/apps/0ce4f3ba-8053-450d-9a0e-fe09ece9c408

## 本地启动

**环境要求：** Node.js

1. 安装依赖：

   ```bash
   npm install
   ```

2. 配置环境变量：

   复制 [.env.example](.env.example) 为 `.env.local`，并把其中的 `GEMINI_API_KEY` 改成你的 Gemini API Key。

3. 启动开发服务：

   ```bash
   npm run dev
   ```

4. 在浏览器打开：

   ```text
   http://localhost:3000
   ```

## 生产构建与启动

```bash
npm run build
npm start
```

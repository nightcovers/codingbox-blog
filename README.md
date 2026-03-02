# Boxin 的技术博客

基于 VitePress 构建的个人博客。

## 本地初始化

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run docs:dev
```

浏览器访问 http://localhost:5173 查看效果。

## 测试部署

```bash
# 构建静态文件
npm run docs:build

# 本地预览构建结果
npm run docs:preview
```

构建产物在 `.vitepress/dist` 目录，可部署至 GitHub Pages 等静态托管服务。

# Morimiue 的杂物堆

基于 [Astro](https://astro.build/) 与 [Tailwind CSS](https://tailwindcss.com/) 的个人博客，使用 [AstroPaper](https://github.com/satnaing/astro-paper) 主题二次开发。

## 本地开发

```bash
pnpm install      # 安装依赖
pnpm dev          # 启动开发服务器 localhost:4321
pnpm build        # 类型检查 + 构建 + Pagefind 索引
pnpm preview      # 本地预览构建产物
```

## 写作

博客文章存放在 `src/content/posts/`，可按子目录组织，子目录名会成为文章 URL 的一部分。页面（如关于页）存放在 `src/content/pages/`。

站点配置在 `astro-paper.config.ts`。

## 部署

部署到 Cloudflare Pages，构建命令 `pnpm build`，输出目录 `dist`。

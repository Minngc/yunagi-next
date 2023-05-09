# Yunagi

Yunagi (Evening Calm) is a blog system based on Next.js and Markdown.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Why Yunagi?

~~Yunagi is a Japanese word that means "evening calm". It is a beautiful word that describes the calmness of the evening. I hope that this blog system can bring you the same feeling.~~ The name yunagi is from [one of nine Kamikaze-class destroyers built for the Imperial Japanese Navy (IJN) during the 1920s](https://en.wikipedia.org/wiki/Japanese_destroyer_Y%C5%ABnagi_(1924)).

## Color

The color of the hyperlink is from PILOT iroshizuku kiri-same and [Semi Design](https://semi.design/zh-CN/basic/tokens). Other colors are only pure white and black with different alpha channel values.

## Code Block Theme

The theme is from [GitHub - PrismJS/prism-themes: A wider selection of Prism themes](https://github.com/PrismJS/prism-themes).

## Lazy Load

No lazy load is used in this blog system. The reason is that I believe in Cloudflare's CDN.

## TODO

- [x] 页面锚点滚动定位 & 导航栏
- [x] 返回页面顶部
- [x] 图片渲染
- [x] 图片放大显示（模态框或 :target）
- [x] 代码高亮
- [x] 代码块复制
- [x] 代码块行号
- [x] CI/CD
- [x] 字体渲染
- [x] 评论区
- [x] RSS 订阅支持
- [x] 修改 TOC 目录显示位置
- [x] markdown excel 样式修改
- [x] 在文章页面显示详细信息
- [x] 移动端适配
- [ ] Archive 功能模块
- [x] 文章目录显示不全（目录标题位置需固定而非上下滑动）
- [ ] 小屏下使用按钮展开目录（bookmark 图标）
- [ ] 文章显示宽度与关于页保持一致
- [ ] 移动端在点击链接后菜单自动回缩

## Issues

- [x] 复制按钮存在复制按钮随代码滚动的问题
- [x] 锚点需要给定偏移量

### Content Issues

- [x] 关于界面内容填充
- [ ] 文档内容空格缺失导致加粗无法正常显示
- [ ] 纯字符标题锚点无法正确工作
- [ ] 关于中注明夕凪名称、配色方案、博客设计风格借鉴、古诗应用出处等于“杂记”忝列于后

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

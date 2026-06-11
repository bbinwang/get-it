# 环境搭建记录

日期：2026-06-11

## 系统工具

| 工具 | 版本 | 安装方式 |
|------|------|----------|
| GitHub CLI (gh) | 2.94.0 | `brew install gh` |

## npm 依赖安装

项目根目录执行 `npm install`，以下为 package.json 中声明的依赖：

### 运行时依赖 (dependencies)

| 包名 | 版本 |
|------|------|
| @openai/codex-sdk | ^0.130.0 |
| @tailwindcss/typography | ^0.5.19 |
| clsx | ^2.1.1 |
| framer-motion | ^12.38.0 |
| katex | ^0.16.45 |
| lucide-react | ^1.14.0 |
| next | 16.2.6 |
| pdfjs-dist | ^5.7.284 |
| pdfkit | ^0.18.0 |
| react | 19.2.4 |
| react-dom | 19.2.4 |
| react-markdown | ^10.1.0 |
| rehype-katex | ^7.0.1 |
| remark-math | ^6.0.0 |
| three | ^0.184.0 |
| zod | ^4.4.3 |

### 开发依赖 (devDependencies)

| 包名 | 版本 |
|------|------|
| @tailwindcss/postcss | ^4 |
| @types/node | ^20 |
| @types/pdfkit | ^0.17.6 |
| @types/react | ^19 |
| @types/react-dom | ^19 |
| @types/three | ^0.184.1 |
| concurrently | ^9.1.2 |
| cross-env | ^7.0.3 |
| electron | ^33.2.1 |
| electron-builder | ^25.1.8 |
| eslint | ^9 |
| eslint-config-next | 16.2.6 |
| marked | ^14.1.4 |
| pdf-lib | ^1.17.1 |
| playwright | ^1.59.1 |
| tailwindcss | ^4 |
| tsx | ^4.21.0 |
| typescript | ^5 |
| wait-on | ^8.0.1 |

## 安装过程中的警告

npm 输出以下 allow-scripts 提示（未阻塞安装）：

- fsevents@2.3.2 — install 脚本
- sharp@0.34.5 — install 脚本
- unrs-resolver@1.11.1 — postinstall 脚本

可通过 `npm approve-scripts` 查看并批准。

## Python 包

本次未安装任何 Python 包。

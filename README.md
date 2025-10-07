# lyran

[![Built with Starlight](https://astro.badg.es/v2/built-with-starlight/tiny.svg)](https://starlight.astro.build)

```
pnpm create astro@latest -- --template starlight
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun! | 🧑‍🚀 **有经验的宇航员？** 删除此文件。祝你玩得开心！

## 🚀 Project Structure | 🚀 项目结构

Inside of your Astro + Starlight project, you'll see the following folders and files: | 在你的 Astro + Starlight 项目中，你会看到以下文件夹和文件：

```
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   └── docs/
│   └── content.config.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

Starlight looks for `.md` or `.mdx` files in the `src/content/docs/` directory. Each file is exposed as a route based on its file name. | Starlight 会在 `src/content/docs/` 目录中查找 `.md` 或 `.mdx` 文件。每个文件都会根据文件名作为路由暴露出来。

Images can be added to `src/assets/` and embedded in Markdown with a relative link. | 图片可以添加到 `src/assets/` 中，并通过相对链接嵌入到 Markdown 中。

Static assets, like favicons, can be placed in the `public/` directory. | 静态资源，如网站图标，可以放在 `public/` 目录中。

## 🧞 Commands | 🧞 命令

All commands are run from the root of the project, from a terminal: | 所有命令都从项目的根目录通过终端运行：

| Command | Action |
| :------------------------ | :----------------------------------------------- |
| `pnpm install` | Installs dependencies | 安装依赖 |
| `pnpm dev` | Starts local dev server at `localhost:4321` | 在 `localhost:4321` 启动本地开发服务器 |
| `pnpm build` | Build your production site to `./dist/` | 将生产站点构建到 `./dist/` |
| `pnpm preview` | Preview your build locally, before deploying | 在部署前本地预览构建 |
| `pnpm astro ...` | Run CLI commands like `astro add`, `astro check` | 运行 CLI 命令，如 `astro add`、`astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI | 获取 Astro CLI 的帮助信息 |

## 👀 Want to learn more? | 👀 想了解更多？

Check out [Starlight's docs](https://starlight.astro.build/), read [the Astro documentation](https://docs.astro.build), or jump into the [Astro Discord server](https://astro.build/chat). | 查看 [Starlight 文档](https://starlight.astro.build/)，阅读 [Astro 文档](https://docs.astro.build)，或加入 [Astro Discord 服务器](https://astro.build/chat)。
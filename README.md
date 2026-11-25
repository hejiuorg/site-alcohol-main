# site-alcohol-main

喝酒去主站仓，部署地址 `hejiu.org`。承载喝法、收藏、审核预览、全站聚合搜索与旧地址承接。

- 正文来源：`world-alcohol-encyclopedia/guide/`（208 页）
- 应用：`apps/main/`（Astro 静态生成，包名 `@hejiu/site-main`）
- 共享工程：`site-alcohol-core` 的 `packages/ui`、`packages/build-tools`、`packages/contracts`
- 旧地址：`legacy-routes.json`、`compat.js`、`review-registry.json` 随主站发布；`guide.hejiu.org` 与 `www` 由独立跳转仓兜底

## 命令

在 `implementation/` 工作区运行：

```text
npm run build:main
npm run build -w @hejiu/site-main
npm run serve:preview
```

主站首页是喝法叙事；酒类百科、文化与去处通过跨站链接进入。

# ORCA 网页模板

零依赖的响应式中文首页。直接打开 `index.html` 即可查看。

## GitHub → Vercel

1. 在 GitHub 新建仓库，例如 `orca-launch-demo`。
2. 将本目录中的 `index.html`、`vercel.json` 和 `README.md` 上传至仓库根目录。
3. 在 Vercel 选择 Add New → Project，导入该仓库。
4. Framework Preset 选择 Other；Root Directory 保持 `./`，无需安装或构建命令。
5. 点击 Deploy，完成后打开生成的 `.vercel.app` 地址。

如果直接导入包含本目录的完整仓库，将 Root Directory 设置为 `launch-demo`。

## 修改

文案和交互在 `index.html` 中；颜色在 CSS 开头的 `:root` 中。
提交到连接的 GitHub 分支后，Vercel 会自动重新部署。

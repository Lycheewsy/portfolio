# 部署说明

## 方法一：Netlify
1. 登录 Netlify。
2. 进入 Add new site / Deploy manually。
3. 将整个 `wang_shuyi_portfolio_publish` 文件夹拖入上传区域。
4. 部署完成后会获得一个 `.netlify.app` 固定网址。
5. 可在 Domain settings 中绑定自己的域名。

## 方法二：GitHub Pages
1. 在 GitHub 新建一个仓库，例如 `portfolio`。
2. 将本文件夹内的 `index.html`、`images/`、`README.txt` 上传到仓库根目录。
3. 打开仓库 `Settings → Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，Folder 选择 `/ (root)`。
6. 保存后即可获得 GitHub Pages 网址。

如果以后购买自定义域名，可在 GitHub Pages 或 Netlify 的域名设置中绑定。

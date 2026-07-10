# Travel Buddy｜马来西亚双城家庭之旅

## 发布文件

- `index.html`：完整交互页面，单文件、自包含。
- `.nojekyll`：关闭 Jekyll 处理。
- `.github/workflows/deploy-pages.yml`：GitHub Pages 自动部署工作流。

## 发布步骤

1. 在 GitHub 新建一个 **Public** 仓库，建议命名：`travel-buddy-malaysia`
2. 将本目录全部文件上传到仓库 `main` 分支根目录。
3. 打开仓库：`Settings → Pages`
4. 在 `Build and deployment → Source` 中选择 **GitHub Actions**
5. 等待 Actions 中 `Deploy GitHub Pages` 运行成功。

访问地址通常为：

`https://<GitHub用户名>.github.io/travel-buddy-malaysia/`

## 兼容性

页面已包含响应式 viewport 与多组桌面/手机断点；所有图片、CSS 和 JavaScript 均内嵌，无第三方脚本、字体或图片依赖。

## 说明

页面设置了 `noindex,nofollow`，降低搜索引擎收录概率，但 GitHub Pages 和 Public 仓库本身仍是公开内容。请勿放入身份证号、订单号、联系方式等敏感信息。

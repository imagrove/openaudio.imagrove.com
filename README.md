# openaudio.imagrove.com

Imagrove OpenAudio 官网门户（landing page）+ 文档入口。

- `index.html`：自包含静态落地页
- `vercel.json`：把 `/docs` 反代到文档站 `openaudio-docs.vercel.app`

## 部署

托管在 **Vercel**（团队 `imagroves-projects`），自定义域名 `openaudio.imagrove.com`。
因组织仓库在 Hobby 计划的 Git 集成限制，采用 `.github/workflows/deploy.yml` 的 **Vercel 隧道**方式部署（GitHub Actions 内用 CLI 上传，不依赖 Vercel↔Git 直连）。

## 内容

文案来源：项目工作区 `03-01_网站文案.md`。

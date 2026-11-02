# LATITUDE｜职业与财富实验室

个人培养计划网页：面向 2026 年 11 月—2027 年 10 月的技术能力、求职作品、用户访谈、金钱管理与每周复盘。

## 在线发布（GitHub Pages）

这个项目是零依赖静态站点。推荐使用公开仓库 `latitude-plan`：

1. 在 GitHub 登录后打开 https://github.com/new ，Repository name 填 `latitude-plan`，Visibility 选 **Public**，创建仓库。
2. 点击 **Add file → Upload files**，把本项目根目录里的 `index.html`、`README.md`、`.nojekyll` 上传到仓库根目录，点击 **Commit changes**。注意上传的是解压后的文件，**不是整个 zip**。
3. 打开仓库的 **Settings → Pages**，在 **Build and deployment** 选择 **Deploy from a branch**；Branch 选择 `main`，Folder 选择 `/(root)`，保存。
4. 站点地址：`https://docknek7.github.io/latitude-plan/`（以 GitHub Pages 页面显示的状态为准）。

`index.html` 即完整网页，未来修改后重新提交即可更新网站。

## 功能

- 四个季度培养计划与任务进度
- PaperTrail 科研阅读助手的开发与商业验证路线
- 用户访谈、岗位交流和外联记录
- 小额项目收支、净现金流与首笔100元实验
- 每周复盘及 JSON 导入/导出

## 隐私与技术边界

所有个人数据保存在浏览器的 `localStorage`，不会自动同步到 GitHub，**也不会跨设备同步**；清理浏览器数据可能导致信息丢失。请定期使用网页导出 JSON 并私下保存，勿将包含人名、联系方式、私人收支的备份文件提交到公开仓库。项目暂时没有真实的 AI 对话、支付或云端账号服务，PaperTrail 是后续作品开发路线。

## 未来迭代建议

1. 将职业计划任务、每周总结结构化以便编辑和迁移。
2. 用真实用户访谈验证 PaperTrail 的需求，而不是立即开发复杂的 RAG 后端。
3. 在具有稳定用户需求后再考虑 AI 服务端、鉴权、使用量和支付。

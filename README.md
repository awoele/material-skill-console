# 素材 Skill 工作台前端

这是素材 Skill 自动化工作台的公开静态前端，部署地址：

https://awoele.github.io/material-skill-console/

页面本身不保存素材、任务记录、令牌或本机路径。实际制作必须从本机的 `START-MATERIAL-SKILL-CONSOLE.cmd` 启动；启动器会运行只监听 `127.0.0.1:4317` 的控制器和 Worker，再用一次性临时凭证打开此页面。

仓库中的 `site/` 只包含经过构建的静态界面。服务端、Worker、运行数据和交付文件均不发布到 GitHub。

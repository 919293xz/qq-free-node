# qq-free-node — GitHub 免费算力节点

- 手动触发：`gh workflow run free-node.yml -R 919293xz/qq-free-node`
- 查看最近一次日志：`gh run view (gh run list -R 919293xz/qq-free-node -L1 --json databaseId -q '.[0].databaseId') -R 919293xz/qq-free-node --log`
- 免费额度：私有仓库 2000 分钟/月，单次 2 核 7GB Ubuntu
- 定时：每 30 分钟一次（可改 .github/workflows/free-node.yml 里的 cron，最短 5 分钟）
- 用途：定时任务、爬取、签到脚本、构建产物——任何无状态计算活

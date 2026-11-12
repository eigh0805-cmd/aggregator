# Aggregator 部署说明

- 每 6 小时由 GitHub Actions 运行 subscribe/collect.py 抓取公开免费节点，去重并检测可用性。
- 生成 data/clash.yaml、data/v2ray.txt、data/singbox.json 并回存本仓库。
- 订阅地址见仓库 data 目录对应文件的 Raw 链接。

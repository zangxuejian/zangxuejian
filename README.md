<div align="center">

# Zang Infra Notes

**Infrastructure / Cloud Native / Observability / AI Infra**

把工作中遇到的问题和业余做的小项目整理成技术记录。重点关注容器平台、基础设施运维、可观测性，以及 AI 工具如何融入日常工程。

[![Blog](https://img.shields.io/badge/BLOG-zangxuejian.com-050505?style=for-the-badge&logo=vercel&logoColor=white)](https://www.zangxuejian.com)
[![Projects](https://img.shields.io/badge/PROJECTS-工程作品集-FFFFFF?style=for-the-badge&logo=github&logoColor=050505)](https://www.zangxuejian.com/projects/)
[![RSS](https://img.shields.io/badge/RSS-订阅更新-050505?style=for-the-badge&logo=rss&logoColor=white)](https://www.zangxuejian.com/atom.xml)

</div>

```text
$ cat current-focus.txt
platform engineering / observability / AI infrastructure
```

## 关于我

从 Linux、网络和中间件运维起步，逐步转向 Kubernetes / OpenShift 容器平台和可观测性。目前一边做平台运维，一边尝试把遇到的问题做成可以运行、复用的小工具。

- **日常工作方向：** 基础设施、容器平台、中间件与系统稳定性
- **常用技术：** Linux、Nginx、Kubernetes、OpenShift、Prometheus、Grafana
- **正在探索：** 离线环境下的日志观测、Agent 工作流与 AI Infra
- **文章与经历：** [博客](https://www.zangxuejian.com) · [About](https://www.zangxuejian.com/about/)

## 工程项目

### [LogsView 2.0 · Nginx 日志观测工作台](https://www.zangxuejian.com/2026/07/09/nginx-log-dashboard/)

面向内网、DMZ 和离线环境的 Nginx 日志观测工具。节点 Agent 负责采集，服务端集中展示流量指标、采样请求明细和采集状态；支持请求检索、Request ID 关联，以及浅色工作台与深色大屏。全量指标聚合和明细采样分开处理，运行时不依赖互联网或 GPU。

`Nginx` `Python` `FastAPI` `SQLite` `Observability`

[阅读项目记录 →](https://www.zangxuejian.com/2026/07/09/nginx-log-dashboard/)

### [Codex Agent Delegator](https://github.com/zangxuejian/codex-agent-delegator)

连接 Codex 与本地 WorkBuddy MCP Server 的插件。把仓库扫描、资料提取和长上下文摘要等边界明确的辅助任务交给 WorkBuddy，最终判断、代码修改和评审仍由 Codex 负责。

`Codex` `MCP` `Python` `Agent Workflow`

[查看代码](https://github.com/zangxuejian/codex-agent-delegator) · [阅读设计与实践](https://www.zangxuejian.com/2026/07/05/codex-agent-delegator-thinking/)

### [DeepSeek 余额桌面小屏](https://github.com/zangxuejian/ESP)

用 ESP8266 和 1.44 英寸 TFT 屏显示 DeepSeek API 余额、账户状态与更新时间。云端 Node.js 服务获取余额并保管 API Key，设备通过 Wi-Fi 读取整理后的数据。

`ESP8266` `Node.js` `DeepSeek API` `Edge Display`

[查看代码](https://github.com/zangxuejian/ESP) · [阅读制作记录](https://www.zangxuejian.com/2026/06/22/personal-ai-observability-esp8266-deepseek-usage-dashboard/)

### [LifeWindows · 人生窗口期](https://github.com/zangxuejian/LifeWindows)

一个关于人生事件与时间感知的交互式网站。拖动年龄，观察事件卡片在「正盛 / 将谢 / 余温」之间变化；V3 还提供事件探索、详情和本地行动清单。事件年龄范围是内容组织模型，并非对个人机会的预测。

`React` `TypeScript` `Vite` `Interactive Web`

[查看代码](https://github.com/zangxuejian/LifeWindows) · [打开网站](https://lifewindows.vercel.app/)

## 技术方向

| 方向 | 关注内容 |
| --- | --- |
| 基础设施与中间件 | Linux · Networking · Nginx · DNS · TLS |
| 云原生与平台工程 | Kubernetes · OpenShift · 容器平台运维 · 自动化交付 |
| 可观测性 | Metrics · Logging · Alerting · Tracing |
| AI Infra 与工具 | API 用量监控 · Agent 工作流 · 受限环境中的轻量实践 |

## 认证

`RHCE` · `Red Hat OpenShift Administration` · `CKA` · `Prometheus Certified Associate (PCA)` · `CCNA` · `OceanBase OBCA`

更多经历和认证信息见[博客 About 页面](https://www.zangxuejian.com/about/)。

---

<div align="center">

[Blog](https://www.zangxuejian.com) · [Projects](https://www.zangxuejian.com/projects/) · [About](https://www.zangxuejian.com/about/)

</div>

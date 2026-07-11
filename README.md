<div align="center">

# Zang Infra Notes

**Infrastructure / Cloud Native / Observability / AI Infra**

这里放我的项目和技术记录。内容主要来自日常工作中碰到的问题，以及下班后做的一些小工具。

[![Blog](https://img.shields.io/badge/BLOG-zangxuejian.com-050505?style=for-the-badge&logo=vercel&logoColor=white)](https://www.zangxuejian.com)
[![Projects](https://img.shields.io/badge/PROJECTS-工程作品集-FFFFFF?style=for-the-badge&logo=github&logoColor=050505)](https://www.zangxuejian.com/projects/)
[![RSS](https://img.shields.io/badge/RSS-订阅更新-050505?style=for-the-badge&logo=rss&logoColor=white)](https://www.zangxuejian.com/atom.xml)

</div>

```text
$ cat current-focus.txt
observability / platform engineering / AI infrastructure
```

## 关于我

我的技术经历从Linux、网络和系统运维开始，后来逐步转向Kubernetes、OpenShift和可观测性。最近在折腾AI API用量监控、边缘小屏和Agent工具。

- 工作方向：基础设施、云原生平台、DevOps和可观测性
- 常用技术：Linux、Nginx、Kubernetes、OpenShift、Prometheus、Grafana
- 最近关注：AI Infra、Agent工作流和轻量边缘设备
- 博客：[Zang Infra Notes](https://www.zangxuejian.com)

## 当前方向

| 方向 | 正在关注 |
| --- | --- |
| **基础设施** | Linux · Networking · Nginx · DNS · TLS |
| **云原生平台** | Kubernetes · OpenShift · Helm · Platform Engineering |
| **可观测性** | Prometheus · Grafana · Logging · Alerting · Tracing |
| **最近在做** | AI API用量监控 · Edge Display · Codex · MCP |

## 工程作品

### Codex Agent Delegator

这是一个连接Codex和辅助Agent的本地工具。我用它处理日志压缩、目录扫描、候选查找这类边界明确但比较占上下文的任务，Codex继续负责技术判断和代码修改。

`Codex` `MCP` `Python` `Agent Workflow`

[阅读设计与实现 →](https://www.zangxuejian.com/2026/07/05/codex-agent-delegator-thinking/)

### Nginx Log Dashboard

一个轻量的Nginx日志仪表盘，主要面向内网、DMZ和离线环境。目标很直接：机器不能随便联网时，也能快速查看入口层性能、异常请求和节点状态。

`Nginx` `Python` `FastAPI` `Observability`

[查看项目复盘 →](https://www.zangxuejian.com/2026/07/09/nginx-log-dashboard/)

### DeepSeek AI Usage Dashboard

我不想每次都打开网页查看DeepSeek余额，于是用ESP8266做了一块桌面小屏。它会定时显示API余额、账户状态和更新时间。

`ESP8266` `Node.js` `DeepSeek API` `Edge Display`

[阅读实践记录 →](https://www.zangxuejian.com/2026/06/22/personal-ai-observability-esp8266-deepseek-usage-dashboard/)

## 能力与认证

`RHCE` · `Red Hat OpenShift Administration` · `CKA` · `Prometheus Certified Associate` · `CCNA Routing & Switching`

完整的证书和经历放在博客的[About页面](https://www.zangxuejian.com/about/)，这里不重复铺开。

---

<div align="center">

[Blog](https://www.zangxuejian.com) · [Projects](https://www.zangxuejian.com/projects/) · [About](https://www.zangxuejian.com/about/)

</div>

> 🌐 本文档由 [DigitalPlatDev/FreeDomain](https://github.com/DigitalPlatDev/FreeDomain) 翻译,英文原版见原项目。

# 从域名注册到网站上线的学习路线

本仓库包含一套成书规模的学习路径。产品操作说明与通用知识教程相互分离,以避免把 DigitalPlat 的能力与外部 DNS 或托管服务功能混为一谈。

## 类别 A:DigitalPlat FreeDomain

1. [关于 FreeDomain 项目](./documents/tutorial/platform/project-overview.md)
2. [控制面板导览](./documents/tutorial/platform/dashboard-tour.md)
3. [DigitalPlat 做什么](./documents/tutorial/platform/1.0-product-boundaries.md)
4. [创建 DigitalPlat 账户](./documents/tutorial/platform/1.1-account-registration.md)
5. [注册免费域名](./documents/tutorial/platform/1.2-domain-registration.md)
6. [接入外部域名服务器](./documents/tutorial/platform/1.3-connect-nameservers.md)
7. [查看状态与续期](./documents/tutorial/platform/1.4-status-and-renewal.md)
8. [管理账户数据与策略](./documents/tutorial/platform/1.5-account-and-policies.md)
9. [安全使用 API](./documents/tutorial/platform/1.6-api-overview.md)

DigitalPlat 负责注册域名并将其委派到外部权威域名服务器。常规 DNS 记录在 DigitalPlat 之外管理。

## 类别 B:通用教程

- [第 0 部分:新手基础](./documents/tutorial/foundations/index.md)
- [第 2 部分:外部 DNS](./documents/tutorial/dns/index.md)
- [第 3 部分:网站搭建与部署](./documents/tutorial/website/index.md)
- [第 4 部分:邮箱与服务记录](./documents/tutorial/email/index.md)
- [第 5 部分:运维与安全](./documents/tutorial/operations/index.md)
- [第 6 部分:高级架构与参考](./documents/tutorial/advanced/index.md)

<details>
<summary>展开通用教程全部章节</summary>

### 第 0 部分:新手基础

1. [如何使用本书](./documents/tutorial/foundations/0.1-how-to-use-this-book.md)
2. [互联网如何传输数据](./documents/tutorial/foundations/0.2-internet-foundations.md)
3. [终端与文件基础](./documents/tutorial/foundations/0.3-terminal-basics.md)
4. [搭建安全的练习环境](./documents/tutorial/foundations/0.4-practice-environment.md)
5. [规划你的第一个网站](./documents/tutorial/foundations/0.5-plan-your-site.md)
6. [域名与 DNS 基础](./documents/tutorial/foundations/0.6-domain-and-dns.md)

### 第 2 部分:外部 DNS

1. [委派与外部域名服务器](./documents/tutorial/dns/2.0-delegation.md)
2. [DNS 记录类型](./documents/tutorial/dns/2.1-record-types.md)
3. [主域名与子域名](./documents/tutorial/dns/2.2-subdomains.md)
4. [TTL、缓存与传播](./documents/tutorial/dns/2.3-ttl-and-propagation.md)
5. [DNS 故障排查](./documents/tutorial/dns/2.4-troubleshooting.md)

### 第 3 部分:网站搭建与部署

1. [HTML 与 CSS 基础](./documents/tutorial/website/3.0-html-css-foundations.md)
2. [网站请求的工作原理](./documents/tutorial/website/3.1-how-websites-work.md)
3. [搭建静态网站](./documents/tutorial/website/3.2-build-static-site.md)
4. [本地测试网站](./documents/tutorial/website/3.3-test-locally.md)
5. [准备 Linux Web 服务器](./documents/tutorial/website/3.4-prepare-server.md)
6. [部署并连接域名](./documents/tutorial/website/3.5-deploy-and-connect.md)
7. [启用并验证 HTTPS](./documents/tutorial/website/3.6-https.md)
8. [动态应用与反向代理](./documents/tutorial/website/3.7-dynamic-applications.md)
9. [无障碍访问与搜索基础](./documents/tutorial/website/3.8-accessibility-and-search.md)
10. [性能与缓存](./documents/tutorial/website/3.9-performance-and-caching.md)

### 第 4 部分:邮箱与服务记录

1. [邮箱 DNS:MX、SPF、DKIM 与 DMARC](./documents/tutorial/email/4.1-email-dns.md)
2. [验证与服务记录](./documents/tutorial/email/4.2-service-records.md)

### 第 5 部分:运维与安全

1. [基础设施清单与变更管理](./documents/tutorial/operations/5.1-domain-management.md)
2. [续期与过期](./documents/tutorial/operations/5.2-renewal-and-expiration.md)
3. [安全迁移域名服务器](./documents/tutorial/operations/5.3-migrate-nameservers.md)
4. [注册数据与隐私](./documents/tutorial/operations/5.4-registration-data.md)
5. [账户与 API 安全](./documents/tutorial/operations/5.5-security.md)
6. [可接受使用与滥用响应](./documents/tutorial/operations/5.6-acceptable-use.md)
7. [备份与恢复](./documents/tutorial/operations/5.7-backups-and-restoration.md)
8. [监控与事件响应](./documents/tutorial/operations/5.8-monitoring-and-incidents.md)
9. [服务器加固与维护](./documents/tutorial/operations/5.9-server-hardening.md)

### 第 6 部分:高级架构与参考

1. [API 自动化安全](./documents/tutorial/advanced/6.1-api-automation.md)
2. [自托管权威 DNS](./documents/tutorial/advanced/6.2-self-hosted-dns.md)
3. [命令参考](./documents/tutorial/advanced/6.3-command-reference.md)
4. [网站架构模式](./documents/tutorial/advanced/6.4-architecture-patterns.md)
5. [可靠性与容量规划](./documents/tutorial/advanced/6.5-reliability-and-capacity.md)
6. [术语表](./documents/tutorial/advanced/glossary.md)
7. [标准与延伸阅读](./documents/tutorial/advanced/references.md)

</details>

## 实践与测评

- [综合毕业项目](./documents/tutorial/capstone/index.md)
  1. [项目简报与架构](./documents/tutorial/capstone/7.1-project-brief.md)
  2. [搭建并测试网站](./documents/tutorial/capstone/7.2-build-and-test.md)
  3. [注册、部署与连接](./documents/tutorial/capstone/7.3-register-and-deploy.md)
  4. [加固、监控与备份](./documents/tutorial/capstone/7.4-secure-and-operate.md)
  5. [最终验收与交付](./documents/tutorial/capstone/7.5-final-acceptance.md)
- [练习册与练习题](./documents/tutorial/appendices/workbook.md)
- [参考答案](./documents/tutorial/appendices/answers.md)
- [故障排查决策树](./documents/tutorial/appendices/troubleshooting-trees.md)
- [检查清单与模板](./documents/tutorial/appendices/checklists-and-templates.md)

继续阅读[完整学习指南](./documents/tutorial/index.md)。

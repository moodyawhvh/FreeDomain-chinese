> 🌐 本文档由 [DigitalPlatDev/FreeDomain](https://github.com/DigitalPlatDev/FreeDomain) 翻译,英文原版见原项目。

# FreeDomain 学习指南

本书分为界限清晰的两大类别:

1. **DigitalPlat FreeDomain 指南** —— 产品专属的账户、注册、外部域名服务器委派、状态、续期和策略说明。
2. **通用域名与网站教程** —— 互联网基础、外部 DNS 记录、Web 开发、部署、HTTPS、邮箱、运维和高级工程。

DigitalPlat 将注册的域名委派到外部权威域名服务器,本身不提供常规 DNS 记录编辑器。所有 `A`、`AAAA`、`CNAME`、`MX`、`TXT` 等区域记录教程都归入外部 DNS 类别。

阅读[本书规划](./BOOK_PLAN.md)可了解范围与编写规则。

## 类别 A:DigitalPlat FreeDomain 指南

1. [关于 FreeDomain 项目](./platform/project-overview.md)
2. [控制面板导览](./platform/dashboard-tour.md)
3. [DigitalPlat 做什么](./platform/1.0-product-boundaries.md)
4. [创建 DigitalPlat 账户](./platform/1.1-account-registration.md)
5. [注册免费域名](./platform/1.2-domain-registration.md)
6. [接入外部域名服务器](./platform/1.3-connect-nameservers.md)
7. [查看状态与续期](./platform/1.4-status-and-renewal.md)
8. [管理账户数据与策略](./platform/1.5-account-and-policies.md)
9. [安全使用 API](./platform/1.6-api-overview.md)

[类别 A 总览](./platform/index.md)

## 类别 B:通用域名与网站教程

### 第 0 部分:学习准备

1. [如何使用本书](./foundations/0.1-how-to-use-this-book.md)
2. [互联网如何传输数据](./foundations/0.2-internet-foundations.md)
3. [终端与文件基础](./foundations/0.3-terminal-basics.md)
4. [搭建安全的练习环境](./foundations/0.4-practice-environment.md)
5. [规划你的第一个网站](./foundations/0.5-plan-your-site.md)
6. [域名与 DNS 基础](./foundations/0.6-domain-and-dns.md)

[第 0 部分总览](./foundations/index.md)

### 第 2 部分:学习外部 DNS

1. [委派与外部域名服务器](./dns/2.0-delegation.md)
2. [DNS 记录类型](./dns/2.1-record-types.md)
3. [主域名与子域名](./dns/2.2-subdomains.md)
4. [TTL、缓存与传播](./dns/2.3-ttl-and-propagation.md)
5. [DNS 故障排查](./dns/2.4-troubleshooting.md)

[第 2 部分总览](./dns/index.md)

### 第 3 部分:搭建并发布网站

1. [HTML 与 CSS 基础](./website/3.0-html-css-foundations.md)
2. [网站请求的工作原理](./website/3.1-how-websites-work.md)
3. [搭建静态网站](./website/3.2-build-static-site.md)
4. [本地测试网站](./website/3.3-test-locally.md)
5. [准备 Linux Web 服务器](./website/3.4-prepare-server.md)
6. [部署并连接域名](./website/3.5-deploy-and-connect.md)
7. [启用并验证 HTTPS](./website/3.6-https.md)
8. [动态应用与反向代理](./website/3.7-dynamic-applications.md)
9. [无障碍访问与搜索基础](./website/3.8-accessibility-and-search.md)
10. [性能与缓存](./website/3.9-performance-and-caching.md)

[第 3 部分总览](./website/index.md)

### 第 4 部分:邮箱与服务记录

1. [邮箱 DNS:MX、SPF、DKIM 与 DMARC](./email/4.1-email-dns.md)
2. [验证与服务记录](./email/4.2-service-records.md)

[第 4 部分总览](./email/index.md)

### 第 5 部分:运营与保护域名

1. [基础设施清单与变更管理](./operations/5.1-domain-management.md)
2. [续期与过期](./operations/5.2-renewal-and-expiration.md)
3. [安全迁移域名服务器](./operations/5.3-migrate-nameservers.md)
4. [注册数据与隐私](./operations/5.4-registration-data.md)
5. [账户与 API 安全](./operations/5.5-security.md)
6. [可接受使用与滥用响应](./operations/5.6-acceptable-use.md)
7. [备份与恢复](./operations/5.7-backups-and-restoration.md)
8. [监控与事件响应](./operations/5.8-monitoring-and-incidents.md)
9. [服务器加固与维护](./operations/5.9-server-hardening.md)

[第 5 部分总览](./operations/index.md)

### 第 6 部分:高级架构与参考

1. [API 自动化安全](./advanced/6.1-api-automation.md)
2. [自托管权威 DNS](./advanced/6.2-self-hosted-dns.md)
3. [命令参考](./advanced/6.3-command-reference.md)
4. [网站架构模式](./advanced/6.4-architecture-patterns.md)
5. [可靠性与容量规划](./advanced/6.5-reliability-and-capacity.md)
6. [术语表](./advanced/glossary.md)
7. [标准与延伸阅读](./advanced/references.md)

[第 6 部分总览](./advanced/index.md)

## 第 7 部分:综合毕业项目

1. [项目简报与架构](./capstone/7.1-project-brief.md)
2. [搭建并测试网站](./capstone/7.2-build-and-test.md)
3. [注册、部署与连接](./capstone/7.3-register-and-deploy.md)
4. [加固、监控与备份](./capstone/7.4-secure-and-operate.md)
5. [最终验收与交付](./capstone/7.5-final-acceptance.md)

[第 7 部分总览](./capstone/index.md)

毕业项目是唯一的综合章节:DigitalPlat 负责注册与外部 NS 委派,外部 DNS 服务负责区域记录,Web 服务器负责 HTTP 与 HTTPS。

## 附录与练习册

1. [练习册与练习题](./appendices/workbook.md)
2. [参考答案](./appendices/answers.md)
3. [故障排查决策树](./appendices/troubleshooting-trees.md)
4. [检查清单与模板](./appendices/checklists-and-templates.md)

[附录总览](./appendices/index.md)

## 快速路径

### 我只需要把 DigitalPlat 域名接入外部 DNS

1. [DigitalPlat 做什么](./platform/1.0-product-boundaries.md)
2. [接入外部域名服务器](./platform/1.3-connect-nameservers.md)
3. [委派与外部域名服务器](./dns/2.0-delegation.md)

### 我的委派域名没有网站记录

1. [DNS 记录类型](./dns/2.1-record-types.md)
2. [DNS 故障排查](./dns/2.4-troubleshooting.md)
3. [故障排查决策树](./appendices/troubleshooting-trees.md)

### 我想发布第一个网站

1. [规划你的第一个网站](./foundations/0.5-plan-your-site.md)
2. [搭建静态网站](./website/3.2-build-static-site.md)
3. [部署并连接域名](./website/3.5-deploy-and-connect.md)
4. [启用并验证 HTTPS](./website/3.6-https.md)

### 我想学完整课程

从[类别 A](./platform/index.md)开始,依次学完[第 0 部分](./foundations/index.md),最后完成[毕业项目](./capstone/index.md)和[练习册](./appendices/workbook.md)。

## 安全守则

- 真实部署前,替换文档中的虚构域名和示例 IP 地址。
- 绝不发布密码、令牌、私钥、Cookie、恢复代码或个人注册数据。
- 注册、续期、付款或账户变更前,先阅读最新的产品通知与政策。
- 常规 DNS 记录只在外部权威 DNS 服务中管理。
- 任何 DNS、服务器或域名服务器变更前,先备份当前值并定义回滚方案。
- 独立评估第三方 DNS、托管、邮箱和证书服务。

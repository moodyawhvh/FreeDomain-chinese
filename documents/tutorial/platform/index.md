> 🌐 本文档由 [DigitalPlatDev/FreeDomain](https://github.com/DigitalPlatDev/FreeDomain) 翻译,英文原版见原项目。

# 类别 A:DigitalPlat FreeDomain 指南

本类别记录 DigitalPlat FreeDomain 产品本身的内容,刻意与通用 DNS 及网站教程分开。

## 当前产品边界

DigitalPlat 注册符合条件的域名,并将其委派到用户提供的外部权威域名服务器。

DigitalPlat 不提供 DNS 记录编辑器。`A`、`AAAA`、`CNAME`、`MX`、`TXT` 等记录应在外部权威 DNS 服务中创建和管理,而不是在 DigitalPlat 控制面板中。

控制面板用于账户、注册、域名服务器委派、域名状态、续期、注册数据以及产品当前展示的其他功能。

## 章节

1. [关于 FreeDomain 项目](./project-overview.md)
2. [控制面板导览](./dashboard-tour.md)
3. [DigitalPlat 做什么](./1.0-product-boundaries.md)
4. [创建 DigitalPlat 账户](./1.1-account-registration.md)
5. [注册免费域名](./1.2-domain-registration.md)
6. [接入外部域名服务器](./1.3-connect-nameservers.md)
7. [查看状态与续期](./1.4-status-and-renewal.md)
8. [管理账户数据与策略](./1.5-account-and-policies.md)
9. [安全使用 API](./1.6-api-overview.md)

## 产品环节完成检查

进入通用教程之前,确认:

- 账户可以登录。
- 域名出现在 Domain List 中。
- 外部 DNS 区域已创建。
- DigitalPlat 已把域名委派到指定的外部域名服务器。
- `dig NS` 返回预期的域名服务器。
- 你已理解:所有常规 DNS 记录都在 DigitalPlat 之外管理。

继续阅读[关于 FreeDomain 项目](./project-overview.md)。

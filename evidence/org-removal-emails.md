# 证据：GitHub 组织移除通知（两封）

本目录保存了作者于 **2026-11-16** 收到的两封 GitHub 通知邮件，用于支撑正文第 8 节关于"被移出组织"的陈述。

## 元数据

| 字段 | 邮件一 | 邮件二 |
|---|---|---|
| 原始文件名 | `[GitHub] You've been removed from the _Casdoor_ organization.eml` | `[GitHub] You've been removed from the _Apache Casbin (Incubating)_ organization.eml` |
| 归档文件名 | `2026-11-16-github-removed-from-casdoor-org.eml` | `2026-11-16-github-removed-from-casbin-org.eml` |
| 发件人 | `GitHub <noreply@github.com>` | 同左 |
| 收件人 | `WindSpiritSR <simon343riley@gmail.com>` | 同左 |
| 时间 | `Mon, 16 Nov 2026 03:08:39 -0800`（北京时间 2026-11-16 19:08:39） | `Mon, 16 Nov 2026 03:08:38 -0800`（北京时间 2026-11-16 19:08:38） |
| 主题 | `[GitHub] You've been removed from the "Casdoor" organization` | `[GitHub] You've been removed from the "Apache Casbin (Incubating)" organization` |
| Message-ID | `<6afae437de240_ec12104576cc@sharedworker-78974977d7-7l9wd.mail>` | `<6afae4361ceaf_11d1210356942@sharedworker-78974977d7-qmqzj.mail>` |
| 分类头 | `categories: org,org-remove-member` | 同左 |

## 正文（quoted-printable 解码后逐字）

邮件一：

> Hi @WindSpiritSR,
>
> You've been removed from the "Casdoor" organization.
>
> Cheers & Octocats,
> GitHub Support

邮件二除组织名外与邮件一完全相同：

> Hi @WindSpiritSR,
>
> You've been removed from the "Apache Casbin (Incubating)" organization.
>
> Cheers & Octocats,
> GitHub Support

## 需要说明的几点

1. **两封邮件相差 1 秒**（19:08:38 / 19:08:39），且 `categories` 头都是 `org,org-remove-member`——这是 GitHub 的"组织成员被移除"通知类型，不是仓库权限变更、不是 issue 关闭。
2. **真实性**：两封邮件的 SMTP 链路显示 `dkim=pass`、`spf=pass`、`dmarc=pass`（发信域 `github.com`，DKIM selector `pf2026`），原始 MIME 与签名头完整保存在同目录的 `.eml` 文件中，可用任意邮件客户端打开核验。
3. **收件地址**：`simon343riley@gmail.com` 同时也是作者在 Casdoor 仓库中 commit 签名的邮箱（`git log --author=WindSpiritSR` 可查），不属于新增的隐私暴露。
4. **隐私范围**：原始邮件包含 Google 的 `Received`/`ARC` 头（其中含收件地址、Gmail 内部 SMTP id）。若你不想公开这些内容，可只发布本文件的正文部分，删除同目录 `.eml`。

## 引用方式

正文第 8 节引用为"图 5 / 证据 26"，链接指向同目录的 `.eml` 文件；如需在网页上直接阅读，用本文件即可。

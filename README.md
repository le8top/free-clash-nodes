# 极光节点站 · 每日实测的免费 Clash 节点订阅

![更新频率](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0-%E6%AF%8F%E6%97%A5%E8%87%AA%E5%8A%A8-blue)
![界面语言](https://img.shields.io/badge/%E8%AF%AD%E8%A8%80-%E4%B8%AD%2F%E8%8B%B1%2F%E4%BF%84%2F%E6%B3%A2-green)

> 免费 Clash 节点订阅：每天自动实测一遍连通性，只把真正能连上的节点发布出来。
>
> **站点入口：<https://clash.le8.top>**

---

## 中文

### 这是什么

一个每天自动更新的**免费节点订阅**，输出标准 Clash 配置格式（`clash.yaml`），
可直接导入 Clash / Clash Verge / Mihomo 等支持订阅链接的客户端。

和常见的「节点列表分享」不同，这里的每一条节点在发布前都跑过一次真实连接测试：
连不上的直接丢掉，延迟过高的排后面。**页面上显示的数量、通过率、延迟中位数，
都是当日实测出来的实际值，不是估计值，也不是固定写死的数字。**

### 主要特点

| | |
|---|---|
| **每日实测** | 每天自动对所有候选节点做一次连通性实测，只发布通过测试的节点 |
| **数据公开** | 实测数量、通过率、延迟中位数、验证状态都显示在页面上，可自行核对 |
| **不凑数** | 当天通过多少就发多少，不为了达到某个数字而塞入不可用节点 |
| **免费、无账号** | 不需要注册，不要求登录，页面不埋统计脚本 |
| **四语界面** | 简体中文 / English / Русский / فارسی |
| **纯静态站点** | 无后端、无数据库，页面秒开，不记录访客信息 |

### 怎么用

1. 打开 <https://clash.le8.top>
2. 点击「获取订阅链接」，页面会生成当日订阅地址
3. 复制地址，粘贴到客户端的「订阅」或「配置」里导入

也可以直接用客户端的「从 URL 导入」功能填入地址。

> **关于链接有效期**：订阅地址每天更换，单条链接有效期为 3 天。
> 客户端的「更新订阅」是用已保存的地址重新拉取，**不会拿到新地址**，
> 所以链接最长 3 天后需要回站点重新获取一次。这一点我们如实说明，
> 不做「开启自动更新就能一直用」的承诺。

### 数据从哪来

每天自动聚合公开的节点来源，逐条实测后发布。**上游来源清单不在页面上展示**，
页面只呈现实测结果与聚合后的自有订阅。

当某一天的实测未能完成时，页面会诚实地显示「未验证」而不是假装已经验证过——
宁可少显示，也不显示没有依据的数字。

### 支持的语言

| 语言 | 入口 |
|---|---|
| 简体中文 | <https://clash.le8.top/> |
| English | <https://clash.le8.top/en/> |
| Русский | <https://clash.le8.top/ru/> |
| فارسی | <https://clash.le8.top/fa/> |

### 常见问题

<details>
<summary>导入客户端后看不到节点怎么办？</summary>

先确认客户端支持 Clash 订阅格式（`clash.yaml`）。若订阅能下载但节点列表为空，
通常是客户端配置未被完整识别——重新导入一次，或在客户端里手动执行一次「更新订阅」。
</details>

<details>
<summary>链接失效了怎么办？</summary>

订阅地址每 3 天轮换一次。回站点重新获取即可，不需要重新配置客户端里的其他选项。
</details>

<details>
<summary>为什么有时显示「未验证」？</summary>

说明当日的自动化实测没有跑完，此时页面不会显示通过率等数字。
这是刻意设计的：没有实测依据的数据宁可不显示。通常次日会自动恢复。
</details>

<details>
<summary>需要付费或注册吗？</summary>

都不需要。站点免费使用，没有账号体系，也不收集访客信息。
</details>

<details>
<summary>节点数量是多少？</summary>

每天不同。实测通过多少就发布多少，因此数量会随当日网络状况波动。
当日实际数量显示在站点页面上。
</details>

### 相关链接

- 站点：<https://clash.le8.top>
- 商务合作：站点页脚「商务合作」区块内提供邮箱

### 免责声明

本项目仅做公开节点信息的聚合与可用性实测，**不提供、不售卖任何付费代理服务**，
不收集或存储访客的任何个人信息。

使用代理工具可能受到你所在国家或地区法律的约束。
请在遵守当地法律法规的前提下使用，因使用本项目内容产生的任何后果由使用者自行承担。

---

## English — Free Daily-Tested Clash Node Subscription

> A free Clash node subscription that re-tests every node daily and publishes
> only the ones that actually connect.
>
> **Site: <https://clash.le8.top>**

### What it is

A **free proxy node subscription** that updates automatically every day and
serves a standard Clash configuration file (`clash.yaml`), ready to import into
Clash, Clash Verge, Mihomo, or any client that supports subscription URLs.

Unlike most shared node lists, every node here goes through a real connection
test before it is published: unreachable ones are dropped, slower ones are
ranked lower. **The node count, pass rate, and median latency shown on the site
are measured values from that day's test run — not estimates, not hardcoded numbers.**

### Highlights

| | |
|---|---|
| **Tested daily** | Every candidate node is connectivity-tested once per day; only nodes that pass are published |
| **Numbers you can check** | Test size, pass rate, median latency, and verification status are all shown on the site |
| **No padding** | Whatever passes that day gets published — no filling the list with dead nodes to hit a quota |
| **Free, no account** | No sign-up, no login, no analytics scripts on the pages |
| **Four languages** | 简体中文 / English / Русский / فارسی |
| **Fully static** | No backend, no database, instant page loads, no visitor tracking |

### How to use

1. Open <https://clash.le8.top>
2. Click "Get subscription link" — the page generates today's subscription URL
3. Copy the URL and import it into your client's subscription / profile section

Most clients also support importing directly from a URL.

> **About link validity:** the subscription URL rotates daily and each link stays
> valid for 3 days. A client's "update subscription" action re-fetches the URL it
> already stored — it does **not** obtain a new one — so you will need to grab a
> fresh link from the site at least every 3 days. We state this plainly rather
> than claiming that auto-update will keep working indefinitely.

### Where the data comes from

Public node sources are aggregated automatically each day, then tested one by one
before publishing. **The upstream source list is not displayed on the site** —
only the test results and the aggregated subscription are.

If a day's test run does not complete, the site honestly shows "unverified"
instead of pretending the data was verified. Showing fewer numbers beats showing
numbers with nothing behind them.

### Languages

| Language | URL |
|---|---|
| 简体中文 (Chinese) | <https://clash.le8.top/> |
| English | <https://clash.le8.top/en/> |
| Русский (Russian) | <https://clash.le8.top/ru/> |
| فارسی (Persian) | <https://clash.le8.top/fa/> |

### FAQ

<details>
<summary>No nodes appear after importing</summary>

Confirm your client supports the Clash subscription format (`clash.yaml`).
If the subscription downloads but the node list is empty, re-import it or trigger
"update subscription" manually once.
</details>

<details>
<summary>My link stopped working</summary>

Subscription URLs rotate every 3 days. Get a fresh one from the site — no need to
change any other client settings.
</details>

<details>
<summary>Why does it sometimes say "unverified"?</summary>

It means that day's automated test run did not finish, so pass rate and similar
figures are not shown. This is deliberate: no numbers without a test behind them.
It usually recovers on the next day's run.
</details>

<details>
<summary>Is it free? Do I need to register?</summary>

Neither. The site is free to use, has no account system, and collects no visitor
information.
</details>

<details>
<summary>How many nodes are there?</summary>

It varies daily — whatever passes the test gets published, so the count fluctuates
with network conditions. The current number is shown on the site.
</details>

### Links

- Site: <https://clash.le8.top>
- Business contact: email provided in the site footer

### Disclaimer

This project only aggregates publicly available node information and tests its
availability. It **does not provide or sell any paid proxy service** and does not
collect or store any personal information from visitors.

The use of proxy tools may be subject to the laws of your country or region.
Please use it in compliance with applicable local laws and regulations;
all consequences arising from the use of this project are borne by the user.

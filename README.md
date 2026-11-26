<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.png" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.png" />
    <img alt="MRXOAD — Open Source & Original Projects" src="./assets/banner-dark.png" width="100%" />
  </picture>
</p>

<p align="center">
  <a href="#original-projects"><img src="https://img.shields.io/badge/Original_Repos-3-10B981?style=flat-square" alt="Original Repos" /></a>
  <a href="https://mrxoad.github.io/china-calendar-curated/all.ics"><img src="https://img.shields.io/badge/Live_Feed-China_Calendar-F59E0B?style=flat-square" alt="China Calendar Live Feed" /></a>
  <a href="#upstream-forks"><img src="https://img.shields.io/badge/Upstream_Forks-Separated-64748B?style=flat-square" alt="Upstream Forks Separated" /></a>
</p>

<br />

专注做**解决真实痛点、可长期维护**的轻量工程工具——覆盖长文本 LLM 工作流、网络分流规则体系以及自动化日历/数据订阅源。

> **仓库边界说明**：公开主页仅呈现独立维护的开源项目；私有工程与日常实验环境保持独立隔离，上游 Fork 单独归类，不与原创项目混排。

---

<a id="original-projects"></a>

## ❖ 原创公开项目 · Original Projects

<table>
  <thead>
    <tr>
      <th align="left" width="24%">项目</th>
      <th align="left" width="46%">定位与核心能力</th>
      <th align="left" width="16%">技术栈</th>
      <th align="left" width="14%">状态 / 入口</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/MRXOAD/xuanji-write"><strong>xuanji-write</strong></a><br />
        <sub>长篇网文 LLM 续写框架</sub>
      </td>
      <td>
        面向百章以上中文长篇写作的 LLM 续写与质控框架：内置 <strong>11 层一致性堵漏</strong>（故事合约、角色锚点、伏笔追踪、RAG 反向防复读、章末审查重试）、写作/监控双模型分流，以及 Streamlit + React 实时看板。
      </td>
      <td>
        <code>Python</code><br />
        <code>FastAPI</code> <code>React</code><br />
        <code>Docker</code>
      </td>
      <td>
        <a href="https://github.com/MRXOAD/xuanji-write/actions/workflows/ci.yml"><img src="https://github.com/MRXOAD/xuanji-write/actions/workflows/ci.yml/badge.svg" alt="CI" /></a><br />
        <img src="https://img.shields.io/github/stars/MRXOAD/xuanji-write?style=flat-square&color=38BDF8" alt="Stars" />
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/MRXOAD/proxy-rules"><strong>proxy-rules</strong></a><br />
        <sub>网络分流与去广告规则库</sub>
      </td>
      <td>
        持续维护的 <strong>Loon</strong> 与 <strong>Mihomo (Clash Meta)</strong> 分流规则集及去广告插件仓库：含 54 份 Loon 规则、58 个去广告/增强插件与 79 份 Mihomo 规则（支持 <code>.mrs</code> / <code>.yaml</code> / <code>.list</code> 直连引入）。
      </td>
      <td>
        <code>JavaScript</code><br />
        <code>Loon</code> <code>Mihomo</code>
      </td>
      <td>
        <img src="https://img.shields.io/github/last-commit/MRXOAD/proxy-rules?style=flat-square&label=Updated&color=10B981" alt="Updated" /><br />
        <img src="https://img.shields.io/github/forks/MRXOAD/proxy-rules?style=flat-square&color=10B981" alt="Forks" />
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/MRXOAD/china-calendar-curated"><strong>china-calendar-curated</strong></a><br />
        <sub>精选中国节日日历订阅源</sub>
      </td>
      <td>
        面向 Apple Calendar（iPhone / iPad / Mac）的 2000–2100 年中国节日、农历与二十四节气订阅源：发布前自动比对 Apple 官方节假日源去重，GitHub Actions 每月自动构建并发布至 GitHub Pages。
      </td>
      <td>
        <code>Python</code><br />
        <code>ICS</code> <code>Actions</code><br />
        <code>GitHub Pages</code>
      </td>
      <td>
        <a href="https://github.com/MRXOAD/china-calendar-curated/actions/workflows/build.yml"><img src="https://github.com/MRXOAD/china-calendar-curated/actions/workflows/build.yml/badge.svg" alt="Build" /></a><br />
        <a href="https://mrxoad.github.io/china-calendar-curated/all.ics"><img src="https://img.shields.io/badge/Subscribe-all.ics-F59E0B?style=flat-square" alt="Subscribe" /></a>
      </td>
    </tr>
  </tbody>
</table>

---

## ❖ 关注方向与常用栈 · Focus & Stack

| 方向 | 实践内容 |
| --- | --- |
| **LLM & Agent 工作流** | 长程上下文控制、结构化审查管线、多模型成本分流与自动化评测 |
| **网络规则与代理工程** | Loon / Mihomo 规则去重编译、去广告重写脚本与跨端同步 |
| **实用自动化工具** | 零运维 GitHub Actions 定时生成、静态订阅源发布与回归测试 |

<p>
  <img src="https://img.shields.io/badge/Python-1E293B?style=flat-square&logo=python&logoColor=38BDF8" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-1E293B?style=flat-square&logo=typescript&logoColor=38BDF8" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-1E293B?style=flat-square&logo=javascript&logoColor=F59E0B" alt="JavaScript" />
  <img src="https://img.shields.io/badge/FastAPI-1E293B?style=flat-square&logo=fastapi&logoColor=34D399" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-1E293B?style=flat-square&logo=react&logoColor=38BDF8" alt="React" />
  <img src="https://img.shields.io/badge/Docker-1E293B?style=flat-square&logo=docker&logoColor=38BDF8" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-1E293B?style=flat-square&logo=githubactions&logoColor=E2E8F0" alt="GitHub Actions" />
</p>

---

<a id="upstream-forks"></a>

## ❖ 上游跟踪 · Upstream Forks

<details>
<summary>展开查看独立归类的公开 Fork（用于上游追踪与学习，非原创项目）</summary>

<br />

| Fork 仓库 | 上游来源 | 方向 |
| --- | --- | --- |
| [`MRXOAD/rea`](https://github.com/MRXOAD/rea) | [`morluto/rea`](https://github.com/morluto/rea) | Agent 驱动的逆向工程工具链 |
| [`MRXOAD/CyberStrikeAI`](https://github.com/MRXOAD/CyberStrikeAI) | [`chigejuzi520/CyberStrikeAI`](https://github.com/chigejuzi520/CyberStrikeAI) | AI 原生安全自动化执行系统 |
| [`MRXOAD/codex-with-chatgpt`](https://github.com/MRXOAD/codex-with-chatgpt) | [`XiaoDuoYa/codex-with-chatgpt`](https://github.com/XiaoDuoYa/codex-with-chatgpt) | ChatGPT 规划 + Codex 执行协作 |

</details>

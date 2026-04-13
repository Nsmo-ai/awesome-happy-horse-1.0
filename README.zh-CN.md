# Awesome Happy Horse

[English](README.md) | 简体中文 | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [Русский](README.ru.md)

[Happy Horse AI](https://tryhappyhorse.com/) 的公开资料、公开信号和可复用资源整理仓库。它的目标不是简单汇总内容，而是帮助你区分：

- 哪些是已经能确认的公开事实
- 哪些只是高概率说法
- 哪些还是 rumor
- 哪些内容虽然热，但并不适合直接当作结论传播

## 这个仓库为什么值得看

[Happy Horse 1.0](https://tryhappyhorse.com/) 的特殊之处在于：产品叙事和 benchmark 叙事几乎同时爆发。

- 一边是公开产品定位：电影感视频生成、面向创作者和 SaaS 场景
- 一边是公开榜单表现：在多个视频榜单类别中非常靠前

这会导致一个常见问题：讨论热度远远大于公开发布完整度。于是用户会不断发问：

- Happy Horse 到底是什么？
- Happy Horse 开源了吗？
- 能本地运行吗？
- 有没有 API？
- 它到底是不是比 Seedance 更强？
- 哪个网站才是应该点进去的？

这个仓库就是为这些问题准备的。

## 事情是怎么发生的

目前公开时间线虽然不长，但已经足够说明问题：

1. `2026-04-08`
   - 公开仓库 [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) 出现在 GitHub。
   - 公开 README 更像产品营销页，不像代码或模型发布页。

2. `2026-04-08` 到 `2026-04-09`
   - 社区仓库开始快速扩展话题，形成 prompt、benchmark、rumor、source tracking 等多个内容层。

3. `2026-04-13`
   - 公开 benchmark 页面显示 [Happy Horse 1.0](https://tryhappyhorse.com/) 在多个类别中处于非常强的位置。
   - 但官方公开 GitHub 仓库仍然没有提供权重或推理代码。

## 当前关键状态

- **[Verified]** 公开仓库 [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) 已存在。
- **[Verified]** 官方公开描述把 Happy Horse AI 呈现为一个强调 `1080p cinematic video` 和 `advanced motion synthesis` 的产品。
- **[Verified]** 当前公开 README 更偏营销，而不是技术发布。
- **[Verified]** 截至 `2026-04-13`，Artificial Analysis 公共页面显示 HappyHorse-1.0 在 `Text to Video (No Audio)` 与 `Image to Video (No Audio)` 都是领先位置。
- **[Verified]** 截至 `2026-04-13`，HappyHorse-1.0 在 `Text to Video (With Audio)` 也处于领先位置。
- **[Verified]** 截至 `2026-04-13`，`Dreamina Seedance 2.0 720p` 在 `Image to Video (With Audio)` 领先，而 HappyHorse-1.0 排第二。
- **[Rumor]** 当前没有官方公开仓库层面的证据表明它已经发布 open weights。

## 快速导航

| 模块 | 文档 | 作用 |
| --- | --- | --- |
| 事实层 | [Verified Facts](./docs/verified-facts.md) | 只看当前能直接支持的事实 |
| 说法台账 | [Claims Ledger](./docs/claims-ledger.md) | 看 claim 的状态、置信度与来源 |
| 时间线 | [Timeline](./docs/timeline.md) | 看 Happy Horse 是怎么变成热门话题的 |
| 榜单层 | [Benchmarks](./docs/benchmarks.md) | 看有日期的 Elo / rank / sample 快照 |
| 信号地图 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | 看 benchmark、官方仓库、社区仓库、站点说法之间的关系 |
| 网址与风险 | [Official Links and Fakes](./docs/official-links-and-fakes.md) | 看应该点哪个站，以及哪些站点需要谨慎 |
| 对比阅读 | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | 看最重要的头对头比较如何解读 |
| Prompt 案例 | [Prompt Library](./docs/prompts/prompt-library.md) | 看该如何测试模型 |
| Failure Cases | [Failure Cases](./docs/prompts/failure-cases.md) | 看最容易被误导的地方 |
| 方法论 | [Methodology](./docs/methodology.md) | 看这个仓库如何分级和判断 |

## 公开信号从哪里来

目前主要有四层：

1. `官方仓库层`
   - 看官方现在真正公开了什么

2. `benchmark 层`
   - 看当前榜单、Elo、样本量和类别区分

3. `社区 GitHub 层`
   - 看 prompt、对比、rumor 和 narrative 是如何被放大的

4. `站点说法层`
   - 看哪些域名是安全入口，哪些只是 SEO 页面或不可靠入口

对应阅读：
- [Verified Facts](./docs/verified-facts.md)
- [Benchmarks](./docs/benchmarks.md)
- [Claims Ledger](./docs/claims-ledger.md)
- [Official Links and Fakes](./docs/official-links-and-fakes.md)
- [Public Signal Surfaces](./docs/public-signal-surfaces.md)

## 这个仓库怎么用

### 如果你想快速理解这个模型

建议按这个顺序读：

1. [Verified Facts](./docs/verified-facts.md)
2. [Timeline](./docs/timeline.md)
3. [Claims Ledger](./docs/claims-ledger.md)

### 如果你关心榜单和竞争格局

先看 [Benchmarks](./docs/benchmarks.md)，再看 [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md)。

### 如果你想亲自测试

先看 [Prompt Library](./docs/prompts/prompt-library.md)，再看 [Failure Cases](./docs/prompts/failure-cases.md)。

### 如果你只是想知道该点哪个网站

本仓库统一把对外展示入口收敛到 [Happy Horse](https://tryhappyhorse.com/)。其他域名如果出现，只作为分析材料，不作为推荐入口。

## 搜索意图 FAQ

### Happy Horse 是什么？

基于当前公开产品描述，[Happy Horse AI](https://tryhappyhorse.com/) 被呈现为一个强调电影感输出的视频生成产品，覆盖 text-to-video 和 image-to-video 场景。

### 为什么 Happy Horse 1.0 突然火了？

因为它同时具备产品叙事和 benchmark 叙事，两条传播路径叠加后，讨论速度非常快。详见 [Timeline](./docs/timeline.md) 与 [Benchmarks](./docs/benchmarks.md)。

### Happy Horse 开源了吗？

按照当前公开 GitHub 仓库，没有看到权重或推理代码公开发布。详见 [Claims Ledger](./docs/claims-ledger.md)。

### Happy Horse 可以本地运行吗？

按照当前公开信息，还不能得出这个结论，因为没有看到官方公开的本地运行资源。

### Happy Horse 有 API 吗？

公开 benchmark 页面里能看到类似 `Coming soon` 的 API 状态提示，但这应被视为时间敏感状态，而不是稳定承诺。详见 [Benchmarks](./docs/benchmarks.md)。

### Happy Horse 支持音频吗？

当前公开 benchmark 页面存在 `with audio` 类别，而 [Happy Horse 1.0](https://tryhappyhorse.com/) 在这些类别中表现很强，所以“音频能力”是当前讨论重点之一。详见 [Benchmarks](./docs/benchmarks.md)。

### Happy Horse 同时支持 text-to-video 和 image-to-video 吗？

从当前公开产品描述和 benchmark 讨论来看，是的。详见 [Verified Facts](./docs/verified-facts.md) 与 [Benchmarks](./docs/benchmarks.md)。

### Happy Horse 和 Seedance 哪个更强？

不能简单一句话下结论。当前公开快照显示 [Happy Horse 1.0](https://tryhappyhorse.com/) 在多个类别领先，但 `Image to Video (With Audio)` 里 Seedance 仍然领先。详见 [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md)。

### 除了 Seedance 之外，它还在和谁比较？

当前最重要的公开比较锚点还有 Kling 和 PixVerse。详见 [Benchmarks](./docs/benchmarks.md)。

### Happy Horse 背后是谁？

本仓库只记录当前能被公开来源较稳妥支持的信息。如果归属问题的证据还不够清晰，就不应该直接当作事实传播。详见 [Claims Ledger](./docs/claims-ledger.md) 和 [Methodology](./docs/methodology.md)。

### 我应该优先从哪些 prompt 角度测试？

优先从这些维度测试：

- cinematic environment
- multi-beat continuity
- product framing
- direct-to-camera speech
- image-to-video identity retention

详见 [Prompt Library](./docs/prompts/prompt-library.md)。

### 社交媒体上的对比视频可以直接信吗？

不建议直接相信。公开视频可能被误标、去上下文或选择性展示。详见 [Failure Cases](./docs/prompts/failure-cases.md)。

## 多语言说明

当前仓库已经提供：

- 英文 README
- 简体中文 README
- 日文 README
- 韩文 README
- 西班牙文 README
- 葡萄牙文 README
- 德文 README
- 法文 README
- 土耳其文 README
- 繁体中文 README
- 俄文 README

更深层的事实文档当前仍以英文为主，避免多语言版本之间出现事实漂移。

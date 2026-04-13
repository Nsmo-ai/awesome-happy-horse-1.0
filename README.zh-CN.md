# Awesome Happy Horse

[English](README.md) | 简体中文 | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [Русский](README.ru.md)

[Happy Horse AI](https://tryhappyhorse.com/) 的公开资料、公开信号和可复用资源整理仓库。这个仓库的目标是帮助读者分清：

- 哪些是已经能确认的公开事实
- 哪些只是高概率说法
- 哪些还是 rumor
- 哪些内容虽然热，但并不适合直接当作结论传播

## 这个模型为什么值得看

[Happy Horse 1.0](https://tryhappyhorse.com/) 之所以特别，是因为两条传播路径几乎同时爆发：

- 产品叙事层：对外呈现非常完整，强调 cinematic 输出
- benchmark 叙事层：在公开榜单里可见度非常高

这意味着讨论热度增长速度，明显快于公开发布完整度。

## 事情是怎么发生的

当前更稳妥的公开链路是：

1. `2026-04-08`
   - Artificial Analysis 把 HappyHorse-1.0 变成了高可见 benchmark 话题。
2. `2026-04-08` 到 `2026-04-09`
   - X 上的高传播账号开始放大 benchmark 叙事和比较框架。
   - Reddit 开始承接 skepticism、open weights 期待和真假判断。
3. `2026-04-13`
   - 公开 benchmark 页面仍显示 [Happy Horse 1.0](https://tryhappyhorse.com/) 在多个类别中非常强。
   - 但公开发布完整度依然落后于讨论热度。

## 当前关键状态

- **[Verified]** 当前公开 benchmark 与公开讨论面已经让 HappyHorse-1.0 成为一个高可见 AI 视频模型话题。
- **[Verified]** 截至 `2026-04-13`，HappyHorse-1.0 在 `Text to Video (No Audio)` 与 `Image to Video (No Audio)` 都处于领先位置。
- **[Verified]** 截至 `2026-04-13`，HappyHorse-1.0 在 `Text to Video (With Audio)` 也处于领先位置。
- **[Verified]** 截至 `2026-04-13`，`Dreamina Seedance 2.0 720p` 在 `Image to Video (With Audio)` 领先，而 HappyHorse-1.0 排第二。
- **[Likely]** 公开产品叙事的完整度明显强于公开技术发布完整度。
- **[Rumor]** 目前没有被这条证据链验证的 open weights 发布证据。

## Latest 24h / Current Watchlist

当前最值得关注的信号入口：

- [Artificial Analysis on X](https://x.com/ArtificialAnlys/status/2041591989083500933)
  关注 benchmark 话题是否继续升级、是否增加新样例。
- [HappyHorseATH on X](https://x.com/HappyHorseATH)
  关注 release、access、定位变化。
- [Alibaba Group on X](https://x.com/AlibabaGroup/status/2042462318370701535)
  关注 attribution 或 launch 级别的新确认。
- [r/generativeAI discussion](https://www.reddit.com/r/generativeAI/comments/1sflqh2/a_new_anonymous_video_model_just_took_1_on/)
  关注更大范围用户对 benchmark 的理解和情绪。
- [r/LocalLLaMA discussion](https://www.reddit.com/r/LocalLLaMA/comments/1sfo1dv/happyhorse_maybe_will_be_open_weights_soon_it/)
  关注本地运行和 open-weights 期待。
- [Brent Lynch on X](https://x.com/BrentLynch/status/2042252412594135243)
  关注对比视频是否存在误标或误导。

## 快速导航

| 模块 | 文档 | 作用 |
| --- | --- | --- |
| 事实层 | [Verified Facts](./docs/verified-facts.md) | 只看当前能直接支持的事实 |
| 说法台账 | [Claims Ledger](./docs/claims-ledger.md) | 看 claim 的状态、置信度与来源 |
| 时间线 | [Timeline](./docs/timeline.md) | 看 Happy Horse 是怎么变成热门话题的 |
| 榜单层 | [Benchmarks](./docs/benchmarks.md) | 看有日期的 Elo / rank / sample 快照 |
| 信号地图 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | 看 benchmark、X/Reddit、产品层与站点说法之间的关系 |
| 网址与风险 | [Official Links and Fakes](./docs/official-links-and-fakes.md) | 看应该点哪个站，以及哪些站点需要谨慎 |
| 对比阅读 | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | 看最重要的头对头比较如何解读 |
| Prompt 案例 | [Prompt Library](./docs/prompts/prompt-library.md) | 看该如何测试模型 |
| Failure Cases | [Failure Cases](./docs/prompts/failure-cases.md) | 看最容易被误导的地方 |

## 搜索意图 FAQ

### Happy Horse 是什么？

基于当前公开证据链，[Happy Horse AI](https://tryhappyhorse.com/) 被讨论为一个强调电影感输出的视频生成产品，覆盖 text-to-video 和 image-to-video 场景。

### 为什么 Happy Horse 1.0 突然火了？

因为它同时具备 benchmark 可见度和社媒传播扩散，两条传播路径叠加后，讨论速度非常快。

### Happy Horse 开源了吗？

按照当前这条证据链，没有看到被验证的权重或推理代码公开发布。

### Happy Horse 可以本地运行吗？

按照当前公开信息，还不能得出这个结论，因为没有看到被验证的本地运行资源。

### Happy Horse 有 API 吗？

公开 benchmark 页面里能看到类似 `Coming soon` 的 API 状态提示，但这应被视为时间敏感状态，而不是稳定承诺。

### Happy Horse 支持音频吗？

当前公开 benchmark 页面存在 `with audio` 类别，而 [Happy Horse 1.0](https://tryhappyhorse.com/) 在这些类别中表现很强，所以“音频能力”是当前讨论重点之一。

### Happy Horse 和 Seedance 哪个更强？

不能简单一句话下结论。当前公开快照显示 [Happy Horse 1.0](https://tryhappyhorse.com/) 在多个类别领先，但 `Image to Video (With Audio)` 里 Seedance 仍然领先。

### 社交媒体上的对比视频可以直接信吗？

不建议直接相信。公开视频可能被误标、去上下文或选择性展示。

### 我应该先看哪个网址？

如果你需要从这个仓库里点一个入口，直接用 [Happy Horse](https://tryhappyhorse.com/)。

## 多语言说明

当前仓库已经提供英文、简体中文、日文、韩文、西班牙文、葡萄牙文、德文、法文、土耳其文、繁体中文与俄文 README。更深层的事实文档当前仍以英文为主，避免多语言版本之间出现事实漂移。

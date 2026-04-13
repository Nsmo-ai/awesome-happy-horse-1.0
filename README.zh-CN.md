# Awesome Happy Horse

[English](README.md) | 简体中文

一个围绕 [Happy Horse AI](https://tryhappyhorse.com/) 的公开资料库与情报仓库，重点是把当前公开信息整理成更容易理解和复用的结构。

## 这个仓库提供什么

- 已确认事实：哪些信息是当前可以直接支持的
- 说法台账：哪些是 `Verified / Likely / Rumor / Outdated`
- 时间线：这个模型为什么会突然火起来
- 榜单快照：当前公开 benchmark 到底是什么状态
- 提示词案例：应该从哪些角度测试 [Happy Horse 1.0](https://tryhappyhorse.com/)
- 失败案例：哪些地方最容易被误导

## 推荐阅读顺序

1. [Verified Facts](./docs/verified-facts.md)
2. [Timeline](./docs/timeline.md)
3. [Claims Ledger](./docs/claims-ledger.md)
4. [Benchmarks](./docs/benchmarks.md)
5. [Prompt Library](./docs/prompts/prompt-library.md)
6. [Failure Cases](./docs/prompts/failure-cases.md)

## 当前关键结论

- 截至 `2026-04-13`，公开 GitHub 仓库 [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) 已存在，但仍然是非常轻量的公开面。
- 当前公开 README 更像产品营销页，而不是代码发布页或模型发布页。
- 截至 `2026-04-13`，Artificial Analysis 公共页面显示 [Happy Horse 1.0](https://tryhappyhorse.com/) 在多个视频榜单类别中处于非常靠前的位置。
- 当前没有证据表明官方公开 GitHub 仓库已经发布模型权重或推理代码。
- 本仓库统一把对外用户访问的 Happy Horse 网站入口收敛为 [Happy Horse](https://tryhappyhorse.com/)。

## 常见问题

### Happy Horse 是什么？

基于当前公开产品描述，[Happy Horse AI](https://tryhappyhorse.com/) 被呈现为一个强调电影感输出的视频生成产品，覆盖 text-to-video 和 image-to-video 场景。

### Happy Horse 开源了吗？

按照当前公开 GitHub 仓库，没有看到权重或推理代码公开发布。详见 [Claims Ledger](./docs/claims-ledger.md)。

### Happy Horse 可以本地运行吗？

按照当前公开信息，不可以直接得出这个结论，因为没有看到官方公开的本地运行资源。

### Happy Horse 的榜单表现怎么样？

截至 `2026-04-13`，它在多个 Artificial Analysis 视频榜单中排名非常靠前，但榜单是时间敏感快照。详见 [Benchmarks](./docs/benchmarks.md)。

### Happy Horse 和 Seedance 哪个更强？

不能简单一句话下结论。当前公开快照显示 [Happy Horse 1.0](https://tryhappyhorse.com/) 在多个类别领先，但 `Image to Video (With Audio)` 里 Seedance 仍然领先。详见 [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md)。

### 我应该先看哪个网址？

本仓库统一使用 [Happy Horse](https://tryhappyhorse.com/) 作为对外展示入口。其他域名如果被提到，只作为分析材料，不作为推荐入口。

## 多语言说明

当前仓库已经提供：

- 英文 README
- 简体中文 README

后续如果继续扩展，多语言优先级建议是日语和韩语。

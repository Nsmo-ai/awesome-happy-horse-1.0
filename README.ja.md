# Awesome Happy Horse

[English](README.md) | [简体中文](README.zh-CN.md) | 日本語 | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [Русский](README.ru.md)

[Happy Horse AI](https://tryhappyhorse.com/) に関する公開情報と公開シグナルを整理したリポジトリです。目的は、何が事実で、何が rumor で、何がまだ結論に値しないかを見分けやすくすることです。

## このモデルが注目される理由

[Happy Horse 1.0](https://tryhappyhorse.com/) は、benchmark 可視性と social amplification がほぼ同時に立ち上がったため、非常に速く話題化しました。

## 何が起きたのか

1. Artificial Analysis が HappyHorse-1.0 を benchmark discussion の中で強く可視化した。
2. X 上の高リーチ投稿が benchmark 物語と比較フレームを拡散した。
3. Reddit では skepticism、open weights 期待、信頼性の議論が増えた。

## 現在の重要ポイント

- **[Verified]** HappyHorse-1.0 は複数の公開 benchmark カテゴリで非常に強い位置にある。
- **[Verified]** `Text to Video (No Audio)` と `Image to Video (No Audio)` では先頭にいる。
- **[Verified]** `Text to Video (With Audio)` でも非常に強い位置にいる。
- **[Verified]** `Image to Video (With Audio)` では Seedance が先頭で、HappyHorse-1.0 は 2 位。
- **[Rumor]** open weights が既に公開されているという主張は、この証拠チェーンでは確認できない。

## Latest 24h / Current Watchlist

- [Artificial Analysis on X](https://x.com/ArtificialAnlys/status/2041591989083500933)
- [HappyHorseATH on X](https://x.com/HappyHorseATH)
- [Alibaba Group on X](https://x.com/AlibabaGroup/status/2042462318370701535)
- [r/generativeAI discussion](https://www.reddit.com/r/generativeAI/comments/1sflqh2/a_new_anonymous_video_model_just_took_1_on/)
- [r/LocalLLaMA discussion](https://www.reddit.com/r/LocalLLaMA/comments/1sfo1dv/happyhorse_maybe_will_be_open_weights_soon_it/)
- [Brent Lynch on X](https://x.com/BrentLynch/status/2042252412594135243)

## すぐ使える導線

- [Verified Facts](./docs/verified-facts.md)
- [Claims Ledger](./docs/claims-ledger.md)
- [Timeline](./docs/timeline.md)
- [Benchmarks](./docs/benchmarks.md)
- [Public Signal Surfaces](./docs/public-signal-surfaces.md)
- [Official Links and Fakes](./docs/official-links-and-fakes.md)
- [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md)
- [Prompt Library](./docs/prompts/prompt-library.md)
- [Failure Cases](./docs/prompts/failure-cases.md)

## FAQ

### Happy Horse とは何ですか？

[Happy Horse AI](https://tryhappyhorse.com/) は cinematic 出力を重視した video generation product として議論されています。

### Happy Horse はオープンソースですか？

この証拠チェーンでは、重みや推論コードの公開は確認できません。

### Happy Horse はローカル実行できますか？

現在の公開情報だけでは、ローカル実行できると判断できません。

### Happy Horse の benchmark 状況は？

`2026-04-13` 時点で、複数の公開カテゴリで非常に高い位置にあります。

### Happy Horse は Seedance より強いのですか？

単純な yes / no では答えにくいです。複数カテゴリで強い一方、`Image to Video (With Audio)` では Seedance が先頭です。

### どのサイトを見ればいいですか？

このリポジトリでは、入口として [Happy Horse](https://tryhappyhorse.com/) を使います。

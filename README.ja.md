# Awesome Happy Horse

[English](README.md) | [简体中文](README.zh-CN.md) | 日本語 | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [Русский](README.ru.md)

[Happy Horse AI](https://tryhappyhorse.com/) に関する公開情報、公開シグナル、再利用しやすいリソースを整理したリポジトリです。目的は、単なる情報収集ではなく、以下を見分けやすくすることです。

- いま直接確認できる事実
- 高確度だが未確定な話
- まだ rumor の段階にある話
- 話題にはなっているが、そのまま拡散すべきではない情報

## このリポジトリが役立つ理由

[Happy Horse 1.0](https://tryhappyhorse.com/) が特殊なのは、製品物語と benchmark 物語がほぼ同時に立ち上がったことです。

- 製品側では、シネマティックな動画生成という強いポジショニング
- ベンチマーク側では、複数カテゴリで非常に強い可視性

そのため、公開情報の整備よりも先に議論だけが膨らみやすい状態になっています。

## 何が起きたのか

現在の公開タイムラインは短いですが、流れを理解するには十分です。

1. `2026-04-08`
   - 公開リポジトリ [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) が GitHub に登場。
   - 公開 README はコードやモデルのリリースではなく、製品紹介型だった。

2. `2026-04-08` から `2026-04-09`
   - コミュニティの GitHub リポジトリが prompt、benchmark、rumor、source tracking など複数の角度から話題を拡張した。

3. `2026-04-13`
   - 公開 benchmark ページでは [Happy Horse 1.0](https://tryhappyhorse.com/) が複数カテゴリで非常に強い位置にある。
   - 一方で、公式公開 GitHub リポジトリには重みや推論コードはまだ見えない。

## 現在の重要ポイント

- **[Verified]** 公開リポジトリ [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) は存在する。
- **[Verified]** 公開説明では Happy Horse AI は `1080p cinematic video` と `advanced motion synthesis` を打ち出している。
- **[Verified]** 現在の公開 README はマーケティング寄りで、コード公開ページではない。
- **[Verified]** `2026-04-13` 時点で、HappyHorse-1.0 は `Text to Video (No Audio)` と `Image to Video (No Audio)` で先頭にいる。
- **[Verified]** `Text to Video (With Audio)` でも非常に強い位置にいる。
- **[Verified]** `Image to Video (With Audio)` では Seedance が先頭で、HappyHorse-1.0 は 2 位。
- **[Rumor]** 現時点で open weights が既に公開されているという主張は、公式公開 GitHub リポジトリでは支えられていない。

## すぐ使える導線

| セクション | ドキュメント | 役割 |
| --- | --- | --- |
| 事実レイヤー | [Verified Facts](./docs/verified-facts.md) | 直接確認できる事実だけを読む |
| クレーム台帳 | [Claims Ledger](./docs/claims-ledger.md) | 各 claim の状態、信頼度、出典を見る |
| タイムライン | [Timeline](./docs/timeline.md) | どうやって話題になったかを追う |
| ベンチマーク | [Benchmarks](./docs/benchmarks.md) | 日付付きの Elo / rank / sample snapshot を見る |
| シグナル地図 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | benchmark、公式 repo、コミュニティ repo、サイト主張の関係を見る |
| 比較読解 | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | もっとも重要な head-to-head を読む |
| Prompt ケース | [Prompt Library](./docs/prompts/prompt-library.md) | 何をどう試すかを見る |
| Failure Cases | [Failure Cases](./docs/prompts/failure-cases.md) | どこで誤解しやすいかを見る |
| シグナル地図 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | benchmark、公式 repo、コミュニティ repo、サイト主張の関係を見る |

## 公開シグナルはどこから来るのか

現在の公開シグナルは、大きく四つの層で読むのが安全です。

1. `公式 repo 層`
   - 公式がいま何を公開しているか

2. `benchmark 層`
   - Elo、rank、sample 数、with-audio / no-audio の区別

3. `コミュニティ GitHub 層`
   - prompt、comparison、rumor、source tracking がどのように拡散しているか

4. `サイト主張層`
   - どのドメインが安全な入口で、どのページが単なる SEO なのか

対応する読み先:

- [Verified Facts](./docs/verified-facts.md)
- [Benchmarks](./docs/benchmarks.md)
- [Claims Ledger](./docs/claims-ledger.md)
- [Official Links and Fakes](./docs/official-links-and-fakes.md)
- [Public Signal Surfaces](./docs/public-signal-surfaces.md)

## FAQ

### Happy Horse とは何ですか？

現在の公開製品説明に基づくと、[Happy Horse AI](https://tryhappyhorse.com/) は cinematic な出力を重視した text-to-video / image-to-video 製品として提示されています。

### Happy Horse はオープンソースですか？

現在の公開 GitHub リポジトリを見る限り、重みや推論コードの公開は確認できません。詳しくは [Claims Ledger](./docs/claims-ledger.md) を参照してください。

### Happy Horse はローカル実行できますか？

現在の公開情報だけでは、ローカル実行できると判断できません。公開された重みや推論パッケージは確認されていません。

### Happy Horse の benchmark 状況は？

`2026-04-13` 時点で、[Happy Horse 1.0](https://tryhappyhorse.com/) は複数の Artificial Analysis ランキングで非常に高い位置にあります。ただし、これらは日付つきの snapshot です。詳しくは [Benchmarks](./docs/benchmarks.md) を参照してください。

### Happy Horse は Seedance より強いのですか？

単純な yes / no では答えにくいです。`2026-04-13` 時点では複数カテゴリで Happy Horse 1.0 が強い一方、`Image to Video (With Audio)` では Seedance が先頭です。詳しくは [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) と [Benchmarks](./docs/benchmarks.md) を参照してください。

### Happy Horse 以外に誰と比べられていますか？

いま重要な比較相手は Seedance、Kling、PixVerse です。これらは benchmark 議論の主要アンカーになっています。

### どの prompt から試すのが良いですか？

このリポジトリでは、次の観点を優先して試すことを勧めています。

- cinematic environment
- multi-beat continuity
- product framing
- direct-to-camera speech
- image-to-video identity retention

詳しくは [Prompt Library](./docs/prompts/prompt-library.md) を参照してください。

### SNS 上の比較動画はそのまま信じてよいですか？

おすすめしません。公開比較動画は mislabeled、文脈欠落、選択的編集の問題を抱えることがあります。詳しくは [Failure Cases](./docs/prompts/failure-cases.md) を参照してください。

### どのサイトを見ればいいですか？

このリポジトリでは、対外的な導線を [Happy Horse](https://tryhappyhorse.com/) に統一しています。その他のドメインは分析対象としてのみ扱います。

## 多言語について

現在、このリポジトリは英語、中国語、日本語、韓国語、スペイン語、ポルトガル語、ドイツ語、フランス語、トルコ語、繁體中文、ロシア語の README を提供しています。深い証拠ドキュメントは現時点では英語を主軸にしています。

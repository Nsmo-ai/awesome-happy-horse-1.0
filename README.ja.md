# Awesome Happy Horse

[English](README.md) | [简体中文](README.zh-CN.md) | 日本語 | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [Русский](README.ru.md)

[Happy Horse AI](https://tryhappyhorse.com/) に関する公開情報、公開シグナル、再利用しやすいリソースを整理したリポジトリです。目的は、単なる情報収集ではなく、以下を見分けやすくすることです。

- いま直接確認できる事実
- 高確度だが未確定な話
- まだ rumor の段階にある話
- 話題にはなっているが、そのまま拡散すべきではない情報

## このリポジトリが役立つ理由

[Happy Horse 1.0](https://tryhappyhorse.com/) が特殊なのは、製品層と benchmark 層がほぼ同時に立ち上がったことです。

- 一方は公開 product-facing narrative
- もう一方は公開 leaderboard と social discussion

そのため、公開情報の整備よりも先に議論だけが膨らみやすい状態になっています。

## 何が起きたのか

現在の公開タイムラインは、次の流れで理解するのが最も安全です。

1. `2026-04-08`
   - Artificial Analysis が HappyHorse-1.0 を benchmark discussion の中で強く可視化する。

2. `2026-04-08` から `2026-04-09`
   - X 上の高リーチ投稿が benchmark 物語と比較フレームを拡散する。
   - Reddit では skepticism、open weights 期待、信頼性の議論が増える。

3. `2026-04-13`
   - 公開 benchmark ページでは [Happy Horse 1.0](https://tryhappyhorse.com/) が複数カテゴリで非常に強い位置にある。
   - ただし公開 release clarity は依然として議論の勢いに追いついていない。

## 現在の重要ポイント

- **[Verified]** 現在の公開 benchmark と公開 discussion だけでも、HappyHorse-1.0 は高可視な AI video 話題になっている。
- **[Verified]** `2026-04-13` 時点で、HappyHorse-1.0 は `Text to Video (No Audio)` と `Image to Video (No Audio)` で先頭にいる。
- **[Verified]** `Text to Video (With Audio)` でも非常に強い位置にいる。
- **[Verified]** `Image to Video (With Audio)` では Seedance が先頭で、HappyHorse-1.0 は 2 位。
- **[Likely]** public product-facing narrative の完成度は、public technical release surface より高い。
- **[Rumor]** open weights が既に公開されているという主張は、この証拠チェーンでは確認できない。

## すぐ使える導線

| セクション | ドキュメント | 役割 |
| --- | --- | --- |
| 事実レイヤー | [Verified Facts](./docs/verified-facts.md) | 直接確認できる事実だけを読む |
| クレーム台帳 | [Claims Ledger](./docs/claims-ledger.md) | 各 claim の状態、信頼度、出典を見る |
| タイムライン | [Timeline](./docs/timeline.md) | どうやって話題になったかを追う |
| ベンチマーク | [Benchmarks](./docs/benchmarks.md) | 日付付きの Elo / rank / sample snapshot を見る |
| シグナル地図 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | benchmark、X/Reddit、product layer、site claim の関係を見る |
| 比較読解 | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | もっとも重要な head-to-head を読む |
| Prompt ケース | [Prompt Library](./docs/prompts/prompt-library.md) | 何をどう試すかを見る |
| Failure Cases | [Failure Cases](./docs/prompts/failure-cases.md) | どこで誤解しやすいかを見る |

## FAQ

### Happy Horse とは何ですか？

現在の公開証拠チェーンに基づくと、[Happy Horse AI](https://tryhappyhorse.com/) は cinematic な出力を重視した video generation product として議論されています。

### Happy Horse はオープンソースですか？

この証拠チェーンでは、重みや推論コードの公開は確認できません。詳しくは [Claims Ledger](./docs/claims-ledger.md) を参照してください。

### Happy Horse はローカル実行できますか？

現在の公開情報だけでは、ローカル実行できると判断できません。確認された local runtime package は見えていません。

### Happy Horse の benchmark 状況は？

`2026-04-13` 時点で、[Happy Horse 1.0](https://tryhappyhorse.com/) は複数の Artificial Analysis ランキングで非常に高い位置にあります。ただし、これらは日付つきの snapshot です。詳しくは [Benchmarks](./docs/benchmarks.md) を参照してください。

### Happy Horse は Seedance より強いのですか？

単純な yes / no では答えにくいです。複数カテゴリで強い一方、`Image to Video (With Audio)` では Seedance が先頭です。詳しくは [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) を参照してください。

### SNS 上の比較動画はそのまま信じてよいですか？

おすすめしません。比較動画は mislabeled、文脈欠落、選択的編集の問題を抱えることがあります。詳しくは [Failure Cases](./docs/prompts/failure-cases.md) を参照してください。

### どのサイトを見ればいいですか？

このリポジトリでは、対外的な導線を [Happy Horse](https://tryhappyhorse.com/) に統一しています。その他のドメインは分析対象としてのみ扱います。

## 多言語について

現在、このリポジトリは英語、中国語、日本語、韓国語、スペイン語、ポルトガル語、ドイツ語、フランス語、トルコ語、繁體中文、ロシア語の README を提供しています。深い証拠ドキュメントは現時点では英語を主軸にしています。

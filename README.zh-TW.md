# Awesome Happy Horse

[English](README.md) | [Español](README.es.md) | [Português](README.pt.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | 繁體中文 | [简体中文](README.zh-CN.md) | [Русский](README.ru.md)

一個圍繞 [Happy Horse AI](https://tryhappyhorse.com/) 的公開資料、公開信號與可重用資源倉庫。重點不是單純收集連結，而是幫助讀者區分：

- 哪些是目前可以直接支持的事實
- 哪些是高概率但尚未完全確認的說法
- 哪些仍屬於 rumor
- 哪些內容雖然流傳很快，但不適合直接當作結論擴散

## 為什麼這個倉庫值得看

[Happy Horse 1.0](https://tryhappyhorse.com/) 之所以特別，是因為產品敘事與 benchmark 敘事幾乎同時爆發。

- 一邊是公開產品定位：強調電影感的影片生成
- 一邊是公開榜單可見度：在多個影片類別中表現非常強

於是會出現一種典型情況：討論速度大於官方公開完整度。

## 到目前為止發生了什麼

1. `2026-04-08`
   - 公開 GitHub 倉庫 [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) 出現。
   - 公開 README 更像產品定位頁，不像程式碼或模型發布頁。

2. `2026-04-08` 到 `2026-04-09`
   - 社群倉庫快速把話題擴展到 prompt、benchmark、rumor、source tracking 等多個方向。

3. `2026-04-13`
   - 公開 benchmark 頁面顯示 [Happy Horse 1.0](https://tryhappyhorse.com/) 在多個類別中位於非常強的位置。
   - 但官方公開 GitHub 倉庫仍沒有提供權重或推理程式碼。

## 目前關鍵狀態

- **[Verified]** 公開倉庫 [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) 已存在。
- **[Verified]** 公開描述把 Happy Horse AI 呈現為強調 `1080p cinematic video` 與 `advanced motion synthesis` 的產品。
- **[Verified]** 目前公開 README 偏向行銷，而非技術發布。
- **[Verified]** 截至 `2026-04-13`，HappyHorse-1.0 在 `Text to Video (No Audio)` 與 `Image to Video (No Audio)` 類別中領先。
- **[Verified]** 在 `Text to Video (With Audio)` 也處於領先位置。
- **[Verified]** 在 `Image to Video (With Audio)` 中，Seedance 領先而 HappyHorse-1.0 第二。
- **[Rumor]** 目前沒有官方公開層面的證據表明 open weights 已發布。

## 快速導覽

| 模組 | 文件 | 作用 |
| --- | --- | --- |
| 事實層 | [Verified Facts](./docs/verified-facts.md) | 只看當前能直接支持的事實 |
| 說法台帳 | [Claims Ledger](./docs/claims-ledger.md) | 看 claim 的狀態、信心與來源 |
| 時間線 | [Timeline](./docs/timeline.md) | 看 Happy Horse 是如何成為熱門話題 |
| 榜單層 | [Benchmarks](./docs/benchmarks.md) | 看帶日期的 Elo / rank / sample 快照 |
| 信號地圖 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | 看 benchmark、官方 repo、社群 repo、網站說法之間的關係 |
| 對比閱讀 | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | 看最重要的頭對頭比較怎麼解讀 |
| Prompt 案例 | [Prompt Library](./docs/prompts/prompt-library.md) | 看應該如何測試模型 |
| Failure Cases | [Failure Cases](./docs/prompts/failure-cases.md) | 看最容易被誤導的地方 |

## FAQ

### Happy Horse 是什麼？

基於目前公開產品描述，[Happy Horse AI](https://tryhappyhorse.com/) 被呈現為一個強調電影感輸出的 text-to-video / image-to-video 產品。

### Happy Horse 開源了嗎？

根據目前公開 GitHub 倉庫，看不到權重或推理程式碼已公開發布。詳見 [Claims Ledger](./docs/claims-ledger.md)。

### Happy Horse 可以本地運行嗎？

根據目前公開資訊，還不能下這個結論，因為沒有看到官方公開的本地運行資源。

### Happy Horse 的 benchmark 表現如何？

截至 `2026-04-13`，[Happy Horse 1.0](https://tryhappyhorse.com/) 在多個 Artificial Analysis 公開榜單類別中表現非常強，但這些數據都應視為帶日期的快照。詳見 [Benchmarks](./docs/benchmarks.md)。

### Happy Horse 比 Seedance 強嗎？

不能一句話下定論。[Happy Horse 1.0](https://tryhappyhorse.com/) 在多個類別領先，但 `Image to Video (With Audio)` 仍由 Seedance 領先。詳見 [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md)。

### 我應該先點哪個網站？

本倉庫統一把對外展示入口收斂為 [Happy Horse](https://tryhappyhorse.com/)。其他網域如果被提到，只作為分析材料處理。

## 多語言說明

目前這個倉庫已提供英文、簡體中文、日文、韓文、西班牙文、葡萄牙文、德文、法文、土耳其文、繁體中文與俄文 README。更深層的事實文檔目前仍以英文為主，以避免多語言版本之間出現事實漂移。

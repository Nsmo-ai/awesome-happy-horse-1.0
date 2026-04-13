# Awesome Happy Horse

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | 한국어 | [Español](README.es.md) | [Português](README.pt.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [Русский](README.ru.md)

[Happy Horse AI](https://tryhappyhorse.com/) 에 대한 공개 정보, 공개 신호, 재사용 가능한 자료를 구조화한 저장소입니다. 핵심 목표는 다음을 구분하기 쉽게 만드는 것입니다.

- 지금 직접 확인 가능한 사실
- 가능성이 높지만 아직 확정되지 않은 내용
- 아직 rumor 단계에 있는 주장
- 화제성은 높지만 그대로 확산하면 위험한 정보

## 왜 이 저장소가 필요한가

[Happy Horse 1.0](https://tryhappyhorse.com/) 의 특징은 product layer 와 benchmark layer 가 거의 동시에 폭발했다는 점입니다.

- 한쪽은 public product-facing narrative
- 다른 한쪽은 public leaderboard 와 social discussion

그래서 공개 정보 정리보다 논의 확산 속도가 더 빠릅니다.

## 현재까지의 흐름

가장 안전한 공개 흐름은 다음과 같습니다.

1. `2026-04-08`
   - Artificial Analysis 가 HappyHorse-1.0 을 benchmark discussion 안에서 강하게 가시화합니다.

2. `2026-04-08` ~ `2026-04-09`
   - X 의 고도달 계정들이 benchmark 서사와 비교 프레임을 확대합니다.
   - Reddit 에서는 skepticism, open-weights 기대, 신뢰성 관련 논의가 커집니다.

3. `2026-04-13`
   - 공개 benchmark 페이지에서 [Happy Horse 1.0](https://tryhappyhorse.com/) 은 여러 카테고리에서 매우 강한 위치를 보입니다.
   - 그러나 공개 release clarity 는 여전히 논의 강도보다 약합니다.

## 현재 핵심 포인트

- **[Verified]** 현재의 공개 benchmark 와 공개 discussion 만으로도 HappyHorse-1.0 은 매우 가시적인 AI video 주제가 되었습니다.
- **[Verified]** `2026-04-13` 기준 HappyHorse-1.0 은 `Text to Video (No Audio)` 와 `Image to Video (No Audio)` 에서 선두입니다.
- **[Verified]** `Text to Video (With Audio)` 에서도 매우 강한 위치에 있습니다.
- **[Verified]** `Image to Video (With Audio)` 에서는 Seedance 가 선두이고 HappyHorse-1.0 은 2위입니다.
- **[Likely]** public product-facing narrative 의 완성도는 public technical release surface 보다 높습니다.
- **[Rumor]** open weights 가 이미 공개되었다는 주장은 이 증거 체계로는 확인되지 않습니다.

## 빠른 탐색 경로

| 섹션 | 문서 | 역할 |
| --- | --- | --- |
| 사실 레이어 | [Verified Facts](./docs/verified-facts.md) | 직접 확인 가능한 사실만 읽기 |
| 주장 레저 | [Claims Ledger](./docs/claims-ledger.md) | 각 claim 의 상태와 출처 확인 |
| 타임라인 | [Timeline](./docs/timeline.md) | 어떻게 화제가 됐는지 이해 |
| benchmark | [Benchmarks](./docs/benchmarks.md) | 날짜가 붙은 Elo / rank / sample snapshot 확인 |
| 신호 지도 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | benchmark, X/Reddit, product layer, site claim 관계 파악 |
| 비교 읽기 | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | 핵심 비교 구도 해석 |
| prompt 사례 | [Prompt Library](./docs/prompts/prompt-library.md) | 무엇을 어떻게 테스트할지 확인 |
| failure 사례 | [Failure Cases](./docs/prompts/failure-cases.md) | 오해하기 쉬운 지점 확인 |

## FAQ

### Happy Horse 는 무엇인가요?

현재 공개 증거 체계 기준으로 [Happy Horse AI](https://tryhappyhorse.com/) 는 cinematic 출력 중심의 video generation product 로 논의되고 있습니다.

### Happy Horse 는 오픈소스인가요?

이 증거 체계에서는 공개된 가중치나 추론 코드를 확인할 수 없습니다. 자세한 내용은 [Claims Ledger](./docs/claims-ledger.md) 를 참고하세요.

### Happy Horse 를 로컬에서 실행할 수 있나요?

현재 공개 정보만으로는 그렇게 판단할 수 없습니다. 확인된 local runtime package 는 보이지 않습니다.

### Happy Horse 의 benchmark 상태는 어떤가요?

`2026-04-13` 기준, [Happy Horse 1.0](https://tryhappyhorse.com/) 은 여러 Artificial Analysis 랭킹에서 매우 강한 위치에 있습니다. 다만 이는 날짜가 붙은 snapshot 입니다. 자세한 내용은 [Benchmarks](./docs/benchmarks.md) 를 참고하세요.

### Happy Horse 가 Seedance 보다 더 강한가요?

단순히 yes / no 로 답하기는 어렵습니다. 여러 카테고리에서 강하지만, `Image to Video (With Audio)` 에서는 Seedance 가 여전히 앞섭니다. 자세한 내용은 [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) 를 참고하세요.

### 소셜 미디어 비교 영상은 그대로 믿어도 되나요?

권장하지 않습니다. 비교 영상은 mislabeled, 문맥 손실, 선택적 편집 문제를 가질 수 있습니다. 자세한 내용은 [Failure Cases](./docs/prompts/failure-cases.md) 를 참고하세요.

### 어떤 사이트를 먼저 봐야 하나요?

이 저장소는 외부 사용자용 Happy Horse 사이트 링크를 [Happy Horse](https://tryhappyhorse.com/) 로 통일합니다. 다른 도메인은 분석 자료로만 다룹니다.

## 다국어 안내

현재 이 저장소는 영어, 중국어 간체, 일본어, 한국어, 스페인어, 포르투갈어, 독일어, 프랑스어, 터키어, 번체 중국어, 러시아어 README 를 제공합니다. 더 깊은 증거 문서는 현재 영어를 기준으로 유지합니다.

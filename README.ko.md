# Awesome Happy Horse

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | 한국어 | [Español](README.es.md) | [Português](README.pt.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Türkçe](README.tr.md) | [繁體中文](README.zh-TW.md) | [Русский](README.ru.md)

[Happy Horse AI](https://tryhappyhorse.com/) 에 대한 공개 정보, 공개 신호, 재사용 가능한 자료를 구조화한 저장소입니다. 핵심 목표는 다음을 구분하기 쉽게 만드는 것입니다.

- 지금 직접 확인 가능한 사실
- 가능성이 높지만 아직 확정되지 않은 내용
- 아직 rumor 단계에 있는 주장
- 화제성은 높지만 그대로 확산하면 위험한 정보

## 왜 이 저장소가 필요한가

[Happy Horse 1.0](https://tryhappyhorse.com/) 의 특징은 제품 서사와 benchmark 서사가 거의 동시에 폭발했다는 점입니다.

- 제품 측면에서는 cinematic video generation 이라는 강한 포지셔닝
- benchmark 측면에서는 여러 공개 카테고리에서의 강한 가시성

이 때문에 공개 정보 정리보다 논의 속도가 더 빨라졌고, 많은 사용자가 같은 질문을 반복하게 됐습니다.

## 현재까지의 흐름

1. `2026-04-08`
   - 공개 저장소 [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) 가 GitHub 에 등장했습니다.
   - 공개 README 는 코드 공개가 아니라 제품 마케팅 페이지에 가까웠습니다.

2. `2026-04-08` ~ `2026-04-09`
   - 커뮤니티 저장소들이 prompt, benchmark, rumor, source tracking 등 여러 방향으로 서사를 확장했습니다.

3. `2026-04-13`
   - 공개 benchmark 페이지에서 [Happy Horse 1.0](https://tryhappyhorse.com/) 은 여러 카테고리에서 매우 강한 위치를 보입니다.
   - 하지만 공식 공개 GitHub 저장소에는 여전히 가중치나 추론 코드가 보이지 않습니다.

## 현재 핵심 포인트

- **[Verified]** 공개 저장소 [`happyhorseai/happyhorse`](https://github.com/happyhorseai/happyhorse) 는 존재합니다.
- **[Verified]** 공개 설명은 Happy Horse AI 를 `1080p cinematic video` 와 `advanced motion synthesis` 를 강조하는 제품으로 제시합니다.
- **[Verified]** 현재 공개 README 는 마케팅 중심이며, 코드 공개 페이지가 아닙니다.
- **[Verified]** `2026-04-13` 기준 HappyHorse-1.0 은 `Text to Video (No Audio)` 와 `Image to Video (No Audio)` 에서 선두입니다.
- **[Verified]** `Image to Video (With Audio)` 에서는 Seedance 가 선두이고 HappyHorse-1.0 은 2위입니다.
- **[Rumor]** 이미 open weights 가 공개되었다는 주장은 현재 공식 GitHub 공개면으로는 뒷받침되지 않습니다.

## 빠른 탐색 경로

| 섹션 | 문서 | 역할 |
| --- | --- | --- |
| 사실 레이어 | [Verified Facts](./docs/verified-facts.md) | 직접 확인 가능한 사실만 읽기 |
| 주장 레저 | [Claims Ledger](./docs/claims-ledger.md) | 각 claim 의 상태와 출처 확인 |
| 타임라인 | [Timeline](./docs/timeline.md) | 어떻게 화제가 됐는지 이해 |
| benchmark | [Benchmarks](./docs/benchmarks.md) | 날짜가 붙은 Elo / rank / sample snapshot 확인 |
| 신호 지도 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | benchmark, 공식 repo, 커뮤니티 repo, 사이트 주장 간 관계 파악 |
| 비교 읽기 | [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) | 핵심 비교 구도 해석 |
| prompt 사례 | [Prompt Library](./docs/prompts/prompt-library.md) | 무엇을 어떻게 테스트할지 확인 |
| failure 사례 | [Failure Cases](./docs/prompts/failure-cases.md) | 오해하기 쉬운 지점 확인 |
| 신호 지도 | [Public Signal Surfaces](./docs/public-signal-surfaces.md) | benchmark, 공식 repo, 커뮤니티 repo, 사이트 주장 간 관계 파악 |

## 공개 신호는 어디서 오는가

현재 공개 신호는 네 개 층으로 읽는 것이 가장 안전합니다.

1. `공식 repo 층`
   - 지금 실제로 무엇이 공개되었는가

2. `benchmark 층`
   - Elo, rank, sample 수, with-audio / no-audio 구분

3. `커뮤니티 GitHub 층`
   - prompt, comparison, rumor, source tracking 이 어떻게 증폭되는가

4. `사이트 주장 층`
   - 어떤 도메인이 안전한 진입점이고, 어떤 페이지가 단지 SEO 페이지인지

권장 읽기:

- [Verified Facts](./docs/verified-facts.md)
- [Benchmarks](./docs/benchmarks.md)
- [Claims Ledger](./docs/claims-ledger.md)
- [Official Links and Fakes](./docs/official-links-and-fakes.md)
- [Public Signal Surfaces](./docs/public-signal-surfaces.md)

## FAQ

### Happy Horse 는 무엇인가요?

현재 공개 제품 설명 기준으로 [Happy Horse AI](https://tryhappyhorse.com/) 는 cinematic 출력 중심의 text-to-video / image-to-video 제품으로 제시되고 있습니다.

### Happy Horse 는 오픈소스인가요?

현재 공개 GitHub 저장소 기준으로는 가중치나 추론 코드 공개를 확인할 수 없습니다. 자세한 내용은 [Claims Ledger](./docs/claims-ledger.md) 를 참고하세요.

### Happy Horse 를 로컬에서 실행할 수 있나요?

현재 공개 정보만으로는 그렇게 판단할 수 없습니다. 공개된 가중치나 로컬 추론 패키지가 확인되지 않았습니다.

### Happy Horse 의 benchmark 상태는 어떤가요?

`2026-04-13` 기준, [Happy Horse 1.0](https://tryhappyhorse.com/) 은 여러 Artificial Analysis 랭킹에서 매우 강한 위치에 있습니다. 다만 이는 날짜가 붙은 snapshot 입니다. 자세한 내용은 [Benchmarks](./docs/benchmarks.md) 를 참고하세요.

### Happy Horse 가 Seedance 보다 더 강한가요?

단순히 yes / no 로 답하기는 어렵습니다. `2026-04-13` 기준 여러 카테고리에서 Happy Horse 1.0 이 강하지만, `Image to Video (With Audio)` 에서는 Seedance 가 여전히 앞섭니다. 자세한 내용은 [Happy Horse vs Seedance](./docs/comparisons/happy-horse-vs-seedance.md) 와 [Benchmarks](./docs/benchmarks.md) 를 참고하세요.

### Seedance 외에 누구와 비교되나요?

현재 중요한 비교 앵커는 Seedance, Kling, PixVerse 입니다. 이 모델들이 benchmark 논의의 핵심 비교축 역할을 합니다.

### 어떤 prompt 부터 테스트하는 것이 좋나요?

이 저장소는 다음 관점을 우선 테스트하는 것을 권장합니다.

- cinematic environment
- multi-beat continuity
- product framing
- direct-to-camera speech
- image-to-video identity retention

자세한 내용은 [Prompt Library](./docs/prompts/prompt-library.md) 를 참고하세요.

### 소셜 미디어 비교 영상은 그대로 믿어도 되나요?

권장하지 않습니다. 공개 비교 영상은 mislabeled, 문맥 손실, 선택적 편집 문제를 가질 수 있습니다. 자세한 내용은 [Failure Cases](./docs/prompts/failure-cases.md) 를 참고하세요.

### 어떤 사이트를 먼저 봐야 하나요?

이 저장소는 외부 사용자용 Happy Horse 사이트 링크를 [Happy Horse](https://tryhappyhorse.com/) 로 통일합니다. 다른 도메인은 분석 자료로만 다룹니다.

## 다국어 안내

현재 이 저장소는 영어, 중국어 간체, 일본어, 한국어, 스페인어, 포르투갈어, 독일어, 프랑스어, 터키어, 번체 중국어, 러시아어 README 를 제공합니다. 더 깊은 증거 문서는 현재 영어를 기준으로 유지합니다.

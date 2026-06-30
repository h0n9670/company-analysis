# 기업 분석 스킬 플레이북

Claude Code에 설치된 PM 스킬 중 **기업 분석**에 유용한 것들을 우선순위로 정리.
W1 프레임워크 문서([W1-company-analysis-frameworks.md](./W1-company-analysis-frameworks.md))와 매핑.

---

## 추천 실행 순서 (기업 1곳 분석 시)

```
1. market-scan          → 거시환경·산업구조 스캔
2. market-sizing        → TAM/SAM/SOM
3. competitive-analysis → 경쟁 구도·강약점
4. business-model       → 수익·가치 전달 구조
5. user-segmentation    → 타겟 세그먼트
```

각 스킬 실행 결과는 `analysis/<기업명>/` 폴더에 저장한다.
(예: `analysis/toss/01-market-scan.md`)

---

## 1순위 — 시장·경쟁 분석 핵심

| 스킬 | 용도 | 프레임워크 매핑 |
|---|---|---|
| `pm-product-strategy:market-scan` | SWOT·PESTLE·Porter 5 Forces·Ansoff 한 번에 스캔 | §0, §2 산업 구조 |
| `pm-market-research:competitive-analysis` | 경쟁 구도·강약점·차별화 기회 | §3 경쟁사 분석 |
| `pm-market-research:market-sizing` | TAM/SAM/SOM (top-down·bottom-up) | §1 시장 규모 |
| `pm-market-research:user-segmentation` | 행동 기반 세그먼트 분류 | §6 세그멘테이션 |

## 2순위 — 세부 프레임워크 심화 (단품)

- `pm-product-strategy:porters-five-forces` — 산업 매력도 정밀 분석
- `pm-product-strategy:swot-analysis` — 자사/대상 기업 포지션 평가
- `pm-product-strategy:pestle-analysis` — 거시환경(규제·기술·경제)
- `pm-go-to-market:competitive-battlecard` — 경쟁사 1:1 비교·대응

## 3순위 — 비즈니스 모델·가치 분석

- `pm-product-strategy:business-model` — Business Model Canvas 9블록 (디커플링 §5 분석에 유용)
- `pm-product-strategy:value-proposition` — 가치 제안 분해
- `pm-product-strategy:monetization-strategy` / `pricing-strategy` — 수익 모델
- `pm-go-to-market:ideal-customer-profile` / `beachhead-segment` — 타겟 고객 정의

## 4순위 — 데이터·고객 기반 분석 (정량 검증)

- `pm-data-analytics:cohort-analysis` — 리텐션·First 7 Days 검증
- `pm-market-research:customer-journey-map` — 고객 여정·페인포인트
- `pm-market-research:user-personas` — 데이터 기반 퍼소나

---

## 진행 체크리스트 (기업별 복사해서 사용)

분석 대상: `_______`

- [ ] 1. market-scan → `analysis/<기업>/01-market-scan.md`
- [ ] 2. market-sizing → `analysis/<기업>/02-market-sizing.md`
- [ ] 3. competitive-analysis → `analysis/<기업>/03-competitive-analysis.md`
- [ ] 4. business-model → `analysis/<기업>/04-business-model.md`
- [ ] 5. user-segmentation → `analysis/<기업>/05-user-segmentation.md`

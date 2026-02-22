# Ideation Index (SSOT)

**1-minute goal:** 이 문서만 열어도 다음 1~2개 실행 액션을 바로 고를 수 있어야 합니다.

## Start Here (Canonical Pointers)

- Repo docs entrypoint: [../INDEX.md](../INDEX.md)
- Workflow PRD SSOT: [../PRD.md](../PRD.md)
- Product PRD SSOT: [../PRODUCT_PRD.md](../PRODUCT_PRD.md)
- Execution backlog: [../next-actions.md](../next-actions.md)

## Recently Completed Cards

- [#147](https://github.com/higgs-jung/tf-prd-lab/issues/147) — docs: /changelog에 '작성 가이드' 링크 추가 → merged via [PR #148](https://github.com/higgs-jung/tf-prd-lab/pull/148)
- [#145](https://github.com/higgs-jung/tf-prd-lab/issues/145) — feat: 오늘의 실험 섹션에서 /changelog로 연결 (closed)
- [#143](https://github.com/higgs-jung/tf-prd-lab/issues/143) — changelog 항목 작성 가이드 추가 → merged via [PR #144](https://github.com/higgs-jung/tf-prd-lab/pull/144)
- [#127](https://github.com/higgs-jung/tf-prd-lab/issues/127) — deterministic "today's experiment" section resolution → merged via [PR #128](https://github.com/higgs-jung/tf-prd-lab/pull/128)
- [#125](https://github.com/higgs-jung/tf-prd-lab/issues/125) — ideation INDEX + next-actions refresh after recent merges → merged via [PR #126](https://github.com/higgs-jung/tf-prd-lab/pull/126)
- [#123](https://github.com/higgs-jung/tf-prd-lab/issues/123) — docs reconcile (`docs/next-actions.md` + `docs/STATUS.md`) → merged via [PR #124](https://github.com/higgs-jung/tf-prd-lab/pull/124)

## Next 1–2 Actions (Pick One)

### 1) Fix ideation INDEX stale Next Actions (Small)
- Issue: [#153 docs: ideation INDEX Next Actions 정합성 복구 (stale 링크 제거)](https://github.com/higgs-jung/tf-prd-lab/issues/153)
- Why now: idle일 때 이 문서가 단일 엔트리포인트인데, CLOSED 카드가 섞이면 다음 실행 선택이 깨짐.
- Done: Next Actions에 CLOSED 이슈 링크 0 + Latest run 최신화

### 2) Keep pointers warm
- Why now: 작은 변경이 연속될 때 `docs/INDEX.md`/`docs/next-actions.md` 정합성 유지가 누적 비용을 줄임.
- Scope: 링크/상태 표기만 최소 수정
- Done: 문서 간 상태 불일치 0 유지

## Runs

- Active run template: [runs/TEMPLATE.md](./runs/TEMPLATE.md)
- Latest run: [runs/ideation-20260223-0507.md](./runs/ideation-20260223-0507.md)
- Archive index: [_archive/README.md](./_archive/README.md)
- Latest archived run: [_archive/ideation-20260214-0412.md](./_archive/ideation-20260214-0412.md)

## 운영 규칙 (간단)

- 새 아이디어는 먼저 run 문서로 기록 후, 검증되면 이슈/백로그로 승격
- 오래된 run은 삭제하지 말고 `docs/ideation/_archive/`로 이동
- 문서 탐색은 항상 `docs/INDEX.md`에서 시작 가능해야 함

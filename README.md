# Sample #3 — UI + Studio Team

| 차원 | 선택 |
|---|---|
| **UI** | ✅ 직접 개발 Flask |
| **Agent** | ✅ AAH Agent Team Studio 산출물 (multi-agent baked ARN) |

UI는 #2와 동일 구조. 차이는 Team Studio 에서 만든 **multi-agent workflow** 가 컨테이너
안에서 실행됨 — parallel_fork / aggregator / supervisor 등 패턴 그대로 동작.

## 배포 절차

1. AAH `/teams` 에서 Team 빌드 + 컨테이너 배포 → ARN 발급 대기 (READY)
2. `/develop/code-deploy` → 샘플 #3 카드 → Studio Team 드롭다운에서 선택 → 배포

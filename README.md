# ops-scheduler

15분마다 마케팅 운영실 Cloud 점검(감시기·대기열·재시도)을 호출하는 공개 스케줄러입니다.

- 비밀값 없음: GitHub Actions OIDC 토큰(audience `dazim-hilink-ops-tick`)을 서버가 검증하고, 이 저장소에서 온 요청만 받습니다.
- 공개 저장소의 표준 GitHub-hosted runner 사용은 무료입니다 (GitHub Actions billing 문서).
- 이 저장소에는 코드·데이터·토큰을 두지 않습니다. 워크플로 정본: dazim-hilink-integration `docs/development/scheduler/ops-tick.yml`.

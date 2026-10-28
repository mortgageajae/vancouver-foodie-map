# 밴쿠버 푸디맵 (Vancouver Foodie Map)

밴쿠버 한인을 위한 오늘의 패스트푸드 딜, 딜 캘린더, 내 주변 매장 찾기와 한인 맛집 협찬 딜.

- `index.html`: 사이트 전체 (빌드 과정 없음)
- `data/deals.json`: 딜 목록. 매일 아침 Claude가 웹을 확인해 갱신합니다.
- `data/sponsors.json`: 한인 협찬 업소 목록 (운영자가 직접 관리)
- `data/meta.json`: 마지막 업데이트 시각과 요약

Cloudflare Pages에 연결되어 `main` 브랜치에 푸시되면 자동으로 배포됩니다.

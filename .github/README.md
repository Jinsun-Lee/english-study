# 설명  
영어 학습 데이터와 자동화 설정이 들어있는 폴더입니다.

<br>

### 폴더 구조
- [`claude/`](claude/): Claude가 워크플로우를 수행할 때 참고하는 설정 파일
- [`answers/`](answers/): 사용자가 작성한 영어 답변 스크립트 (`yyyy_mm_dd_내용.md`)
- [`expressions/`](expressions/): 복습용 표현 정리 파일 (한국어 파일명, 날짜 없음)
- [`trends/`](trends/): 말하기 연습 주제로 참고하는 최근 경향 파일 (`yyyy_mm_dd.md`)
- [`level/`](level/): 사용자 영어 수준 분석 파일 (답변 피드백 시마다 갱신)
- [`config/`](config/): 데일리 질문 자동화가 참고하는 코치 설정 파일
- [`workflows/`](workflows/): 매일 영어 질문 이슈를 생성하는 GitHub Actions 워크플로우
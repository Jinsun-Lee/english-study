# 설명  
[OpenAI API 사용량](https://platform.openai.com/settings/organization/usage)을 확인하기 위한 링크입니다.
```
study-english/
 ├─ .github/
 │    ├─ workflows/                       # GitHub Actions 자동화가 들어있는 폴더
 │    │    ├─ daily-question.yml          # 매일 영어 질문을 Issue로 생성하는 워크플로우
 │    │    ├─ issue-date.yml.disable      # (비활성) Issue 제목 앞에 날짜를 붙이는 워크플로우
 │    │    └─ scripts/                    # 위 workflows에서 실행할 Python 스크립트 모음
 │    │         └─ generate_question.py   # (현재 미사용) OpenAI로 질문을 생성하는 스크립트
 │    │
 │    └─ config/                          # 데일리 질문 자동화용 코치 설정
 │         ├─ README.md                   # 이 파일
 │         └─ coach.md                    # 코치 페르소나 + 피드백 규칙 + 질문 생성 규칙 설정 파일
 │
 └─ README.md                             # 레포 전체 설명
```
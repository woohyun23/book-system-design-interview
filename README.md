# System Design Interview Study

시스템 설계 책을 읽으며 각 챕터의 핵심 내용과 실습 결과를 정리하는 저장소입니다.

## 학습 목표

- 시스템 설계의 핵심 개념을 자신의 언어로 설명한다.
- 요구사항 분석부터 상세 설계까지의 사고 과정을 기록한다.
- 설계 선택에 따른 장점, 단점, 트레이드오프를 비교한다.
- 학습 내용을 면접과 실제 프로젝트에 활용할 수 있도록 정리한다.

## 저장소 구조

```text
.
├── chapters/                # 챕터별 학습 기록
│   └── chapter-01/
│       ├── README.md        # 챕터 요약과 토론 내용
│       ├── practice/        # 챕터 관련 실습
│       │   └── README.md
│       └── images/          # 구성도와 참고 이미지
├── resources/               # 책 전체에서 공유하는 자료
│   ├── glossary.md
│   ├── references.md
│   └── useful-links.md
└── templates/               # 새 문서 작성용 템플릿
    ├── chapter-template.md
    └── practice-template.md
```

## 진도표

| Chapter | 주제 | 정리 | 실습 |
| --- | --- | --- | --- |
| [Chapter 01](chapters/chapter-01/README.md) | 작성 예정 | ⬜ | ⬜ |

상태는 `⬜ 시작 전`, `🟡 진행 중`, `✅ 완료`로 표시합니다.

## 작성 방법

1. `templates/chapter-template.md`를 복사해 챕터 폴더의 `README.md`를 작성합니다.
2. 실습이 있다면 `templates/practice-template.md`를 복사해 `practice/` 아래에 추가합니다.
3. 다이어그램과 이미지는 해당 챕터의 `images/`에 저장합니다.
4. 새로운 용어와 참고 자료는 `resources/` 문서에도 반영합니다.

## 작성 원칙

- 책의 문장을 그대로 옮기기보다 자신의 언어로 요약합니다.
- 설계의 결과뿐 아니라 선택한 이유와 포기한 대안도 기록합니다.
- 출처가 있는 내용은 링크와 확인 날짜를 함께 남깁니다.
- 파일과 폴더 이름은 소문자 kebab-case를 사용합니다.

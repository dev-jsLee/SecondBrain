# IT 지식 관리 시스템

## 구조
```
IT_brain/
├── MOC/
│   ├── Programming_Concepts_MOC.md
│   └── Languages_MOC.md
├── Inbox/
│   ├── Draft/           # 초안 작성
│   │   ├── 원문_초안/
│   │   └── 영구노트_초안/
│   └── WIP/            # 작성 중단된 문서
│       ├── 원문_진행중/
│       └── 영구노트_진행중/
├── 원문/
│   ├── 프로그래밍_개념/
│   │   ├── 변수/
│   │   └── 자료형/
│   └── 프로그래밍_언어/
└── 영구노트/
    ├── 프로그래밍_개념/
    └── 언어별_특징/
```

## Inbox 사용 방법
1. Draft/
   - 새로운 노트 작성 시작
   - 구조만 잡은 문서
   - 아이디어 메모
   ```yaml
   ---
   status: draft
   started: 2024-03-21
   type: permanent/literature
   ---
   ```

2. WIP/
   - 작성 중단된 문서
   - 진행 상태 표시
   - 다음 작업 메모
   ```yaml
   ---
   status: wip
   last_edited: 2024-03-21
   next_steps: 
   - "자료형 부분 보완 필요"
   - "예제 코드 추가"
   ---
   ```

## 작업 흐름
1. Inbox/Draft에서 시작
2. 작성 중단 시 WIP로 이동
3. 완성되면 원문 또는 영구노트로 이동

#Home #MOC
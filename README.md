# maedeup-paper

〈매듭: 신윤복을 엮다〉 넌버벌 대본 작성 방법론 소논문 작업 저장소 (비공개).
작업 규칙과 현재 상태는 [CLAUDE.md](CLAUDE.md)에 있다.

## 폴더

```
build/        논문 docx 빌드 소스(Node, docx 9.x)와 그림
drafts/       원고: 260720(심사 반영본), 261122(보충 초안 docx·pdf)
notes/        261122 보충계획, 7월 인수인계서, 3~4월 피드백 메모
sources/
  scripts/    2025 쇼케이스 대본, 사전 대본 7종(260319~260411) PDF + 텍스트
  gdocs/      260917 최종 기록 대본 본문, 260913 댓글 스레드
  production/ 공연 기사·공연정보·연출부 피드백 메모
  paintings/  원화 이미지 4점
references/   Muftić(2019) 박사논문
private/      로컬 전용(.gitignore). 카톡 원본 등 개인정보 자료를 둔다
```

## 빌드

```bash
cd build && npm install && node method_part2.js
```

## Google Docs 원본

| 문서 | 성격 | 저장소 |
|---|---|---|
| [260917_매듭: 신윤복을 엮다](https://docs.google.com/document/d/1HKFK6EZRuDbLWk5N7Ci8hLW5JB_3U7eKrcubmmayV9U/edit) | 최종 기록 대본 | `sources/gdocs/` 본문+열린 댓글 |
| ['260915' 영문판 반영본](https://docs.google.com/document/d/1LdrYiPriX5-Rsu5yZZGzTKOcltMNOGTTbx_wuHL45bg/edit) | 영문판 수정 반영, 9/16 프롤로그 순서 댓글 | 없음 |
| [260913_매듭: 신윤복을 엮다](https://docs.google.com/document/d/1kBaP6apb75fbU7ORJ6pI8GZ5XL5A6CLOPJJa2hLBwTw/edit) | 기록기 공유 문서, 교수님 댓글 | `sources/gdocs/` 댓글 스레드 |
| [[대본] 매듭: 신윤복을 엮다](https://docs.google.com/document/d/10ZzLWthBkIpLL383Vf-jBOAWqTSiF8SX1QdUgLmNUgI/edit) | 2025 쇼케이스 대본(작가), 댓글 9건 | `sources/scripts/` PDF·텍스트(댓글 제외) |
| [2025 연출 구성안](https://docs.google.com/document/d/1rrHD1flWp03cyrRTV6w8Zm1jBRpug6BT9VUAsjFPYsI/edit) | 교수님 구성안('치마폭…' 출처) | 없음 |
| [0825_월야밀회](https://docs.google.com/document/d/1-0Nuk4RDDBoq79cN2LGi4fGi62Cjpy7zhlF1KBlCOGA/edit) | 2025 월야밀회 두 해석 | 없음 |
| [0826_월하정인](https://docs.google.com/document/d/1a0syAJmvZ5R3b1NFbzxdCZMuwhWoDpf9NmGO8j7wWeY/edit) | 2025 월하정인 초안 | 없음 |
| [9/2 회의록](https://docs.google.com/document/d/1ai5sw_8omJYVafT-3Eq5O-Mzwh3GwQtCjpG6UCe72OA/edit) | 2026-09-02 연출 회의 기록 | 없음 |

사전 대본 '260319'와 '260411'의 Google Docs 원본은 이미지가 많아 커넥터로 댓글을 읽지 못했다. 필요하면 이미지를 뺀 사본을 만들어 댓글을 확인한다.

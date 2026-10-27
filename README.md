# 수학 방탈출 — 출발 저장소

## 시작
1. github.com/i20091119-ai/2026.aiescape → Use this template → 이름 `escape-내이름`
2. claude.ai/code → 저장소 선택 → "CLAUDE.md 읽고 이 앱 구조 설명해 줘"
3. `js/my-questions.js`에 내 단원 문제 5개
4. "계획부터 보여 줘" → 허락 → 수정 → 확인
5. PR → Merge → Settings → Pages → main / (root) → Save
6. 주소: `https://아이디.github.io/escape-내이름/` → NFC 피규어에 기록

## 파일
| 파일 | 역할 |
|---|---|
| index.html | 화면 · 자물쇠 · 타이머 · QR |
| js/my-questions.js | ★ 내 문제 5개 |
| js/qrcode.js | QR 생성 (qrcode-generator, MIT) |

## 문제 하나 더 넣으려면
`questions` 배열에 `{ q, a, hint }`를 추가하면 자물쇠가 하나 늘어납니다.

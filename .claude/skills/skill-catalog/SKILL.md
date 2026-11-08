---
name: skill-catalog
description: 평소엔 이름만 보이는 스킬들의 용도표. 디자인·UI·애니메이션·Figma·기획·테스트·디버깅·코드 리뷰 작업을 시작할 때 먼저 읽고 맞는 스킬 1~2개를 고른다.
---

# 필요 시 스킬 목록 (hunter-guild)

이 저장소는 토큰을 아끼려고 대부분의 스킬을 **이름만 보이게**(`.claude/settings.json`의 `skillOverrides: name-only`) 두었다.
작업이 아래에 해당할 때만 그 스킬을 Skill 도구로 불러 쓴다. 불러지지 않으면 `.claude/skills/<이름>/SKILL.md`를 직접 읽고 따른다.

- 한 작업에 1~2개만 고른다. 같은 칸에 여러 개가 있으면 이 프로젝트 전용 스킬(프로젝트 이름이 들어간 것, CLAUDE.md가 지목한 것)을 먼저 쓴다.
- CLAUDE.md의 규칙이 스킬 내용보다 우선한다.

## 세션 공통·기획
- `grill-me` — 계획·설계를 질문으로 끝까지 검증
- `brainstorming` — 새 기능 아이디어를 설계로 다듬기
- `writing-plans` — 여러 단계 작업의 구현 계획 작성
- `executing-plans` — 작성된 계획을 직접 실행
- `subagent-driven-development` — 계획을 서브에이전트로 나눠 실행
- `dispatching-parallel-agents` — 독립 작업 2개 이상 병렬 처리

## 디버깅·테스트·검증
- `systematic-debugging` — 버그를 재현→원인→최소 수정 순서로
- `test-driven-development` — 테스트 먼저 쓰고 구현
- `verification-before-completion` — 완료 보고 전 실제 검증
- `break-ui` — 극단 데이터로 UI 깨뜨려 보기

## 코드 리뷰·브랜치 마무리
- `requesting-code-review` — 리뷰어 에이전트에 리뷰 요청
- `receiving-code-review` — 받은 리뷰를 검증하며 반영
- `using-git-worktrees` — 격리된 작업 공간 만들기
- `finishing-a-development-branch` — 작업 브랜치 병합·PR 마무리

## 화면 디자인·다듬기
- `impeccable` — 화면 설계·감사·다듬기·애니메이션 (하위 명령)
- `mobile-native` — 웹앱을 폰에서 앱처럼 (100vh·탭 하이라이트 등)

## UI 원칙(필요한 항목만)
- `feedback-patterns` — 저장·완료 피드백
- `micro-interaction-spec` — 작은 상호작용 명세
- `fitts-law` — 버튼 크기·위치(터치)
- `critique-visual-hierarchy` — 기존 화면 시선 흐름 비평
- `critique-information-density` — 기존 화면 정보 밀도 비평

## 애니메이션·모션
- `animate` — 애니메이션을 처음부터 설계·구현
- `review-animations` — 모션 코드 리뷰
- `animation-performance` — 애니메이션 끊김·프레임 문제

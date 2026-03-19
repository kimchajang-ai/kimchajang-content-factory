# 김차장의 머니해킹 콘텐츠 공장

이 레포는 김차장 유튜브 채널의 콘텐츠 생산 자동화를 위한 Skills Pack 입니다.

## 핵심 목적
- 트렌드 주제 조사
- 팩트 체크
- 김차장 스타일 대본 작성
- TTS 오디오 패키지 생성
- 비주얼 스토리보드 생성
- 썸네일 / 업로드 패키지 자동 생성
- QA 검수

## 하드 룰
- TTS Voice: `Sadaltager`
- Image Model: `gemini-3-flash-preview`
- Visual Reference: `김차장 캐릭터 레퍼런스 이미지 시트 (references/kimchajang_character_reference.md)`
- White background
- Korean localization
- Full body character
- Default runtime: 4 minutes
- Default storyboard: 48 scenes
- Default summary pack: 5 shots

## 주요 디렉토리
- `skills/`: 에이전트별 스킬 정의
- `templates/`: 출력 템플릿
- `manifests/`: 레지스트리 및 파이프라인 설정
- `references/`: 캐릭터/보이스/스타일 기준
- `examples/`: 실제 예시 산출물

## 권장 실행 순서
1. skills/00_global_hard_rules.md
2. skills/00_global_persona_kimchajang.md
3. skills/01_topic_research_agent.md
4. skills/02_factcheck_agent.md
5. skills/03_scriptwriting_agent.md
6. skills/04_audio_package_agent.md
7. skills/05_visual_storyboard_agent.md
8. skills/06_summary_visual_agent.md
9. skills/07_thumbnail_package_agent.md
10. skills/08_upload_package_agent.md
11. skills/09_quality_assurance_agent.md

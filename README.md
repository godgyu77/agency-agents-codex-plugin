# Agency Agents Codex Plugin

agency-agents 저장소를 Codex용 로컬 플러그인으로 변환한 결과물입니다.

## 구성

- 변환된 스킬: 163개
- 각 스킬은 `skills/<slug>/SKILL.md`에 저장됨
- 각 스킬은 `agents/openai.yaml`을 포함해 Codex UI 목록 노출을 보강함
- `.codex-plugin/plugin.json`으로 로컬 플러그인으로 등록 가능

## 사용

- 원하는 스킬 이름으로 호출합니다.
- 예: `engineering-backend-architect 스킬로 백엔드 구조 설계해줘`
- 예: `marketing-seo-specialist 관점으로 SEO 점검해줘`

## 참고

- 원본 파일 경로는 각 `SKILL.md` 본문에 보존되어 있습니다.
- 변환 목록은 `converted-summary.json`에서 확인할 수 있습니다.
- 제외된 문서는 `failed-conversions.json`에서 확인할 수 있습니다.

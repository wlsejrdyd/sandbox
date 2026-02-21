# Sandbox Monorepo

## 개요

아이디어를 실험하고 개발하는 모노레포.
괜찮은 앱은 운영 레포로 분리 예정.

## 구조

```
sandbox/
  apps/           # 개별 앱 (앱마다 독립된 폴더)
  shared/         # 앱 간 공유 코드 (유틸, 설정 등)
  .github/
    workflows/    # GitHub Actions CI/CD (앱별 path filter)
```

## 규칙

- 새 앱은 `apps/<app-name>/` 하위에 생성
- 앱마다 자체 README.md, 빌드/실행 방법 포함
- 언어/프레임워크 제한 없음
- CI/CD: GitHub Actions + path filter 방식 (변경된 앱만 빌드)

## 앱 목록

(아직 없음 - 앱 추가 시 여기에 기록)

| 앱 이름 | 설명 | 기술 스택 | 상태 |
|---------|------|----------|------|

## 다음 할 일

- [ ] CI/CD 파이프라인 구성 논의
- [ ] 첫 번째 앱 아이디어 구체화

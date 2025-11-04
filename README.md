# ✨ Flutter CI/CD with GitHub Actions

이 저장소는 Flutter 프로젝트의 CI/CD(지속적 통합 및 배포)를 GitHub Actions로 자동화하는 예제입니다.  
테스트, 빌드, 코드 포맷, 린트 검사, APK 생성 등 다양한 과정을 자동화하여 개발 효율성과 코드 품질을 향상시킵니다.

---

## 📁 구성 요소

| 항목 | 설명 |
|------|------|
| `.github/workflows/ci.yaml` | GitHub Actions Workflow 파일입니다. |
| `flutter analyze` | 코드 정적 분석을 수행합니다. |
| `flutter test` | 단위 테스트를 실행합니다. |
| `flutter build apk` | Android용 APK를 빌드합니다. |

---

## 🛠 사용 방법

1. 이 저장소의 `.github/workflows/ci.yaml` 파일을 복사하여 원하는 Flutter 프로젝트에 추가합니다.
2. GitHub에 코드를 Push하거나 PR을 생성하면 자동으로 워크플로가 실행됩니다.
3. 실행 결과는 GitHub의 Actions 탭에서 확인하거나, 빌드된 APK를 다운로드할 수 있습니다.

---

## ✅ 트리거 조건

- **Push**: `main` 브랜치에 push될 때 실행됩니다.
- **Pull Request**: 모든 PR 생성 및 업데이트 시 실행됩니다.

---

## 📝 사전 조건

- 프로젝트 루트에 `pubspec.yaml` 파일이 있어야 합니다.
- Android 빌드를 위해 프로젝트가 적절히 구성되어 있어야 합니다.
- Flutter SDK는 GitHub Actions에서 자동으로 설치됩니다.

---

## 🙋‍♂️ 만든 사람

- GitHub: [@iloveuhyeon](https://github.com/iloveuhyeon)

---


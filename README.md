# 재활용 체쿠

분리배출 안내를 제공하는 Android 앱 프로젝트입니다.

## Android APK 만들기
1. GitHub 저장소의 **Actions** 탭을 엽니다.
2. **Build Android APK** 워크플로를 선택합니다.
3. **Run workflow**를 실행합니다.
4. 완료된 실행의 **Artifacts**에서 `recycle-check-debug-apk`를 내려받아 ZIP을 풀고 APK를 설치합니다.

main 브랜치에 push해도 자동으로 APK 빌드가 실행됩니다.

## 현재 기능
- 사진 촬영 또는 앨범에서 이미지 선택
- 품목을 직접 선택해 분리배출 안내 확인
- 내장 Q&A 및 분리배출 기본 상식

사진 자동 AI 판별이나 실시간 지자체 조회는 포함되어 있지 않습니다. 안내는 일반적인 학습용 정보이며 지역별 기준을 확인해야 합니다.

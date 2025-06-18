# Custom SwiftUI Craft 🚀

SwiftUI로 자주 사용하는 UI 패턴과 컴포넌트를 미리 만들어둔 뷰 컬렉션입니다.  
이 저장소는 다음 목적을 가지고 있습니다:

- 매번 새로 만들기 귀찮은 그리드, 시트, 오버레이 등 템플릿 뷰 저장
- 스타일(폰트, 색상, 패딩, 코너 등)을 변수로 통일하여 일관성 유지
- 실제 프로젝트에서 빠르게 복붙하여 사용할 수 있도록 구성
- SwiftUI 연습 및 포트폴리오용 UI 데모 정리

---

## 📱 구성 예시

| 화면 | 설명 |
|------|------|
| HomeView | 뷰 목록을 `List` 형태로 나열, 각 뷰 데모로 이동 |
| GridViewExample | LazyVGrid 레이아웃 |
| CustomSheetView | `.sheet` 활용 커스텀 시트 |
| CustomPopupOverlay | ZStack + overlay 활용 |

---

## 🎨 스타일 가이드

모든 뷰는 다음 공통 스타일 파일을 통해 스타일을 설정합니다:

- `UIConstants.swift`  
- `UIFont+Custom.swift`  
- `UIColor+Custom.swift`

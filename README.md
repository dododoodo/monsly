# 📅 Monsly

Flutter로 제작한 **일정 관리 어플리케이션 'Monsly'**  
사용자는 날짜별로 일정을 등록하고, 수정 및 삭제할 수 있으며, 로컬 DB를 통해 데이터를 저장합니다.

## ✨ 주요 기능

1. **TableCalendar 기반 캘린더 UI**
   - 한국어(`locale: ko_KR`)를 지원합니다.
   - 원하는 날짜 선택 후 해당 날짜의 일정을 확인 가능합니다.

2. **일정 삭제 및 수정 기능**
   - 원하는 날짜의 일정을 수정 또는 삭제할 수 있습니다.

3. **Hive를 이용한 로컬 데이터 저장**
   - Hive를 활용하여 키값을 기반으로 일정 데이터를 저장합니다.
   - 앱 종료 후에도 사용자의 데이터가 유지됩니다.

4. **GetX를 활용한 상태관리**
   - 선택 날짜 및 일정 리스트를 실시간으로 반영시킵니다.
   - 반응형 UI를 구성합니다.

## 🛠 사용 기술

- Flutter 3.x
- Dart
- GetX
- Hive (hive_flutter)
- table_calendar

## 🚀 배포

🔗 [👉 Monsly 배포 주소](https://monsly.vercel.app/)  
본 프로젝트는 Vercel을 통해 배포되었습니다.

## 🖼️ 스크린샷

| 메인 캘린더 | 일정 추가 | 일정 확인 |
|-------------|------------|------------|
| ![calendar](screenshots/calendar.png) | ![add](screenshots/add.png) | ![view](screenshots/view.png) |


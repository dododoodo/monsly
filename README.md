![thumbnail](https://github.com/user-attachments/assets/eb0be028-41c4-4e79-bf9b-cec0cdcb7fde)

# 📅 Monsly

Flutter로 제작한 **일정 관리 어플리케이션 'Monsly'**  
사용자는 날짜별로 일정을 등록하고, 수정 및 삭제할 수 있으며, 로컬 DB를 통해 사용자의 일정 데이터를 저장합니다.

## 🖊️ 주요 기능

1. **TableCalendar 기반 캘린더 UI**
   - 한국어(`locale: ko_KR`)를 지원합니다.
   - 원하는 날짜 선택 후 해당 날짜의 일정을 추가할 수 있습니다.

2. **일정 삭제 및 수정 기능**
   - 원하는 날짜의 일정을 수정 또는 삭제할 수 있습니다.

3. **Hive를 이용한 로컬 데이터 저장**
   - Hive(원격 저장소)를 활용하여 키값을 기반으로 일정 데이터를 저장합니다.
   - 앱 종료 후에도 사용자의 데이터가 유지됩니다.

4. **GetX를 활용한 상태관리**
   - 선택 날짜 및 일정 리스트를 실시간으로 반영시킵니다.
   - 반응형 UI를 구성합니다.

## 🛠 사용 기술

- Flutter GUI 프레임워크
- GetX : flutter 상태관리
- Hive (hive_flutter) : 로컬 데이터베이스
- Github : 자료 보관 및 기록
- Vercel : 자동 배포

## 🚀 배포

🔗 [Monsly 배포 주소](https://monsly.vercel.app/)  
본 프로젝트는 Vercel을 통해 배포되었습니다.

## 🖼️ 스크린샷

![thumbnail2](https://github.com/user-attachments/assets/1a52d13a-4a85-4db6-964b-175ada835a35)

| 메인 캘린더 | 일정 추가 | 일정 확인(홈) |
|-------------|------------|------------|
| ![calendar_page_1](https://github.com/user-attachments/assets/2346819e-3507-48f6-b933-a3f0c9e2b871) | ![calendar_page_2](https://github.com/user-attachments/assets/a5202a9d-ca6e-4aa8-b95d-6221683db5c7) | ![Main_page](https://github.com/user-attachments/assets/804001d0-41f4-4501-8f11-4f319371af12) |





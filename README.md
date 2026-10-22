<img width="355" height="749" alt="image" src="https://github.com/user-attachments/assets/00a697ef-e154-49ea-8af6-ea9d426b022e" />
<img width="353" height="749" alt="image" src="https://github.com/user-attachments/assets/df45778c-f26f-48eb-827a-fe97472c2c5e" />
<img width="361" height="754" alt="image" src="https://github.com/user-attachments/assets/c948f741-d91a-40c8-b401-339147a6a419" />

# Advanced_iOS (day1)

## 학습 내용

1. overlay 패턴: 프로필 카드 이미지
2. ZStack + LinearGradient: 프로필 카드 그라데이션, 마이페이지 커버
3. clipShape: 둥근 모서리, 원형 이미지
4. @State / @Binding: 블러 토글, 신청 화면 전환
5. enum + CaseIterable: MeetDay, Area
6. ForEach / LazyVGrid: 요일/지역 선택 버튼 반복 생성
7. .toolbar + TabView: 앱 레이아웃 (상단바 + 하단 탭)
8. .tint(): 앱 전체 테마 색상
9. .alert: 사진 공개 확인 대화상자
10. .blur + .animation: 블러 효과 + 애니메이션
11. .custom() 폰트: 커스텀 글자체 적용
12. 함수로 뷰 추출: selectButton, infoRow
13. 앱 아이콘 / Display Name: 프로젝트 설정에서 변경


## Advancements

1. ProfileCard에 User 모델 적용: 하드코딩된 텍스트를 User 구조체로 바꾼다.
2. 로그아웃에 알림 추가: 로그아웃 버튼에 .alert를 적용해서, "정말 로그아웃 하시겠습니까?" 출력
3. 마이페이지 커버를 이미지로: LinearGradient 대신 실제 이미지를 커버로 넣어본다. 프로필 카드에서 배운 overlay 패턴을 활용하면 된다.
4. 마이페이지에 추가 정보: 매너 점수, 가입일, 매칭 횟수 등을 infoRow로 추가한다.

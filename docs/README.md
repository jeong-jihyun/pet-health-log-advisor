# PRJ-0032 반려동물 건강 기록·상담 앱 — 모바일 산출물

## 제공 파일
- PRJ-0001_UI-설계서_v1.0.docx
- PRJ-0001_기능정의서_v1.0.docx
- PRJ-0001_API-설계서_v1.0.docx
- PRJ-0001_디자인-시스템_v1.0.docx
- 모바일 인터랙티브 프로토타입 디자인 시안용.html
- 모바일_화면_미리보기.png

## 모바일 메뉴
홈 / 기록 / 상담 / 리포트 / 마이. 하단 탭 이동과 기록 입력 폼을 제공한다.

## 기존 엔진 연결 기준
- petlog.store.add_pet → 반려동물 등록
- petlog.store.add_entry → 건강 기록
- petlog.advice.advise / urgent_signs / repeated / weight_trend → 상담·주의 신호
- petlog.report.vet_summary → 병원 제출용 요약

## 구현 범위 주의
저장소의 현재 엔진은 Python CLI + JSON 파일 기반이다. REST 서버·인증·클라우드 DB·사진 업로드는 확인되지 않았다. API 설계서는 모바일 전환을 위한 계약 제안이며, HTML은 브라우저 내 컨셉 시안이다. 실제 진단·처방·약물 용량 안내를 하지 않는다. 응급 기준과 수치 기준은 출시 전 수의사 검토가 필요하다.

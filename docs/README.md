# PRJ-0032 반려동물 건강 기록·상담 앱 — 모바일 산출물

## 저장소에 반영된 파일
- `모바일 인터랙티브 프로토타입 디자인 시안용.html`: 브라우저 실행형 모바일 컨셉
- `README.md`: 산출물 안내 및 기존 엔진 연결 관계

## 별도 전달 패키지
대화창에서 제공한 `PawNote_Mobile_Project_Deliverables.zip`에 다음 파일을 포함한다.
- `PRJ-0001_UI-설계서_v1.0.docx`
- `PRJ-0001_기능정의서_v1.0.docx`
- `PRJ-0001_API-설계서_v1.0.docx`
- `PRJ-0001_디자인-시스템_v1.0.docx`
- `모바일 인터랙티브 프로토타입 디자인 시안용.html`
- `모바일_화면_미리보기.png`

## 기존 엔진 연결 기준
- `petlog.store.add_pet` → 반려동물 등록
- `petlog.store.add_entry` → 건강 기록
- `petlog.advice.advise / urgent_signs / repeated / weight_trend` → 상담·주의 신호
- `petlog.report.vet_summary` → 병원 제출용 요약

## 구현 범위와 안전 고지
현재 저장소의 기존 엔진은 Python CLI + JSON 파일 기반이다. REST 서버·인증·클라우드 DB·사진 업로드는 확인되지 않았다. API 설계서는 모바일 전환을 위한 계약 제안이며, HTML은 브라우저 내 컨셉 시안이다. 실제 진단·처방·약물 용량 안내를 하지 않는다. 응급 키워드와 수치 기준은 출시 전 수의사 검토가 필요하다.

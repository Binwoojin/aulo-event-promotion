# Aulo Event Promotion

Aulo의 **이벤트 프로모션** 페이지를 만들고 보관하는 저장소입니다.
이벤트마다 페이지 소스와 결과물(배포용 파일, 배너·이미지 내보내기)을 한곳에 남깁니다.

- 디자인 컨셉(색·서체·사진 틀·모션 톤)만 [aulo-reservation-app](https://github.com/Binwoojin/aulo-reservation-app)의 브랜드 랜딩·웹앱에서 참고합니다.
- 예약·주문 앱의 코드·화면 규칙·정책은 이 저장소에 가져오지 않습니다. 이벤트 조건은 이벤트마다 따로 정합니다.

## 구성

- `shared/tokens.css` — Aulo 디자인 컨셉 토큰(색·서체·간격·모서리·모션). 이벤트 페이지가 공통으로 불러 씁니다.
- `events/` — 이벤트별 폴더. 목록은 [events/README.md](./events/README.md).

```
events/
  2026-11-sample-event/
    README.md   이벤트 개요(기간·목적·대상·상태·조건 출처)
    src/        페이지 소스(HTML·CSS·JS, 원본 이미지·디자인 파일)
    dist/       결과물(배포한 페이지, 배너·SNS 이미지 내보내기)
```

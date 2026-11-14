# 백제갈비 (BAEKJE GALBI) 홈페이지

하노이 미딩 백제갈비 가맹점 랜딩페이지. 정적 HTML 한 장 (`index.html`) + `assets/images`.

- 데이터: BestClub 중앙 Firebase(`jumper-b15aa`)에서 가맹점 BT 정책(`merchants`), 쿠폰(`coupon_campaigns`), 판매상품(`merchant_products`)을 실시간 조회. 데이터가 없으면 해당 블록은 숨김.
- 가맹점 ID 기본값 `baekje_galbi` — BestClub에 정식 등록되면 `index.html`의 `MERCHANT_ID` 기본값을 실제 ID로 교체. (`?merchant=ID` 로 임시 지정 가능)
- 다국어: KO / VI
- 원본 사진: `../asset/images`
- 로컬 미리보기: `python -m http.server 8080` 후 http://localhost:8080
- 배포: Netlify (publish = 이 폴더)

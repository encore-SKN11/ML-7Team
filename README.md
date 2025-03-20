# EDA-8Team

## 👋🏻 8 Team 팀원소개
| 김정원 | 김한솔 | 백미송 |
| --- | --- | --- |
| <img src="image/jw.jpg" height="200"> | <img src="image/hs.png" height="200">  | <img src="image/ms.png" height="200">  |
---
### **🔍 주요 내용**
- 데이터 로드 및 전처리
- 변수별 분석 및 시각화
- 머신러닝을 위한 데이터 변환 
---
### 💡인사이트
- 건물 크기가 방 개수, 욕실 개수에 큰 영향을 받는 점을 보아, 멜버른의 집값은 건물 크기에 가장 큰 영향을 받음
- 그 외로는 주택 유형과 건물 연식과 상관관계를 볼 수 있음
---

### 🗂️데이터셋 소개
  - **Melbourne Housing Snapshot**
  - 출처: Kaggle (https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot/data)

#### **변수에 대한 설명**
  - Rooms: 방 개수
  - Price: 가격 (달러)
  - Method: 판매 방식
    - S: 매물 판매됨
    - SP: 사전 판매됨
    - PI: 경매에서 유찰됨
    - PN: 사전 판매되었으나 가격 미공개
    - SN: 판매되었으나 가격 미공개
    - NB: 입찰 없음
    - VB: 판매자가 제시한 입찰가
    - W: 경매 전에 철회됨
    - SA: 경매 후 판매됨
    - SS: 경매 후 판매되었으나 가격 미공개
    - N/A: 가격 또는 최고 입찰가 정보 없음
  - Type: 주택 유형
    - br: 침실 개수
    - h: 단독주택, 코티지, 빌라, 반단독주택, 테라스하우스
    - u: 유닛, 듀플렉스(다세대주택)
    - t: 타운하우스
    - dev site: 개발 가능 부지
    - o res: 기타 주거용 부동산
  - SellerG: 부동산 중개업자
  - Date: 판매 날짜
  - Distance: 도심 (CBD)까지의 거리
  - Regionname: 지역명 (서부, 북서부, 북부, 북동부 등)
  - Propertycount: 해당 지역에 존재하는 부동산 수
  - Bedroom2: 다른 출처에서 수집한 침실 개수
  - Bathroom: 욕실 개수
  - Car: 주차 가능 차량 수
  - Landsize: 토지 크기
  - BuildingArea: 건물 크기
  - CouncilArea: 해당 지역의 관할 지방정부
---
### EDA
1. 데이터 로드

   <img src="image/readcsv.png"> <br>
    
2. 데이터 구조 및 기초통계 확인

   <img src="image/info.png" height="400">
   <img src="image/describe.png"><br>

3. 결측치 및 이상치 탐색

   <img src="image/isna.png" height="400"><br>
   <img src="image/outlier_iqr.png"><br>
   <img src="image/outlier_iqr_print.png" height="400"><br>

4. 데이터 시각화를 통한 탐색

   <img src="image/heatmap_not_processed.png" height="400"><br>
   <img src="image/price_to_rooms.png" height="400"><br>
   <img src="image/price_to_car.png" height="400"><br>

5. 데이터 정제 및 전처리

   <img src="image/dropna.png"><br><br>
   <img src="image/ord_enc.png">
   <img src="image/type_enc.png">
   <img src="image/df_v.png" height = "400"><br><br>
   <img src="image/heatmap.png" height="400">

6. Appendix

    <img src="image/folium.png" height="500">
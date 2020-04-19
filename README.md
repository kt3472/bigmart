## BigMart Sales Prediction

**1. Object**
  - 빅마트 의 상품아이템별 판매수량 예측 


**2. Data & Exploration**
  - 빅마트 10개 체인점의 1559개 상품아이템 판매 데이터(train and test_data)
  - 상품의 무게(Item_Weight), 상품의 가격(Item_MRP), 체인점의 규모(Outlet_Size) 등 총 12개 컬럼
  - Numeric형 5개, object형 7개 컬럼으로 구성(test data는 판매실적인 Item_Outlet_Sales 컬럼 제외)


**3. Preprocessing & Feature Eng.**
  - Outlet_Size, Item_weight의 Null값 처리(기존 data set 에서 검색 및 색인) 
  - 0의 값을 가지고 있는 Item_Visibility를 해당 상품의 평균값으로 변환
  - Item_Fat_Content컬럼의 동일한 의미의 Object값을 병합(3개 -> 2개)  
  - Outlet_Size, Outlet_location 등 6개 Object형 컬럼을 dummy 변수로 생성


**4. Model tuning**


**5. Ensemble**


**6. Results**


**7. Reference**
  - https://www.kaggle.com/brijbhushannanda1979/bigmart-sales-data 


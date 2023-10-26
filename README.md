# Korean_currency_detection_model

For visually impaired individuals, Korean Won currency classification
- KT AIVLE School AI Developer Track Mini Project

- Data Source : selectstar (https://open.selectstar.ai/ko/?page_id=5844)
     - 화폐데이터 image
     - 10원/50원/100원/500원/1000원/5000원/10000원/50000원
       
- Yolov5모델 이용
- 결과

  ![image](https://github.com/2hy03/Korean_currency_detection_model/assets/101242683/c4936a14-a6ad-4c69-8300-d60249c96107)
  ![image](https://github.com/2hy03/Korean_currency_detection_model/assets/101242683/9d184d87-aac0-440f-bb4d-8137e25978b1)
  ![image](https://github.com/2hy03/Korean_currency_detection_model/assets/101242683/3e2b183c-49c0-4925-a733-eb8571cc34a8)
- 단독 이미지 분류는 잘 이루어지고 있음 확인
  
  ![image](https://github.com/2hy03/Korean_currency_detection_model/assets/101242683/aad6db56-acab-4fa4-9212-99b2322b68b3)
- 겹쳐있는 경우 인식이 잘 되지 않음, 추가 학습 필요
    
  ![image](https://github.com/2hy03/Korean_currency_detection_model/assets/101242683/32d420d7-c2e7-4006-9132-a6347e474653)
- 과거 10원의 경우 인식이 잘 이루어지지 않음

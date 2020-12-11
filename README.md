# mask_detection
machine learning based mask_detection 

실시간 이미지 인식 기반 마스크 인식 프로그램 코드

COVID-19의 예방책으로 가장 각광받고 있는 마스크 착용의 실천을 도모하기 위하여 마스크 착용자를 식별하기 위한 인공지능 이미지 인식 서비스.


데이터 셋은 위 개요의 참고 데이터 셋을 Kaggle에서 다운로드하여 사용하였습니다. 
해당 데이터 셋은 Train 및 Validation의 비율을 8:2로 나누었습니다. 
데이터는 With Mask, Without Mask로 나누었으며 각각 5000장씩 이미지를 사용하였습니다.

사용된 데이터 셋은 아래에 있습니다.


구성도
================
![그림2](https://user-images.githubusercontent.com/5088870/101862726-4acd7e80-3bb6-11eb-9fb7-edde007a7740.png)



추가적으로 인식을 돕기 위하여 haarcascade_frontalface_default.xml을 이용하여 얼굴을 좀 더 쉽게 인식 할 수 있도록 하였습니다.


Screenshot
=================
![그림1](https://user-images.githubusercontent.com/5088870/101862720-44d79d80-3bb6-11eb-9440-e2c344b5c0d1.jpg)



Data Sets
================
https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset

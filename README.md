# 닮은꼴 강아지 테스트 웹

[페이지 URL]

## 1. 사진 크롤링

- google_images_download 라이브러리 이용

## 2. Machine Learning

- 구글의 'Teachable Machine' 이용

## 3. 웹 사이트 구현

- HTML/Javascript 이용

# 닮은꼴 강아지 테스트 :books:

[닮은꼴 강아지 테스트]: https://dogsbreedrecognition.netlify.app/ "닮은꼴 강아지 테스트"

## **1. 프로젝트 소개**

> **인공지능으로 나와 닮은 견종을 알아보자! '닮은꼴 강아지 테스트 서비스'**

👉 사진을 넣으면 인공지능이 분석해 닮은꼴 강아지를 알려주며 가장 닮은 강아지와 상위 4가지 닮은 종을 알려준다.

**🚀 기술 스택**
|구분|설명|
|:---:|:---:|
|Front|HTML, javascript, CSS|
|MachineLearning|TeachableMachine|
|Crawling|Python(google-image-download)|

## **2. 프로젝트 목표**

- 이미지 크롤링 후 머신러닝 결과를 이용해 나와 닮은꼴 강아지를 예측한다.

## **3. 기능**

`메인`

- 이미지를 업로드 한다.
- 이미지 업로드 후 바로 머신러닝이 시작된다.

`분석 결과`

- 가장 높은 확률로 닮은 강아지를 메인에 표기
- 상위 4가지 견종을 'pie-chart'를 이용해 표기

`다른 사진으로 재시도`

- 재시도 버튼 클릭시 modal 팝업창 뜸
- '다른 사진으로 재시도' 클릭시 메인 화면으로 이동

➕ 유저가 주로 모바일로 테스트 한다는 점을 고려해 반응형 UI 구현

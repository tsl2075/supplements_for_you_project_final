
## 자연어처리와 의미학습을 이용한 영양제 추천 시스템
## <img width="40" height="40" alt="image" src="https://github.com/user-attachments/assets/a6c80d75-530a-4c18-ac7a-4c60b184e5a6" /> 프로젝트 개요
영양제 구매 시 제품 이름이나 성분에 대한 정보 부족으로 선택이 어려운 문제를 해결하고자, 사용자 증상에 기반한 자연어처리 추천 시스템을 구축한다. 
제품 리뷰 데이터를 학습하여 증상과 유사한 의미를 가진 영양제를 추천한다.


## 개발 개요
- 프로젝트 : 영양제 추천
- 개발기간 : 2025.05.25 ~ 05.30
- 개발 언어 : Python


## <img width="40" height="40" alt="Image" src="https://github.com/user-attachments/assets/b37ebdf0-b93d-4a64-8740-0d5b58d975f7" /> 목표
-  영양제 리뷰 데이터를 자연어처리 기법으로 분석하고, 의미학습을 통해 사용자 증상에 따라 적절한 제품을 추천하는 시스템을 구축하는 것을 목표


## 주요 기술
- OpenCV
- YOLO
- PyQT5


<img width="300" height="265" alt="image" src="https://github.com/user-attachments/assets/0a91f4d1-362b-4466-8474-d7dffd05d08e" />


## 세부설명
- 자동데이터 수집 : IHerb 사이트에서 건강보조식품 정보 및 리뷰 크롤링
- 사용자 증상 입력 시 유사한 리뷰를 가진 제품 추천
- TF-IDF 코사인 유사도 기반 맞춤형 제품 추천


## 데이터셋 정보
- 수집 대상 : iHerb사이트
- 카테고리 : 11개(종합비타민, 비타민A~E, 아연, 셀레늄 등)
- 수집 규모 : 48개 제품 x 최대 50개 페이지 리뷰
- 데이터 형태 : 제품명, 영양성분, 고객 리뷰, URL


## 사용 기법
### 자연어 처리
- KoNLPy(Okt) : 한국어 형태소 분석
- 정규표현식 : 비타민 표기 정규화(vitamin c -> 비타민C)
- 불용어 탐지 : IDF값 기반 불용어 추출

### 머신러닝
- TF-IDF 벡터화 : 문서-단어 중요도 행렬 생성
- Word2Vec(Skip-gram) : 단어 의미 임베딩 학습
- 코사인 유사도 : 제품간 유사성 계산


## Youtube 링크
https://www.youtube.com/watch?v=kCo9AleT280

### &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;키워드 입력영상   &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  
![Image](https://github.com/user-attachments/assets/d0584b7f-cc92-4164-a9b2-ce0f248487ad)

### &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;동작영상   &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
![Image](https://github.com/user-attachments/assets/a16e092f-4a9a-42aa-81a2-3026143a83ef)





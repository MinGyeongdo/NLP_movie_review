# NLP_movie_review
## 목표
> 영화에서 평점은 소비자들이 영화를 선택하는 중요한 지표 중 하나입니다. 그러나 리뷰는 사람이 작성하는 것이기 때문에 일관적이지 않고 매우 주관적인 기준으로 매겨집니다.<br> 
예를 들면, 어떤 사람은 '이 영화 나쁘지 않은데?'의 기준이 7점일 수도 있고, 어떤 사람은 5점일 수도 있습니다.<br>
이러한 점을 고려하여, 리뷰텍스트를 분석하여 긍정적인지 부정적인지 분류하면 좀 더 영화에 대한 객관적인 지표를 얻을 수 있다는 생각해서 진행한 프로젝트입니다.
## 프로젝트 개요
> <img width="586" alt="NLP 프로젝트 진행 순서" src="https://user-images.githubusercontent.com/106360843/213373179-78f92165-16ba-4a37-afec-0a222eea94e8.png">

##  데이터 개요
###  수집한 데이터
> <img width="516" alt="NLP 데이터개요(1)" src="https://user-images.githubusercontent.com/106360843/213374316-ed542617-f340-4fc7-9682-d904879e6960.png">
###  학습에 사용될 데이터
> <img width="416" alt="NLP 데이터개요(2)" src="https://user-images.githubusercontent.com/106360843/213374617-42fbdb11-91b0-42d8-abf7-e992d9c50b86.png">
### 데이터 워드 클라우드
> <img width="535" alt="NLP 데이터개요(3)" src="https://user-images.githubusercontent.com/106360843/213374742-58401786-36c8-4cab-b0f4-f62a2a492405.png">
## 모델 학습
> <img width="472" alt="NLP 데이터개요(4)" src="https://user-images.githubusercontent.com/106360843/213374942-9e0381e9-19fe-4ac3-8775-74a0b667af6d.png">
### 모델 학습 결과 화면
> <img width="347" alt="NLP 모델 학습 결과" src="https://user-images.githubusercontent.com/106360843/213375101-c522056f-c274-4621-9daa-36de60538a9e.png">
###  수집데이터 분류 결과
> <img width="511" alt="NLP 모델 분류 결과" src="https://user-images.githubusercontent.com/106360843/213375223-c312b745-5ea2-4b80-b709-bcb277bc8747.png">
## 결과 정리 및 개선점
> - 대부분의 데이터가 모델의 성능을 끌어올리려면 전처리 과정에 많은 시간이 소요된다고 합니다. 성능개선에 대한 데이터 정규화나, 빈번하게 사용되지만 긍정/분류에는 관계없는 불용어들을 추가하여 여러 시도를 추가적으로 해볼 예정입니다.
> - 감정 분류한 결과를 활용하여 추가적인 인사이트를 도출할 예정입니다. 이전에 영화 총 매출을 예측하는 프로젝트를 진행했었는데, 리뷰 데이터 수집후 감정분류를 통하여 모델의 성능개선을 꾀해 볼 예정이고 감정 분류 결과를 통해 긍정 / 부정에 따른 가중치를 부여하여 좀 더 객관적인 평점 시스템을 구축해볼 수 있을 것입니다.

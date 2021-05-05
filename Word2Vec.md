# Word2Vec을 이용한 문서 유사도 분석



## 1. ```get_wiki_corpus.ipynb```
### 위키백과로부터 53만건의 훈련 데이터를 얻는 과정
### 이 데이터를 활용해 모델을 추가훈련시켜 성능을 향상시킨다.



## 2. ```word2vec_cos_sim.ipynb```
### word2vec을 이용해 문서 유사도를 분석한다.
### 유사도 값은 '코사인 유사도'를 사용한다.



## 3. ```visualization.ipynb```
### 유사도 분석 결과를 히트맵으로 시각화한다.



## * 참고 자료 링크
### ```https://wikidocs.net/50739``` 
> ```word2vec_cos_sim.ipynb``` 에서 모델 훈련 과정 부분을 참고함

### ```https://gogomovy.tistory.com/5?category=1180011```
> ```word2vec_cos_sim.ipynb``` 에서 임베딩 ~ 유사도 분석 과정을 참고함

### ```https://paul-hyun.github.io/vocab-with-sentencepiece/```
> ```get_wiki_corpus.ipynb``` 에서 위키 익스트랙터를 사용하는 부분을 참고함

### ``` https://www.infoking.site/16``` 
> ```word2vec_cos_sim.ipynb``` 에서 모델 추가학습 부분을 참고함

### ```https://ratsgo.github.io/embedding/downloaddata.html```
> ```word2vec_cos_sim.ipynb``` 에서 첫번째 학습 데이터로 사용함
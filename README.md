
 WORD to Vector Data with Movie comment
 =========================================
 
 > Lecture Chinese culture Data portfolio by baro kim
### CoronaVirus Data Analysis

> this project is made for research on People's recognitive difference 
> on Contasion and flu Movie .

> this is made by joonto  
> 201402412 이승준 


#### 본 연구내용은 아래에 기술되어 있습니다.

Usage
------------------------------------------

  if you want to research with this project 
  click Fork or Clone and edit in your repo.
  
## 1. Open DataScraper.ipynb

<img src="/imgs/datapic1.PNG"  >

####  you can edit movieid to what you want to change. you can find movie id in naver movie website url.

<img src="/imgs/datapic2.PNG"  >

#### you can change csv file name. if you use metrix, you can change metrix.csv



## 2. Open Word2VecSystem.ipynb

<img src="/imgs/datapic3.PNG"  >

#### you can change what you want to recognize. if you want to use metrix.csv, you just put 'metrix.csv' in the string part.

<img src="/imgs/datapic4.PNG"  >

#### you can get the one word similarity

<img src="/imgs/datapic5.PNG"  >

#### you can test the positive and the negative 


## 3. See the result in x, y Vectors


 contagion comment
 ------------------
 
<img src="/imgs/contagion_data_image.jpg"  width="500" height="250">


 flu comment
 ------------
<img src="/imgs/flu_data_image.jpg"  width="500" height="250">


------------------------------------------------------------

본 연구내용
---------

### 연구 의도

2020년도 코로나 바이러스로 인한 사람들의 행태변화에 영향을 미친 인식의 변화가 있을 것으로 예상

### 연구 목적

코로나 사태 이후 전염병에 대한 사람들의 인식변화 확인

### 연구 설계 

전염병과 관련된 영화의 댓글을 수집하고 
Word to Vector 기법을 
이용하여 유사성을 분석하여 유의미한 인식변화 도출

### 연구 방법


한국영화 감기와 영화 컨테이전을 상정하여, 
네이버 영화 댓글을 수집

감기의 경우 13,000개의 댓글 수집
컨테이전의 경우 3,800개의 댓글 수집

각각 2019년 이전 댓글과 2020년 이후 댓글 분리

Word to Vector 적용하여,
2019년 과 2020년 데이터 분석 후 결과 도출

### 연구결과


#### 2019년

#### 3D 

<img src="/imgs/2019_3d_contagion.jpg"  width="500" height="250">
<img src="/imgs/2019_3d_flu.jpg"  width="500" height="250">

감기, 위험을 검색했을 때, 
영화 관련 내용이 많음

설국열차, 테러, 
라이브, 숨바꼭질 등

혹은 감정표현 단어
(의미해석 어려움)

#### 2D 

<img src="/imgs/2019_2d_contagion.jpg"  width="500" height="250">
<img src="/imgs/2019_2d_flu.jpg"  width="500" height="250">

2D 데이터는 무작위적인 양태로 보임

<img src="/imgs/2019_word_result.jpg"  width="1000" height="250">

전염병, 위험 / 중국 => 바이러스 
질병 이 높은 수치로 나옴

전염병 - 중국 – 바이러스 간의 연관성이 떨어진다고 해석 가능
---

#### 2020년

#### 3D

<img src="/imgs/2020_3d_contagion.jpg"  width="500" height="250">
<img src="/imgs/2020_3d_flu.jpg"  width="500" height="250">

중국 검색시 
실화, 박쥐, 혼란, 발생, 감기 연관단어로 존재
 
감기 검색시
중국, 폐렴 연관단어로 존재

<img src="/imgs/2020_word_result.jpg"  width="1000" height="250">

전염병, 위험 / 연출(영화 중심 댓글) 

=> 전세계, 나라, 국가, 중국인, 경험, 민폐, 패닉 등이 99% 이상의 연관성을 보임

전염병과 위험에 대한 단어 인식에 현실경험 & 감정 이 반영되었으며
중국과 높은 연관성을 보이기 시작함.
----


### 단어를 통한 변화검출

<img src="/imgs/word_fear.jpg"  width="1000" height="500">

### 왼쪽 사진은 "감기" 영화 단어에서 공포를 검색한 2019, 2020 데이터 ( 위아래 차례대로 )
### 오른쪽 사진은 "컨테이젼" 영화 단어에서 공포를 검색한 2019, 2020 데이터 ( 위아래 차례대로 )

“공포”  감기 영화에 대한 인식
2019 이전 과 2020 이후-> 대략 확률 10% 이상 차이

2019 : 전염병에 대한 단어 에볼라 가 유일, 나머지는 영화관련 혹은 관련성 X
2020 : 전염병에 대한 단어 다수 , 질병, 위생, 서울, 고증, 박쥐, 최근, 이기심
-----
“공포” 컨테이젼 영화에 대한 인식 
감기 와 컨테이젼이 다른 양상을 보임. 

2019 : 전염병에 대한 현실적인 인식 단어 O , 확률 매우 높음 , but 구체적 X , 확산, 심리, 인류, 재앙, 전세계
2020 : 전염병에 대한 구체적인 인식 , 코로나 바이러스, 짱깨 


#### 결과 해석

영화 감기는 컨테이젼에 비해 코로나 이전에는 상업영화로 인식하는 경향이 강했음을 유추할 수 있다. 
영화 컨테이젼은 연관단어의 검색확률이 감기에 비해 높은 것으로 보아, 감기보다 전염병에 대한 단어가 많이 등장하였고 2020년에 구체화되었다.


<img src="/imgs/word_movie.jpg"  width="1000" height="500">

“영화”  감기 영화에 대한 인식
2019 이전 과 2020 이후-> 대략 확률 10% 이상 차이 + 대상에 대한 부정적 인식 생성 및 강화

2019 : 전염병에 대한 단어 X , 나머지는 영화관련 , 줄거리, 스크린, 인내심, 영화로
2020 : 전염병에 대한 단어 다수 , 때문, 사태, 지금, 코로나 우한, 바이러스, 중국, 쓰레기. -> 탓
-----

“영화” 컨테이젼 영화에 대한 인식 
2019 이전 과 2020 이후 -> 영화관련에서 대상특정 및 부정적 인식 

2019 : 재난영화, 만점, 최악, 그냥, 작품
2020 : 때문, 소름, 우한, 폐렴, 코로나, 실감, 예언.     -> 탓


#### 결과 해석

2020년 이후 전염병과 관련된 부정적 인식이 생성되었고, 강화되는 모습을 보인다.
두 영화 모두 공통적으로 때문이라는 단어가 등장하는데, 부정적 감정과 더불어 ‘탓’을 하는 감정이 생성된 것을 알 수 있다.


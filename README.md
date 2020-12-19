
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

전염병과 관련된 영화의 댓글을 수집하고 Word to Vector 기법을 
이용하여 유사성을 분석하여 유의미한 인식변화 도출

### 연구 방법


한국영화 감기와 영화 컨테이전을 상정하여, 네이버 영화 댓글을 수집
감기의 경우 13,000개의 댓글 수집, 컨테이전의 경우 3,800개의 댓글 수집.

각각 2019년 이전 댓글과 2020년 이후 댓글 분리

Word to Vector 적용하여,
2019년 과 2020년 데이터 분석 후 결과 도출


# OpenDataWrangling
* 공공데이터 분석
* 다음의 버전을 사용했습니다.
* !pip install plotnine==0.5.0
* !pip install --upgrade pandas==0.23.4
* !pip install folium==0.5.0
* :tv: [전체영상 보기](https://goo.gl/TJeiTi)



## [스타벅스, 이디야 분석](store_location_by_folium.ipynb)

* 이디야는 스타벅스 근처에 입점한다는 설이 있었습니다. 과연 이디야와 스타벅스의 매장입지는 얼마나 차이가 날까요? 관련 기사를 읽고 구별로 이디야와 스타벅스의 매장을 기사와 유사하게 분석하고 시각화 해보면서 Python, Pandas, ggplot(plotnine), Numpy, Folium에 익숙해져 봅니다.
* 인용기사 : [[비즈&빅데이터]스타벅스 '쏠림' vs 이디야 '분산'](http://news.bizwatch.co.kr/article/consumer/2018/01/19/0015)
* 공공데이터 포털에서 제공하고 있는 소상공인시장진흥공단 상가업소정보 데이터를 분석합니다. 대분류와 중분류 데이터를 Pandas, ggplot, folium으로 분석합니다.
* 데이터 출처 : [https://www.data.go.kr/dataset/15012005/fileData.do](https://www.data.go.kr/dataset/15012005/fileData.do)

### 튜토리얼 비디오

:tv: [[1/7] Python, Pandas, folium으로 스타벅스, 이디야 매장 위치 분석하기](https://youtu.be/PR1WeCdFWvg)

:tv: [[2/7] Pandas의 groupby를 활용해 구별 스타벅스, 이디야 매장수 비교](https://youtu.be/P3Hr_fvN980)

:tv: [[3/7] GeoJSON을 활용하여 folium의 choropleth를 통해 행정구역별로 스타벅스, 이디야 매장 합계를 표현하기](https://youtu.be/3ktnySDNTzw)

:tv: [[4/7] 서울 구별 스타벅스 매장 분포와 밀집도를 GeoJSON을 활용하여 folium의 choropleth 와 CircleMarker 로 표현하기](https://youtu.be/WzIoHvdolas)

:tv: [[5/7] 서울 구별 이디야 매장 분포와 밀집도를 GeoJSON을 활용하여 folium의 choropleth 와 CircleMarker 로 표현하기](https://youtu.be/CyCrWekgQrs)

:tv: [[6/7] Pandas의 reshaping data 활용하여 스타벅스, 이디야 매장수 비교하기, 구별 위도/경도 평균 구하기](https://youtu.be/YKESreqAwlc)

:tv: [[7/7] Pandas의 pivot_table로 구한 데이터를 Folium의 CircleMaker로 매장수 크기를 반영해 그리기](https://youtu.be/IwxbRP3mlTU)



## [프랜차이즈 분석](store_location_by_folium.ipynb)
* 배스킨라빈스와 던킨도너츠 매장위치 분석
* 뚜레쥬르와 파리바게뜨 매장위치 분석
* 데이터 출처 : [https://www.data.go.kr/dataset/15012005/fileData.do](https://www.data.go.kr/dataset/15012005/fileData.do)

### 튜토리얼 비디오

:tv: [[1/4] 파이썬 Pandas pd.read_csv로 파일 불러오기, shape로 요약보기, str.contains 로 특정 상호가져오기](https://youtu.be/sV4tbUUHp7Y)

:tv: [[2/4] 파이썬 Pandas 의 value_counts, unique, columns, describe 를 사용하고 gglplot 문법으로 시각화 하여 업종 분석하기](https://youtu.be/_2TdRCx8Z0k)

:tv: [[3/4] 배스킨라빈스와 던킨도너츠 위치분석 - Pandas의 str.contains 로 상호명을 전처리하고 folium.Map과 Marker를 활용하기](https://youtu.be/9MWrff5Hr2w)

:tv: [[4/4] 뚜레쥬르, 파리바게뜨 매장 위치분석 - Python, Pandas, ggplot(plotnine), folium 사용하기](https://youtu.be/Ffesny9Dajc)



## [상가(상권)정보](commercial_store.ipynb)
* 공공데이터 포털에서 제공하고 있는 소상공인시장진흥공단 상가업소정보 데이터를 분석합니다. 
* 대분류와 중분류 데이터를 Pandas, ggplot, folium으로 분석합니다.

### [google colaboratory로 실행하기](https://goo.gl/uVK672)
* [google colaboratory](https://goo.gl/uVK672) 에서 내 드라이브에 저장을 하시게 되면 실행권한이 생깁니다. 

* 소상공인 상권정보 상가업소 데이터
* 데이터 출처 : [https://www.data.go.kr/dataset/15012005/fileData.do](https://www.data.go.kr/dataset/15012005/fileData.do)
* 사용 데이터 
    * 상권별 업종밀집통계 2016
    * 서울특별시 자치구별_상권분석 정보 2017
    * 상가업소정보(2017년 9월) 

### 튜토리얼 비디오

:tv: [[1/3] 상가(상권)정보로 위경도 정보 활용하기, 판다스로 데이터 로드하기 미리보기](https://youtu.be/jAQp0CpNvKc) 

:tv: [[2/3] 상가(상권)정보로 위경도 정보 활용하기, 판다스로 결측치 분석하기, ggplot 문법으로 시각화하기](https://youtu.be/XF1_4RCRsGA) 

:tv: [[3/3] 상가(상권)정보로 위경도 정보 활용하기, 판다스로 결측치 분석하기, ggplot 문법으로 시각화하기, 대분류, 중분류별](https://youtu.be/xo5UQA38q3M) 

    
    
## [전국 신규 민간 아파트 분양가격 동향](apt_presale_price.ipynb)
* 주택분양보증을 받아 분양한 전체 민간 신규아파트 분양가격 동향
* 2013년부터 2018년까지 부동산 가격 변동 추세가 아파트 분양가에도 반영될까요? 공공데이터 포털에 있는 데이터를 Pandas 의 melt, concat, pivot, transpose 과 같은 reshape 기능을 활용해 분석해 봅니다. 그리고  groupby, pivot_table, info, describe, value_counts 등을 통한 데이터 요약과 분석을 해봅니다.
* 데이터 출처 : [https://www.data.go.kr/dataset/3035522/fileData.do](https://www.data.go.kr/dataset/3035522/fileData.do)
* 사용 데이터 
    * 전국 평균 분양가격(2018.4월) 

### 튜토리얼 비디오

:tv: [[1/6] 신규 민간 아파트 분양가격 데이터셋 소개](https://youtu.be/H6-Y-sipgCk)

:tv: [[2/6] Pandas로 데이터 불러오고 요약하기](https://youtu.be/ddSR4xAjAww)

:tv: [[3/6] Pandas 의 groupby, pivot_table 사용하기](https://youtu.be/NdXmOgTYscU)

:tv: [[4/6] 파이썬에서 ggplot 문법을 사용해 시각화 하기](https://youtu.be/KtVUrw3B8KQ)

:tv: [[5/6] 2015년 이전 아파트 분양가 데이터 전처리하기](https://youtu.be/arxUpioX_d8)

:tv: [[6/6] Pandas의 concat으로 데이터 합치고 boxplot 그리기](https://youtu.be/C0Iyp5QUtxE)
    


## [전국 도시공원 표준 데이터](park.ipynb)
* 전국에는 많은 도시공원이 있습니다. 우리 동네에는 어떤 공원이 있을까요? 지역별로 어떤 공원이 어디에 분포되어 있는지 Folium을 통해 시각화 해봅니다.
* 전국 도시공원 정보(공원유형, 보유시설 등)
* 공공데이터 개방 표준데이터 속성정보(표현형식/단위 등)는 행정자치부에서 고시한 [공공데이터 개방 표준(제2015-51호)]를 참고해야함
* 데이터 출처 : [https://www.data.go.kr/dataset/15012890/standard.do](https://www.data.go.kr/dataset/15012890/standard.do)
* 사용 데이터
    * 전국도시공원표준데이터
    
### 튜토리얼 비디오

:tv: [[1/5] 전국 도시 공원 표준 데이터 불러오기, 요약하기](https://youtu.be/uJ6QO6jLBWA)

:tv: [[2/5] 주소 및 사용하지 않는 컬럼 결측치 처리](https://youtu.be/qbfCXbWMYXY)

:tv: [[3/5] ggplot(plotnine)시각화 지역별, 공원구분별 시각화](https://youtu.be/-SHIBg5DD1c)

:tv: [[4/5] 경기도 도시공원 Folium 으로 보기](https://youtu.be/FzYmL7nWSpc)

:tv: [[5/5] 서울, 제주 도시공원 결측치, 이상치, 오류값 분석, Folium 으로 시각화](https://youtu.be/ijYneK1xkE0)



## [서울시 자전거 따릉이 대여 분석](seoul-bike)
* 년/월/일/요일/시간 별 대여현황 분석
* 대여소 위치 크롤링으로 수집
* 대여소 위치 Folium으로 시각화 하기
* 데이터 출처 : 
	* 대여 정보 : http://data.seoul.go.kr/dataList/datasetView.do?infId=OA-15182&srvType=F&serviceKind=1&currentPageNo=1
	* 대여소 정보 : https://www.bikeseoul.com/app/station/moveStationSearchView.do?currentPageNo=



## [서울시 업무추진비 부서별 집행 현황 분석](seoul-jmt)
* 업무추진비 데이터 병합 및 전처리 
* 업무추진비 사용처 워드클라우드로 그리기 
* 데이터 출처 : 
	* [ 서울시 업무추진비 | 부서별 집행 현황 | 서울시 정보소통광장(정보공개)](http://opengov.seoul.go.kr/expense)
	* github : https://github.com/seoul-opengov/opengov 


## PyCon KR 2018 튜토리얼 노트북
* https://goo.gl/x8kasp

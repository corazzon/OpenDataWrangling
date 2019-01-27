# OpenDataWrangling
공공데이터 분석


## [상가(상권)정보](commercial_store.ipynb)
* 소상공인 상권정보 상가업소 데이터
* 데이터 출처 : https://www.data.go.kr/dataset/15012005/fileData.do
* 사용 데이터 
    * 상권별 업종밀집통계 2016
    * 서울특별시 자치구별_상권분석 정보 2017
    * 상가업소정보(2017년 9월) 

## [전국 신규 민간 아파트 분양가격 동향](apt_presale_price.ipynb)
* 주택분양보증을 받아 분양한 전체 민간 신규아파트 분양가격 동향
* 데이터 출처 : https://www.data.go.kr/dataset/3035522/fileData.do
* 사용 데이터 
    * 전국 평균 분양가격(2018.4월) 
    
## [전국 도시공원 표준 데이터](park.ipynb)
* 전국 도시공원 정보(공원유형, 보유시설 등)
* 공공데이터 개방 표준데이터 속성정보(표현형식/단위 등)는 행정자치부에서 고시한 [공공데이터 개방 표준(제2015-51호)]를 참고해야함
* 데이터 출처 : https://www.data.go.kr/dataset/15012890/standard.do
* 사용 데이터
    * 전국도시공원표준데이터
    
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

#### PyCon KR 2018 튜토리얼 노트북
* https://goo.gl/x8kasp

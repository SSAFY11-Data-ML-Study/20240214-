# 20240214_Subway_Data
Data Link: https://www.kaggle.com/datasets/kimjmin/seoul-metro-usage   

### - Goals: 데이터 입출력 및 전처리 연습
### - Data Name: 서울 지하철 승하차 인원
### - Data Preview    
archive    
 ┣ seoul-metro-2015.logs.csv   
 ┣ seoul-metro-2016.logs.csv   
 ┣ seoul-metro-2017.logs.csv   
 ┣ seoul-metro-2018.logs.csv   
 ┣ seoul-metro-2019.logs.csv   
 ┣ seoul-metro-2020.logs.csv   
 ┣ seoul-metro-2021.logs.csv   
 ┗ seoul-metro-station-info.csv   

#### station-info의 키 값
station.code : 역 번호  
station.fr_code: 역 번호 (foreign)  
line.num: 호선 번호  
line.name: 호선 이름  
line.name_sub: 호선 이름  
line.station_seq: 호선별 번호  
station.name_full: 역 이름(전체)  
station.name: 역 이름  
station.name_chc: 역 이름(한자)  
station.name_chn: 역 이름(중국어)  
station.name_en: 역 이름(영어)  
station.name_jp: 역 이름(일본어)  
geo.latitude: 위도  
geo.longitude: 경도  
geo.sigungu_code: 역이 속해있는 구 번호  
geo.sigungu_name: 역이 속해있는 구 이름  
geo.address_road: 도로명 주소  
geo.address_land: 지명 주소  
geo.phone: 역 전화번호  

#### df_logs의 키 값  
timestamp: 시간  
station_code: 역 번호(df_station_info와 연결)  
people_in: 들어온 사람 수  
people_out: 나간 사람 수 

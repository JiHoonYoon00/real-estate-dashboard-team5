##  real-estate-dashboard

### 프로젝트 소개
- 서울시 재개발 부지 예상되는 지역 선정

### 팀원 소개
1. [hyelin606](https://github.com/hyelin606)
2. [jianteow](https://github.com/jianteow)
3. [JiHoonYoon00](https://github.com/JiHoonYoon00)
4. [SSUMINIs](https://github.com/SSUMINIs)

### 데이터셋 출처
- 서울시 공공데이터

### 데이터 설명

### 구조
```
├── .devcontainer # 개발 환경 컨테이너 설정
├── .venv # 가상 환경 설정
├── data # 데이터 분석에 사용되는 데이터셋 폴더
│ ├── 단독다가구.csv # 건물유형(HOUSE_TYPE)이 '단독다가구'인 데이터
│ ├── 아파트.csv # 건물유형(HOUSE_TYPE)이 '아파트'인 데이터
│ ├── 연립다세대.csv # 건물유형(HOUSE_TYPE)이 '연립다세대'인 데이터
│ ├── 오피스텔.csv # 건물유형(HOUSE_TYPE)이 '오피스텔'인 데이터
│ ├── Seoul_data.csv # 서울시 부동산 전체 데이터
│ ├── seoul_sig_cd.geojson # 서울시 구역별 지도 데이터
│ └── seoul.geojson # 서울시 지리 데이터
├── images # 시각화에 사용되는 이미지 폴더
│ ├── 노후 건물 개수 상위 10개 지역.png
│ ├── 노후 건물 거래량 상위 10개 지역.png
│ └── 재개발 선정 지역.png
├── pages # 스트림릿 페이지 파일
│ ├── 1_👋_Hi There.py # 인사말 페이지
│ ├── 2_1️⃣_노후 건물 분포도.py # 노후 건물 분포도 페이지
│ ├── 3_2️⃣_노후 건물 거래 동향.py # 노후 건물 거래 동향 페이지
│ ├── 4_3️⃣_노후 건물 평당 가격.py # 노후 건물 평당 가격 페이지
│ └── 5_4️⃣_관련 정보 가져오기.py # 재개발 부지로 선정된 지역의 관련 정보를 가져오는 페이지
├── app.py # 스트림릿 앱 실행 파일
├── crawling.py # 크롤링 함수가 정의된 파일
├── requirements.txt # 필요한 파이썬 패키지 목록
├── .gitignore # Git에서 추적하지 않을 파일 목록
└── README.md # 프로젝트 설명 파일
```

### 기술 스택
- **Streamlit** : 배포 및 대시보드 개발
- **Naver NewsAPI** : 네이버 뉴스 정보 크롤링
- **QGIS** : 지리정보 활용 (v3.34.3)

### 라이브러리 소개
requirement.txt
- **pandas** : 
- **streamlit** : 
- **geopandas** : 
- **pydeck** : 
- **numpy** : 
- **dotenv** :


### 다이어그램
아래는 서비스 아키텍처를 보여주는 다이어그램입니다.

![real-estate-dashboard 아키텍처](./.png)

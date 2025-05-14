# Part4_Data_Engineering
### 00_docker_database : MYSQL, POSTGRESQL 도커 컨테이너 생성 docker compose 파일
### 01_python_database : 파이썬으로 데이터베이스 다루기
### 02_data_pipeline : 데이터 파이프라인 개발 모듈
### 03_gcp_python : Google Cloud 리소스들을 Python으로 다루기

#### 📁 프로젝트 구조
```
04_Data_Engineering/
│
├── 00_docker_database/
│       └── docker-compose.yaml # DB 컨테이너 생성
│
├── 01_python_database/
│       ├── dataset/
│       ├── python_db_notebook.ipynb
│       └── requirements.txt
│
├── 02_data_pipeline/
│       ├── dataset/
│       ├── db/
│       │     └── connector.py
│       │
│       ├── pipeline/
│       │     ├── extract.py
│       │     ├── transform.py
│       │     └── load.py
│       │
│       ├── controller.py
│       ├── settings.py
│       └── data_pipeline.ipynb
│
└── 03_gcp_python/
        ├── dataset/
        ├── gcp_bigquery.ipynb
        └── gcp_storage.ipynb
```

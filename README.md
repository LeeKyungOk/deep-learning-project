
# Deep Learning Project (English)

## Overview
This repository is part of my AI portfolio and demonstrates my ability to apply deep learning techniques to solve real-world problems.

## Features
1. Financial news sentiment analysis using NLP models.
2. Stock price prediction using LSTM and CNN.
3. Deployment of trained models using FastAPI.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/LeeKyungOk/deep-learning-project.git
   cd deep-learning-project
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## How to Run the Code
1. Train the models:
   ```
   jupyter notebook notebooks/model_training.ipynb
   ```
2. Start the FastAPI server:
   ```
   uvicorn src.main:app --reload --host 0.0.0.0 --port 8000
   ```

## Folder Structure
```
deep-learning-project/
├── data/                # Data files (e.g., CSV, Excel)
├── notebooks/           # Jupyter Notebook files for model training and evaluation
├── src/                 # Backend API code for model deployment (FastAPI)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Future Improvements
1. Incorporate more advanced NLP models like BERT or GPT.
2. Automate hyperparameter tuning using Optuna or GridSearchCV.
3. Expand the project to include additional real-world datasets.

## Contact 
For more information, please contact me at [    @gamil.com]  

---

# 딥러닝 프로젝트 (한국어)

## 개요
이 저장소는 AI 포트폴리오의 일부로, 딥러닝 기법을 활용하여 실제 문제를 해결하는 능력을 보여줍니다.

## 주요 기능
1. NLP 모델을 사용한 금융 뉴스 감성 분석.
2. LSTM 및 CNN을 활용한 주식 가격 예측.
3. FastAPI를 사용하여 학습된 모델 배포.

## 설치 방법
1. 저장소 클론:
   ```
   git clone https://github.com/LeeKyungOk/deep-learning-project.git
   cd deep-learning-project
   ```
2. 의존성 설치:
   ```
   pip install -r requirements.txt
   ```

## 코드 실행 방법
1. 모델 학습:
   ```
   jupyter notebook notebooks/model_training.ipynb
   ```
2. FastAPI 서버 시작:
   ```
   uvicorn src.main:app --reload --host 0.0.0.0 --port 8000
   ```

## 폴더 구조
```
deep-learning-project/
├── data/                # 데이터 파일 (예: CSV, Excel)
├── notebooks/           # 모델 학습 및 평가를 위한 Jupyter Notebook 파일들
├── src/                 # 모델 배포를 위한 백엔드 API 코드 (FastAPI)
├── requirements.txt     # Python 의존성 목록
└── README.md            # 프로젝트 설명 파일
```

## 향후 개선 사항
1. BERT 또는 GPT와 같은 고급 NLP 모델 추가.
2. Optuna 또는 GridSearchCV를 사용한 하이퍼파라미터 튜닝 자동화.
3. 추가적인 실제 데이터셋을 포함하여 프로젝트 확장.

## 문의하기
추가 정보가 필요하다면 [    @gamil.com]으로 연락주세요.


# Flask Hello World

Bootstrap 5를 사용한 최소 Flask 웹앱입니다.

## 실행 방법

```bash
# 1. 가상환경 생성 및 활성화
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # macOS / Linux

# 2. 패키지 설치
pip install -r requirements.txt

# 3. 환경 변수 설정
copy .env.example .env       # Windows
# cp .env.example .env       # macOS / Linux
# .env 파일을 열어 SECRET_KEY 값을 변경하세요

# 4. 앱 실행
python app.py
```

브라우저에서 http://localhost:5000 을 열면 됩니다.

## 폴더 구조

```
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── templates/
    └── index.html
```

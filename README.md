# amadda_back

📌 백엔드 구성
- FastAPI: API 서버
- Firebase: 인증 및 데이터베이스 (Firestore)

👥 팀원
- A (Firebase / 인증)
- B (FastAPI / 서버)

📂 디렉토리 구조
- `/firebase` : Firebase 연결 및 인증 처리
- `/api` : FastAPI 라우터
- `/models` : Pydantic 모델

🚀 실행 방법

```bash
# 가상환경 설정
python -m venv venv
source venv/bin/activate

# 의존성 설치
pip install -r requirements.txt

# 서버 실행
uvicorn api.main:app --reload


---

## 6️⃣ requirements.txt 생성

```bash
pip freeze > requirements.txt


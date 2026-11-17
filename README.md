## 안녕하세요, 박창준입니다 👋

AI 엔지니어를 준비하고 있습니다. 코드잇 AI 엔지니어 부트캠프 11기에서 머신러닝, 컴퓨터 비전, 자연어 처리·LLM, 모델 배포·서빙을 공부했습니다.

모델을 학습하는 데서 끝내지 않고, 서비스로 내보내고 결과를 테스트와 숫자로 확인하는 데까지 해 보고 있습니다.

### 프로젝트

| 프로젝트 | 내용 | 결과 |
|---|---|---|
| 💊 **[PillDetect](https://github.com/cjkj1234/beginner-project-pill)**<br/><sub>팀 4명 · 후처리·실험 담당</sub> | 알약 사진에서 최대 4개 알약의 종류(56종)와 위치를 찾는 객체 탐지. YOLOv8·YOLO11 3단계 미세조정, EMA, WBF 앙상블 | Kaggle mAP **0.956** (9개 모델 앙상블)<br/>프로젝트 후 후처리 버그 3건을 찾아 테스트와 함께 수정 |
| 🚀 **[PillDetect Serving](https://github.com/cjkj1234/pill-detect-serving)**<br/><sub>개인</sub> | 위 모델을 ONNX로 변환해 FastAPI로 서빙하고 Streamlit으로 보여주는 프로젝트. Docker Compose로 실행 | PyTorch 없이 NumPy로 옮긴 NMS를 Ultralytics와 비교 검증<br/>API 이미지 1.66GB → **726MB** |
| 👕 **[FITROOM](https://github.com/cjkj1234/fitroom)**<br/><sub>개인</sub> | 의류 소상공인을 위한 3D 피팅룸과 AI 광고 스튜디오. 실측으로 만든 옷을 천 시뮬레이션으로 아바타에 입히고, gpt-5-mini로 광고 문구 생성 | XPBD 천 시뮬레이션을 라이브러리 없이 구현<br/>프롬프트 6개 판 실제 모델 평가 · 테스트 **148개** |

### 기술

| 분야 | 사용해 본 기술 |
|---|---|
| AI · ML | PyTorch, Ultralytics YOLO, ONNX Runtime, OpenAI API (Structured Outputs), MediaPipe, Weights & Biases |
| 서빙 · 인프라 | FastAPI, Streamlit, Docker, GitHub Actions, Cloudflare Workers |
| 웹 · 3D | TypeScript, React, Three.js |
| 도구 | Python, uv, pytest, Git |

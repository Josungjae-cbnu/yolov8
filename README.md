# YOLOv8 기반 커스텀 다중 객체 탐지 및 이동 경로 추적
- **작성자:** 충북대학교 소프트웨어학부 2023078001 조성재
- **탐지 클래스:** `lighter`, `pen`, `eraser`
- **학습 환경:** Google Colab (T4 GPU), Ultralytics YOLOv8n (`epochs=50`, `imgsz=512`)

## 업로드 파일 설명
- `best.pt`: 50 에포크 학습이 완료된 커스텀 YOLOv8 모델 가중치
- `tracked_result_final.mp4`: 5초 테스트 영상 내 객체 탐지 및 이동 궤적(Trajectory) 시각화 결과 영상
- `Untitled0.ipynb`: 데이터셋 로드, 모델 학습 및 OpenCV 경로 추적 전체 코드
- `results.png` / `confusion_matrix.png`: 모델 학습 손실 곡선 및 검증 혼동 행렬

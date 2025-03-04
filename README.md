# 🚗 차량 파손 검사 프로젝트 (Vehicle Damage Inspection)

## 📖 개요
이 프로젝트는 **딥러닝 기반 차량 파손 감지 모델**을 개발하는 연구입니다.
자동차 외관 이미지를 분석하여 사고로 인한 손상을 탐지하고, 이를 자동으로 분류하는 AI 모델을 구축합니다.

> **🎯 연구 및 산업 적용 가능성:**
> - 차량 보험 심사 및 보상 자동화
> - 스마트 교통 시스템 및 자율주행 차량의 사고 감지
> - 중고차 평가 및 차량 유지보수 자동화
> - 대학원 연구 및 논문 작성에 활용 가능

## 🛠 사용된 라이브러리 및 기술
- `OpenCV` : 영상 전처리 및 특징 추출
- `TensorFlow` / `PyTorch` : 딥러닝 모델 학습 및 평가
- `NumPy`, `Pandas` : 데이터 처리 및 분석
- `Matplotlib`, `Seaborn` : 데이터 시각화

## 🔬 사용된 모델 및 접근 방식
### 1️⃣ **CNN 기반 파손 탐지**
- 합성곱 신경망(CNN)을 활용하여 차량의 손상 여부를 판별
- 데이터 증강(Augmentation) 기법 적용하여 모델 성능 향상

### 2️⃣ **YOLO / Faster R-CNN을 이용한 객체 탐지 기반 손상 감지**
- 차량의 특정 손상 부위를 빠르게 탐지할 수 있도록 YOLO 및 Faster R-CNN 활용
- 사고 부위의 위치 정보를 제공하여 보험 심사 및 정비에 활용 가능

### 3️⃣ **전이 학습(Transfer Learning) 적용**
- 사전 학습된 EfficientNet, ResNet 모델을 활용하여 성능 최적화
- 적은 데이터셋에서도 높은 정확도를 유지할 수 있도록 최적화

## 📂 분석 대상 및 실험 내용
- **차량 손상 데이터셋 구축 및 라벨링**
- **CNN 및 객체 탐지 모델을 활용한 차량 손상 감지 실험**
- **모델별 성능 비교 및 최적화 연구**
- **실제 보험 심사 및 차량 관리 시스템과의 연계 가능성 평가**

## 🚀 프로젝트 목표
- **실시간 차량 파손 감지 시스템 개발**: 스마트 교통 및 보험 자동화를 위한 AI 솔루션 구축
- **고급 영상 처리 기법 적용**: CNN, YOLO, Faster R-CNN 등을 통한 최적의 모델 탐색
- **데이터 기반 연구 수행**: 연구 논문 작성 및 실험을 위한 고품질 데이터셋 구축

## 📌 기대 효과
- **차량 손상 평가의 자동화를 통한 비용 절감 및 처리 속도 향상**
- **AI 기반 차량 유지보수 및 보험 심사의 혁신 가능성 탐색**
- **실제 자동차 산업에 적용할 수 있는 실무적 기술 습득**

---
📢 **추후 업데이트 예정 사항**
- Transformer 기반 객체 탐지 모델(DETR, Swin Transformer) 추가 실험
- 실시간 모바일 앱 연동 가능성 연구
- 다양한 차량 환경에서의 데이터 확장 및 성능 최적화

이 프로젝트가 자동차 파손 감지 및 컴퓨터 비전 연구에 관심 있는 분들에게 의미 있는 경험이 되길 바랍니다! 🚀

# 스마트 침구 시스템 (Smart Bedding System)

## 프로젝트 개요

수면 중 사용자의 자세와 머리 위치를 실시간으로 인식하여 최적의 침구 환경을 제공하는 스마트 침구 시스템을 개발한 프로젝트입니다.

MediaPipe FaceMesh와 Head Pose Estimation 기술을 활용하여 사용자의 머리 방향과 자세를 추정하고, 이를 기반으로 베개의 높이를 자동으로 조절할 수 있는 알고리즘을 구현하였습니다.

## 개발 기간

* 2023.04 ~ 2023.06

## 프로젝트 목표

* 수면 자세를 실시간으로 인식
* 머리 위치 및 각도 추정
* 사용자 상태에 따라 베개 높이 자동 조절
* 수면 환경 개선을 위한 스마트 침구 시스템 구현

## 사용 기술

### Language

* Python

### Computer Vision

* OpenCV
* MediaPipe FaceMesh

### Machine Learning / Estimation

* Head Pose Estimation
* Facial Landmark Detection

### Environment

* Google Colab
* Jupyter Notebook

## 주요 역할

* FaceMesh 기반 얼굴 랜드마크 추출
* Head Pose Estimation 알고리즘 구현
* 머리 각도(Yaw, Pitch, Roll) 계산
* 자세 상태 분류 로직 구현
* 베개 높이 자동 조절 알고리즘 설계
* 실시간 영상 처리 및 결과 시각화

## 시스템 구성

영상 입력
→ 얼굴 랜드마크 추출(FaceMesh)
→ 머리 자세 추정(Head Pose Estimation)
→ 사용자 자세 분석
→ 베개 높이 조절 판단
→ 스마트 침구 제어

## 주요 기능

### 1. 얼굴 랜드마크 추출

MediaPipe FaceMesh를 활용하여 얼굴 주요 특징점을 검출

### 2. 머리 자세 추정

Head Pose Estimation을 통해 사용자의 머리 방향과 각도를 계산

### 3. 자세 분석

사용자의 현재 자세 상태를 판단하고 자세 변화를 감지

### 4. 베개 높이 자동 조절

머리 위치와 자세 정보를 기반으로 적절한 베개 높이를 결정

## 기대 효과

* 올바른 수면 자세 유지 지원
* 사용자 맞춤형 수면 환경 제공
* 스마트 헬스케어 분야 활용 가능

## Repository 구성

```text
smart-bedding-system
│
├─ 스마트침구_코드.ipynb
├─ README.md
├─ images
│   ├─ system_architecture.png
│   └─ demo.gif
└─ ppt
    └─ 발표자료.pdf
```

## 참고

본 저장소는 프로젝트 포트폴리오 용도로 작성되었으며, 일부 데이터 및 결과물은 공개 가능한 범위 내에서 제공됩니다.

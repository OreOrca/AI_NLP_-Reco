# AI_NLP_Reco

# 🚨 생성형 AI 카드 추천 서비스, RecoAI

<div align="center">
  <h3>멋쟁이사자처럼 자연어처리 1팀 Reco</h3>
</div>

## 📋 프로젝트 개요
![image](https://github.com/user-attachments/assets/69a691cc-1d40-4d15-85fd-46a87accc8c2)
images/화면 캡처 2024-12-25 205754.png
### 🎯 프로젝트 목표
고객의 소비 패턴을 분석하거나 요구사항에 맞게 가장 높은 혜택을 받을 수 있는 카드를 추천하는 인공지능 챗봇 서비스입니다.

### 💡 주요 기능
- 대화 내용 실시간 텍스트화 및 시각화
- 응급 상황 분석 인터페이스 구축
- 신고자 실시간 위치 특정 및 시각화
- 긴급 상황 분석 결과 제공
- 다양한 모델을 통한 분석 성능 향상

## 📊 데이터셋

### 데이터 출처
- 서울, 인천, 광주 지역 소방본부 제공
- 실제 신고 접수 음성 데이터와 메타 데이터 활용

### 데이터 규모
- **음성 데이터**: 3,064시간 분량
- **메타 데이터**: 총 158,973건

### 데이터 구성
- 신고 전화 음성의 텍스트 전사본
- 16종의 상황 유형 분류 (질병, 임산부, 산불 등)
- 긴급도 분류 (상, 중, 하)
- 신고자 정보
  - 성별
  - 감정 상태 라벨링

## 🏗️ 모델 아키텍처

### 1. KcELECTRA 기반 상황 분류 모델
#### 1. ![분류모델](/images/horizontal-multitask-electra.svg)
#### 2. ![분류모델](/images/separate-models.svg)
#### 3. ![분류모델](/images/hierarchical-model.svg)

### 2. 위치 정보 추출 모델
- TF-iDF 기반

## 📊 모델 성능 평가

### 1. 상황 분류 모델 성능

#### 상황 유형별 F1-Score

### 2. 긴급도 분류 성능

### 3. 학습 곡선

### 4. 혼동 행렬

## 🛠️ 시스템 구성

1. **음성 인식 시스템**
   - 실시간 음성-텍스트 변환
   - 대화 내용 시각화

2. **상황 분석 엔진**
   - 16종 상황 유형 분류
   - 긴급도 판단
   - 감정 상태 분석

3. **위치 추적 시스템**
   - 실시간 위치 특정
   - 지도 기반 시각화

4. **분석 결과 대시보드**
   - 종합 분석 결과 표시
   - 실시간 모니터링 인터페이스

## 📊 실행 결과

### 1. 메인 대시보드
- 실시간 상황 분류 결과 모니터링
- 긴급도별 통계 시각화

### 2. 분류 결과 시각화
- 상황 유형별 실시간 분류 현황
- 시계열 기반 긴급도 추이 분석

### 3. 위치 정보 시각화
- 신고 위치 클러스터링
- 지역별 상황 유형 분포

## 🔍 기대 효과

- 신고 접수 처리 시간 단축
- 응급 상황 대응 정확도 향상
- 효율적인 구조 자원 배치
- 시민 안전 서비스 품질 개선

## 👥 팀 구성
멋쟁이사자처럼 자연어처리 3팀 삐융삐융

---

© 2024 AI 응급 상황 분류 시스템. All Rights Reserved.

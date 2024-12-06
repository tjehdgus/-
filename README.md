# 💧 수자원공사 공모전 프로젝트

### 프로젝트 개요
2024년 K-water 대국민 물 빅데이터 공모전에서 장려상을 수상한 프로젝트입니다.  
기상 및 수문 데이터를 활용하여 머신러닝 기반의 가뭄 예측 시스템을 개발하였습니다.  
특히, **R**을 활용한 머신러닝 분석과 **Oracle** 데이터베이스를 활용한 데이터 관리로 성과를 도출했습니다.

---

### 🗂 프로젝트 내용

1. **문제 상황 및 분석 목적**
   - 대한민국은 여름철 강수 집중 현상으로 인해 가뭄 위험성이 증가하고 있으며, 효율적인 물 자원 관리가 필수적입니다.
   - 가뭄 예측 모델 개발을 통해 저수량 관리 및 물 자원 활용 계획 수립에 기여하고자 했습니다.

2. **데이터 설명**
   - **활용 데이터**:
     - 다목적 댐 및 용수댐 데이터 (댐 강우량, 방류량, 저수량 등)
     - 기상 데이터 (평균기온, 강수량, 일조시간 등)
     - SPI6 지수 기반 데이터
   - **데이터 수집 출처**:
     - K-water 데이터 포털
     - 기상청 자료

3. **모델 개발**
   - **변수 선택**:
     - 정보 획득량을 기준으로 예측 성능이 높은 5개의 독립변수를 선정.
   - **머신러닝 모델**:
     - 랜덤 포레스트(Random Forest)를 사용하여 모델 개발.
     - **평가지표 개선**:
       - F1 스코어: 0.933
       - AUC: 0.955
       - 정확도: 96.1%

4. **시스템 구현**
   - 예측 결과를 시각적으로 확인할 수 있는 웹 기반 대시보드 구축.
   - 사용자 입력을 통해 가뭄 확률을 계산하고 결과를 제공.

---

### 🛠 사용 기술 스택
- **언어**: R, SQL
- **분석 도구**: Random Forest
- **데이터베이스**: Oracle
- **데이터 시각화 및 웹 구현**: HTML/CSS (기본 대시보드)

---

### 📜 기대 효과
- 조기 경고 시스템을 통한 가뭄 피해 최소화.
- 댐 운영 최적화 및 농업용수 조절로 효율적인 물 자원 관리.
- 지속 가능한 물 관리 전략 수립에 기여.

---

### 🏆 성과
- **2024년 K-water 대국민 물 빅데이터 공모전 장려상 수상**  
  본 프로젝트는 높은 데이터 활용도와 예측 성능을 인정받아 수상하였습니다.

---

### 📄 발표자료
프로젝트의 자세한 내용은 발표자료에서 확인할 수 있습니다:  
[📂 발표자료 PDF](발표자료.pdf)


### 📷 프로젝트 대표 이미지
![수자원 공모전 대표 이미지](https://github.com/user-attachments/assets/your-image-link.jpg)
# -

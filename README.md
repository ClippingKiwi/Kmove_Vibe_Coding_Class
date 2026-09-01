# Create a README.md file using Python script

readme_content = """# 🚀 K-Move 바이브 코딩 수업 과제 제출

K-Move 바이브 코딩 수업에서 작성한 개인 및 팀 프로젝트 과제물 목록입니다.

---

## 📅 8월 31일 과제

### 1. 🇰🇷 korea_trip (개인)
> **일본인 관광객을 위한 한국 3박 4일 여행 추천 코스 웹페이지**
* **주요 내용:**
  * 일본인 맞춤형 3박 4일 한국 추천 여행 일정 안내
  * 주요 관광지, 맛집, 이동 경로 정보 제공
  * 사용자 친화적인 웹 레이아웃 구성

### 2. 🚌 0831 MT project (팀)
> **성공적인 MT를 위한 일정 및 가이드 웹페이지**
* **주요 내용:**
  * MT 세부 일정표 및 장소 안내
  * 예산, 준비물 체크리스트, 레크리에이션 프로그램 소개
  * 팀원 간 원활한 정보 공유를 위한 웹 페이지 구성

---

## 📅 9월 1일 과제

### 1. 🎮 Kmove_0901 (개인)
> **연령 및 성별에 따른 게임 선호도 조사 웹페이지**
* **주요 내용:**
  * 사용자 연령대 및 성별 입력 폼 구현
  * 장르별/플랫폼별 게임 선호도 설문 문항 설계
  * 직관적이고 깔끔한 UI의 설문조사 인터페이스

### 2. 🏠 0901 Team_Project (팀)
> **자취생 생활 실태 조사를 위한 설문 웹페이지**
* **주요 내용:**
  * 1인 가구 자취생들의 주거, 식비, 생활 패턴 실태 파악
  * 데이터 수집을 위한 맞춤형 설문 항목 구성
  * 사용자 응답 편의성을 고려한 웹 디자인
"""

file_path = "README.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

print(f"File created successfully: {file_path}")
print("[file-tag: readme-md-kmove-assignments]")

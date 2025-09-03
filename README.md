# 순수 마크다운 내용 (Python 코드 제거)
markdown_content_clean = """# 웹프로그래밍 수업 요약

## 📌 수업 목표
- 웹의 기본 구조와 동작 원리 이해
- HTML, CSS, JavaScript를 활용한 웹 페이지 제작 능력 습득
- 클라이언트-서버 모델 이해 및 적용
- 간단한 웹 애플리케이션 구현

## 📚 주요 학습 주제
1. **HTML** - 웹 문서의 기본 구조 정의
2. **CSS** - 스타일과 레이아웃 구성
3. **JavaScript** - 동적인 동작 구현
4. **웹 서버 기초** - 요청과 응답 이해
5. **데이터베이스 연동** - 기본 CRUD 기능

## 🛠️ 수업 방식
- 이론과 실습 병행
- 개인 과제 및 팀 프로젝트
- 코드 리뷰 및 발표

## 📝 평가 기준
- 출석: 10%
- 과제: 20%
- 프로젝트: 50%
- 시험: 20%

---
> 본 수업을 통해 웹 개발의 기초 역량을 다지고, 실무에 적용 가능한 경험을 쌓을 수 있습니다.
"""

# 새로운 마크다운 파일 경로
file_path_clean = "/mnt/data/web_programming_clean.md"

# 저장
with open(file_path_clean, "w", encoding="utf-8") as f:
    f.write(markdown_content_clean)

file_path_clean

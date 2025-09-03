import pypandoc

# Markdown 내용 작성
markdown_content = """# 웹프로그래밍 수업 개요

## 1. 수업 목표
- 웹 프로그래밍의 기초 이해
- HTML, CSS, JavaScript를 활용한 웹 페이지 제작
- 클라이언트-서버 구조 이해
- 간단한 웹 애플리케이션 개발 경험

## 2. 주요 학습 내용
- **HTML**: 웹 문서 구조 설계
- **CSS**: 스타일링 및 레이아웃 구성
- **JavaScript**: 동적 기능 구현
- **웹 서버와 데이터베이스**: 기본 개념 및 활용

## 3. 학습 방법
- 이론 강의 + 실습 병행
- 프로젝트 기반 학습
- 팀별 과제 및 발표

## 4. 평가 방식
- 출석: 10%
- 과제: 30%
- 프로젝트: 40%
- 시험: 20%

---
웹 프로그래밍 수업을 통해 실무에 적용 가능한 기초 역량을 습득합니다.
"""

# 파일 경로
file_path = "/mnt/data/web_programming_class.md"

# Markdown 파일 저장
with open(file_path, "w", encoding="utf-8") as f:
    f.write(markdown_content)

file_path

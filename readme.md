# Streamlit 간단한 계산기

Python과 Streamlit을 활용하여 웹 브라우저에서 간편하게 사용할 수 있는 기본 사칙연산 계산기 프로그램입니다. `class`를 사용하지 않고 직관적인 절차적 코드로 작성되었습니다.

---

## 🛠 주요 기능 및 특징
1. **웹 인터페이스**: Streamlit을 이용해 깔끔하고 직관적인 UI 제공
2. **사칙연산 지원**: `+`, `-`, `*`, `/` 연산 처리
3. **예외 및 유효성 검사**: 
   - 정수가 아닌 값이 입력된 경우 오류 메시지 출력
   - 0으로 나누기 시도 시 예외 처리 (`ZeroDivisionError`)
   - 지원하지 않는 연산자 입력 시 오류 안내
4. **간결한 구조**: `class` 없이 작성되어 초보자도 쉽게 코드를 이해하고 수정 가능

---

## 🚀 시작하기 (Installation & Running)

### 1. 요구 사항 (Prerequisites)
- Python 3.7 이상 권장

### 2. 의존성 패키지 설치
프로젝트 실행에 필요한 라이브러리를 설치합니다.
```bash
pip install -r requirements.txt
```

### 3. 애플리케이션 실행
터미널(콘솔)에서 아래 명령어를 입력하여 Streamlit 앱을 실행합니다.
```bash
streamlit run app.py
```

---

## 📁 파일 구조
- `app.py`: 계산기 메인 소스 코드 (Streamlit UI 및 계산 로직)
- `requirements.txt`: 프로젝트 의존성 관리 파일 (Streamlit)
- `README.md`: 프로젝트 설명서
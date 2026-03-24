# C Calculator Project

GitHub Actions를 이용한 C 언어 계산기 프로젝트 예제입니다.

## 프로젝트 구성
- 덧셈
- 뺄셈
- 곱셈
- 나눗셈
- 출력 함수 분리
- 테스트 코드 포함
- GitHub Actions CI 포함

## 폴더 구조
```text
c-calculator-project/
├─ .github/
│  └─ workflows/
│     └─ c-ci.yml
├─ include/
│  └─ calc.h
├─ src/
│  ├─ main.c
│  ├─ add.c
│  ├─ sub.c
│  ├─ mul.c
│  ├─ div.c
│  └─ print_result.c
├─ tests/
│  └─ test_calc.c
├─ Makefile
└─ README.md


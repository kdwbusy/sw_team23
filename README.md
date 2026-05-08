# 소프트웨어 공학 과제 - 팀 23

각 조원이 맡을 use case를 정해 그에 맡게 다음의 네 과정을 수행한다.

## 1) requirement list (functional requirement만 작성함)

## 2) 각 use case에 대한 UI 화면 (Figma 등 tool 사용함)

## 3) use case diagrams (UML tool 형식을 pdf 파일로 변환해야 함)

## 4) use case descriptions (step by step breakdown)

## 브랜치 규칙

- `main` 브랜치에는 직접 push하지 않습니다.
- 모든 작업은 각자 작업 브랜치를 만들어 진행합니다.
- 작업이 끝나면 Pull Request(PR)를 생성한 뒤 merge합니다.

### 브랜치 이름 규칙
```text
homework/your_name

```
## 작업 방법

1. main 브랜치 최신 내용을 pull 받습니다. 
2. 자신의 작업 브랜치를 생성합니다. 
3. 해당 주차 폴더에 본인 파일을 작성합니다. 
4. commit 후 원격 브랜치로 push합니다. 
5. GitHub에서 PR을 생성합니다.

## PR 제목 Convention
[Part #~#] your_name

## use case 목록

1. 회원 가입 페이지
2. 회원 탈퇴 페이지
3. 로그인 페이지

4. 로그아웃 페이지
5. 설문 등록 페이지 - 관리자
6. 설문 조회 페이지 - 관리자 
    extend: 설문 삭제

7. 통계 정보 조회 페이지 - 관리자
8. 설문 검색 페이지 - 회원
9. 설문 상세 정보 페이지 - 회원

10. 설문 응답 페이지 - 회원
11. 본인 응답 조회 페이지 - 회원
12. 응답 수정 페이지 - 회원
    extend: 응답 취소, 기간 선택


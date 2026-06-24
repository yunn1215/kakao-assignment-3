# Kakao Assignment 3

## 프로젝트 소개

Next.js와 FastAPI를 활용하여 구현한 Todo 관리 서비스입니다.

기존 로컬스토리지 기반 Todo 애플리케이션을 서버 API 기반 구조로 변경하였으며, 프론트엔드와 백엔드를 분리하여 데이터를 관리하도록 구현하였습니다.

---

## 기술 스택

### Frontend

- Next.js (App Router)
- TypeScript
- Tailwind CSS

### Backend

- FastAPI
- Python

---

## 주요 기능

- Todo 생성(Create)
- Todo 조회(Read)
- Todo 수정(Update)
- Todo 삭제(Delete)
- 진행 상태 필터링
- Todo 검색 기능
- 주간 캘린더 기반 일정 관리
- 날짜별 Todo 조회

---

## 프로젝트 구조

```text
kakao-assignment-3
├── frontend
│   ├── app
│   └── public
└── backend
    ├── main.py
    └── requirements.txt
```

---

## 실행 방법

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend

python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 구현하면서 배운 점

- Next.js App Router의 파일 기반 라우팅 구조를 이해할 수 있었습니다.
- FastAPI와 연동하며 프론트엔드와 백엔드의 데이터 흐름을 경험할 수 있었습니다.
- 기존 로컬스토리지 방식과 서버 API 방식의 차이를 이해할 수 있었습니다.

---

## GitHub Repository

https://github.com/yunn1215/kakao-assignment-3

### 📚 Daily Study Log

> "작은 성장이 모여 큰 변화를 만든다."

이 레포지토리는 매일 공부한 내용을 정리하고 기록하기 위한 공간입니다.  
공부한 내용을 다시 정리하고, 관련 커밋을 함께 기록함으로써  
스스로의 성장과 변화를 추적하고자 합니다.

---

### 🔍 목적

- 매일 학습한 내용을 간단히 요약하고 정리
- 공부 습관 형성 및 성찰 기회 확보
- 나중에 복습할 때 참고할 수 있는 나만의 기록 노트 만들기

---

### 🗂️ 작성 방식

- 파일 구조: `/YYYY-MM-DD.md` 형태로 저장
- 한 파일당 하루 학습 내용 정리
- 각 일자마다 **관련 커밋 링크** 포함

---

### ✍️ 일일 기록 템플릿

# 📅 2025-04-01

## 🎯 오늘의 학습 목표
- Django ORM에서 모델 간 관계 정의 방법 이해하기
- select_related, prefetch_related의 차이 실습으로 확인
- 정렬 관련 코딩테스트 문제 출제 및 풀이

---

## 🧩 오늘 배운 핵심 개념 / 정리
- `ForeignKey`, `OneToOneField`, `ManyToManyField`의 차이점
- `related_name` 옵션을 지정하면 역참조 이름 커스터마이징 가능
- `select_related`는 JOIN 쿼리로 한번에 가져오고, `prefetch_related`는 N+1 문제를 줄이는 방식
- Django shell에서 `.query`로 실제 쿼리문 확인 가능

---

## 🔢 오늘의 코딩 테스트 문제
- 문제 이름: [백준 3182번 : 한동이는 공부가 하기 싫어!](https://www.acmicpc.net/problem/3182)
- 문제 유형: 그래프 이론
- 난이도: ⭐️⭐
- 핵심 아이디어:
  - 
- 배운 점:
  - 
- 관련 커밋:
  - [백준 3182번 풀이]()

---

## ❓ 생긴 질문들 & 추가로 찾아본 내용
- Q: `prefetch_related`는 내부적으로 어떤 쿼리를 실행할까?
  - → `.query` 출력 확인, 실제로는 두 번의 SELECT 쿼리가 나감
  - → [Django 문서 - select_related vs prefetch_related](https://docs.djangoproject.com/en/stable/ref/models/querysets/#prefetch-related)

- Q: `related_name`을 잘못 지정하면 에러가 나는 경우?
  - → 같은 이름 중복 시 Reverse accessor clash 발생
  - → 해결법: related_name 값을 유니크하게 설정하거나 `+` 사용

---

## 🔍 관련 커밋
- [Django 모델 관계 실습 커밋](https://github.com/username/backend-study/commit/3f9e21b)

---

## 💡 오늘의 느낀 점 / 정리
- ORM은 추상화가 잘 되어 있지만, 결국 SQL의 원리를 이해하고 있어야 진짜 효율적으로 사용할 수 있다.
- 오늘은 공부하다가 생긴 질문이 꽤 많았고, 그걸 탐색하며 더 많은 개념을 연결할 수 있었다.

---

## 📎 참고 자료
- [Django ORM 공식 문서](https://docs.djangoproject.com/en/stable/topics/db/models/)
- [파이썬 collections 문서](https://docs.python.org/3/library/collections.html)

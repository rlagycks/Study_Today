# 📅 2025-03-30

## 🎯 오늘의 학습 목표 / 방향
- (Django 흐름파악, 백엔드 흐름 파악, C++로 병합 정렬 구현해보기)

---

## 🧩 오늘 배운 핵심 개념 / 정리
- (예: ForeignKey vs OneToOneField 차이점)
- (예: select_related는 JOIN, prefetch_related는 다중 쿼리)

---

## ❓ 생긴 질문들 & 추가로 찾아본 내용
- Q: select_related와 prefetch_related의 실제 SQL 차이는?
  - → [StackOverflow 링크](https://example.com)
  - → 실험해보니 prefetch는 N+1 문제 완화에 유리

- Q: ManyToManyField는 중간 테이블을 어떻게 관리할까?
  - → Django 공식 문서 참고, `through` 옵션 존재

---

## 🔍 관련 커밋
- [모델 필드 테스트 및 쿼리 비교](https://github.com/username/repo/commit/abc1234)

---

## 💡 오늘의 느낀 점 / 정리
- Django ORM은 편하지만 결국 SQL을 알아야 자유로워진다
- 질문이 생긴 순간이 제일 중요한 성장 포인트

---

## 📎 참고 자료
- [Django ORM 공식 문서](https://docs.djangoproject.com/en/stable/topics/db/models/)
- [Django 튜토리얼 강의 - 3강](https://example.com)

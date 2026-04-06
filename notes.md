## 2026.04.07 | 5430 - AC | 덱 + 파싱

### 틀린 이유
- size() unsigned 언더플로우
- 파싱 마지막 원소 누락

### 핵심 패턴
- size() 쓸 때 (int) 캐스팅
- stringstream + getline 파싱
- R은 카운트만, 마지막에 reverse

### 다음에 이 유형 보이면
- 덱 + 방향전환 → rev%2로 앞뒤 결정

[문제 링크](https://www.acmicpc.net/problem/5430)

---
# 빌더 패턴

→ 주요 개념 <br />
→ 팩토리 메서드 패턴과의 차이점 <br />

<br />

### 주요 개념

- Director
  - builder를 인자로 받아서 객체 생성의 단계를 정의
- Builder
  - Builder Interface
  - Concrete Builder : 실제로 객체를 생성하는 메서드가 구현됨

<br />

### VS 팩토리 메서드 패턴

- 팩토리 메서드 패턴은 객체 생성이 single step인데, 빌더 패턴은 객체 생성이 multi step임.
  - 객체 생성에 여러 단계가 있음 → 객체 생성에 여러 분기점이 있음 → 객체 생성 시 여러 패러미터를 받아야 함 → 단순 팩토리로 구현할 경우 코드가 지저분해짐
- 팩토리 메서드 패턴의 반환 객체는 동일한 인터페이스를 공유하는 반면, 빌더 패턴의 반환 객체는 동일한 인터페이스를 상속받지 않아도 됨.

<br />

## 📚 Reference

- https://velog.io/@jahoy/%EC%8B%A4%EC%9A%A9%EC%A0%81%EC%9D%B8-Python-%EB%94%94%EC%9E%90%EC%9D%B8-%ED%8C%A8%ED%84%B4-%EC%A0%95%EB%A6%AC
- https://refactoring.guru/design-patterns/builder

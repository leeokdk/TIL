## 코드숨 주간회고: 4주차

### ✅ 달성내역 체크

- [x] 주간 강의를 모두 들었는가?
- [ ] 주간 강의를 듣고 모르는 부분에 대해 질문을 했는가?
- [ ] 모든 과제를 PR하고 피드백/피드포워드 받았는가?
- [ ] 모든 과제를 풀이 내용을 보지 않고 기능구현 하였는가?
- [x] 모든 과제에 지적받은 부분을 무사히 수정하였는가?
- [ ] 일요일에 과제풀이를 하고 주간회고를 하였는가?

### 💬 배운내용

#### 4강 과제 
- [To-do 리스트 Redux를 사용하여 리팩터링 하기](https://github.com/CodeSoom/react-week4-assignment-1/pull/79)
  - [리듀서 리팩토링하기](https://ko.redux.js.org/recipes/structuring-reducers/refactoring-reducer-example/)
  - [eslint no-prototype-builtins](https://eslint.org/docs/rules/no-prototype-builtins)
    > handlers.hasOwnProperty(action.type) => Object.prototype.hasOwnProperty.call(handlers, action.type)

### ⏪ 회고

- 이번 주는 정말 아쉬움만 남은 주였다. 의지가 부족하지 않나 싶다..
- 시간관리가 되지 않는 것은 일의 우선순위를 제대로 알지 못해서 일까? 아무튼 반성하자.
- 분명히 다음 진도는 따라가기 힘들 것이다. 모두 내 잘못이니까 두 배로 공부하자.
- 계속 같은 변수명을 작성할 경우 어느 순간 꼬이는 순간이 발생함.
  - 하지만1 미관상 긴 변수명은 좋아보이지 않는다.
    - 하지만2 name 이라는 변수명보다 teamName 이라는 변수명이 꼬이지 않고 확실히 어떤 것을 사용하는지 알 수 있어서 더 좋은 것 같다.
      - 하지만3 후자를 차용할 경우 점점 길어지는 것을 막을 수 없다.
        - 하지만456... 
  - n번의 하지만을 겪은 어느 멀티버스의 나: 변수명은 켄트 선생님도 어려워할 정도로 어려운 것이 맞다. 계속 고민하자.

### 🔥 다음 일주일 계획

- 월요일은 일단 PR부터. 
- 테스트 코드를 과하다 싶을 정도로 꼼꼼하게 작성해보자.
- 수요일부터라도 하루한번 PR하기.
- 토요일까지 전체 코드가 작성되지 않았으면 벌칙으로 일요일 12시간 공부하기.
- 일요일은 끝났든 아니든 무조건 주간회고 작성.

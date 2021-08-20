# 📌 3주차 과제[Mission3]
- 과제 수행 기간: 8월 20일 ~ 8월 28일 오후 23시 59분
- 과제 리뷰 기간: 8월 29일 ~ 9월 2일
- 내용: Day 2~ 에서 만든 **Simple List Todo 앱을 강화**합니다. 아래의 요구사항을 만족하는 코드를 올려주세요.
  - 아래의 체크리스트를 복사하여 PR 시 활용해도 좋습니다!

### 공통
- [ ] 컴포넌트에 new를 붙이지 않고 쓸 경우 에러가 나도록 방어코드를 넣어주세요.
  - 컴포넌트를 class 형태로 구현한 경우 이 요구사항은 무시하셔도 됩니다.
- [ ] state를 갖는 컴포넌트의 경우, initialState를 받는 부분과 setState 함수에서 nextState를 받는 부분에서 state에 대한 validation을 추가해주세요.
- [ ] 가급적 변수는 const로 선언하며, 부득이한 경우에만 let을 사용합니다.

### TodoList
- [ ] To do의 값에 isCompleted라는 값을 추가합니다. 그리고 TodoList의 Todo를 클릭하면 해당 값이 토글 되도록 만듭니다.
  - isCompleted가 true인 경우 text에 삭선이 그어지도록 해주세요. false로 바뀌면 삭선을 없애주세요.
- [ ] Todo text 옆에 삭제 button을 만듭니다. 누르면 삭제 되도록 처리합니다.

### TodoCount
- [ ] TodoCount 컴포넌트를 만듭니다.이 컴포넌트는 TodoList 아래에 렌더링 되어야 하며, 완료된 Todo의 갯수 / 전제 Todo 갯수를 표시해주면 됩니다.
  - 이때 TodoCount에서 TodoList에 직접 접근해서 데이터를 가져오면 안 됩니다.

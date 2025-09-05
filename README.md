
1. action: all actions must have a type property

2. reducer: a fucntion that accepts state and action and returns a new state(If the reducer receives an action that it doesnot care about, it should return unchanged state)
3. connect returns a function. that function then calls our components
4. connect(mapStateToProps,mapDispatchToProps)
mapStateToProps: this determines what state is passed to our compomnent via props
mapDispatchToProps: declare wht actions to pass to our component on props
5. container component will connect to redux store

Redux async libraries:
1. redux thunk: returns func from action creators
2. redux-promise: use promise fro async
3. redux-observable:use rxjs observable
4. redux-saga:use generators


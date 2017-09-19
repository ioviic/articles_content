## Basics Redux-React
## Principles Redux

Based on what I know about Redux I can come with few principels that I notices and used along the period that I'm using Redux.

1. If we look at the first sentence of the [Redux](http://redux.js.org/) we can see

> Redux is a predictable state container for JavaScript apps

  The state of application is presented by a plain JavaScript object and it's called "state tree", this object is unique and immutable

2. The state tree is read only. You can change the state by dispathcing an "action", action also represet a plain JavaScript object, which identify what part of the state should change.

3. The changes to the state is done by "reducers". Reducers are pure function that receives an action, based on this action it takes current state applies changes and return new state.

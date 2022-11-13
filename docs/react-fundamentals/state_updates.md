---
sidebar_position: 5
---

# State Updates May Be Asynchronous
Often times you run into an issue like this
```ts
const handleEvent = e => {
setState(e.target.value);
console.log(state);
}
```

where state is not the most up to date value when you log it. This is caused by state updates being asynchronous.

Check out these resources for more information:
https://beta.reactjs.org/learn/queueing-a-series-of-state-updates
https://reactjs.org/docs/state-and-lifecycle.html#state-updates-may-be-asynchronous
https://blog.isquaredsoftware.com/2020/05/blogged-answers-a-mostly-complete-guide-to-react-rendering-behavior/#render-batching-and-timing
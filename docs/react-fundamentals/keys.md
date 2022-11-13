---
sidebar_position: 6
---
# The Importance of Keys When Rendering Lists in React
React depends on the use of stable and unique keys to identify items in a list so that it can perform correct and performant DOM updates.

Keys are particularly important if the list can change over time. React will use the index in the array by default if no key is specified. You can use the index in the array if the list doesn't change and you don't have a stable and unique key available.

Please see these resources for more information:

https://beta.reactjs.org/learn/rendering-lists#keeping-list-items-in-order-with-key
https://kentcdodds.com/blog/understanding-reacts-key-prop
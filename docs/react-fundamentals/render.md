---
sidebar_position: 2
title: "React Rendering Behavior"
---

# How does React rendering behavior work?
There are several common misunderstandings about how React renders components. It's important to know that:

- React re-renders components recursively by default
- State updates must be immutable
- Updates are usually batched together
- Context updates always cause components to re-render

See this post for a detailed explanation of how React rendering actually works:

https://blog.isquaredsoftware.com/2020/05/blogged-answers-a-mostly-complete-guide-to-react-rendering-behavior/
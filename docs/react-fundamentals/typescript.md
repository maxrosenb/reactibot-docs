---
title: "React + TypeScript"
sidebar_position: 8
---
# Resources for React + TypeScript
The best resource for how to use TypeScript and React together is the React TypeScript CheatSheet. It has advice on how to type function components, hooks, event handlers, and much more:

https://react-typescript-cheatsheet.netlify.app/

Also, we advise against using the React.FC type for function components. Instead, declare the type of props directly, like:
function MyComp(props: MyCompProps) {}:
See this issue for details on why to avoid React.FC:

https://github.com/facebook/create-react-app/pull/8177
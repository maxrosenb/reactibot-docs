---
title: "Avoiding Derived State"
sidebar_position: 7
---
# Avoid Derived State
You might not need getDerivedStateFrom props or state at all!
Copying data from React props to component state is usually not necessary, and should generally be avoided. The React team offered advice on when "derived state" may actually be needed:

https://reactjs.org/blog/2018/06/07/you-probably-dont-need-derived-state.html
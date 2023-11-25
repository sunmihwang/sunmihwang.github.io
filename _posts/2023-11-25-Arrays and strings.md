---
layout: single
title : "Arrays and strings"
---

- 변경 가능(Mutable): 변경될 수 있는 데이터 유형입니다. 
- 불변(Immutable): 변경할 수 없는 데이터 유형입니다. 불변하는 것을 변경하려면 전체를 다시 만들어야 합니다.
- Why should we care about something being mutable or immutable?
-- If you have a mutable array arr = ["a", "b", "c"] and an immutable string s = "abc", but you want to instead represent "abd", you can easily do arr[2] = "d", but you cannot do s[2] = "d". As such, if you wanted the string s = "abd", 

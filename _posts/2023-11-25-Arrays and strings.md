---
layout: multiple
title : "Arrays and strings"
---

- 변경 가능(Mutable): 변경될 수 있는 데이터 유형입니다. 
- 불변(Immutable): 변경할 수 없는 데이터 유형입니다. 불변하는 것을 변경하려면 전체를 다시 만들어야 합니다.
- Why should we care about something being mutable or immutable?
- If you have a mutable array arr = ["a", "b", "c"] and an immutable string s = "abc", but you want to instead represent "abd", you can easily do arr[2] = "d", but you cannot do s[2] = "d". As such, if you wanted the string s = "abd",

---
layout: multiple
title : "Two pointers"
---

- 두 포인터는 배열 및 문자열 문제를 해결하는 데 사용되는 매우 일반적인 기술입니다. 이는 반복 가능 항목을 따라 이동하는 두 개의 정수 변수를 갖는 것과 관련됩니다. This means we will have two integers, usually named something like i and j, or left and right which each represent an index of the array or string.
- 두 개의 포인터를 구현하는 방법에는 여러 가지가 있습니다. 입력 가장자리에서 포인터를 시작합니다. 만날 때까지 서로를 향해 이동하십시오.
 - 첫 번째 인덱스에서 포인터 하나를 시작 0하고 마지막 인덱스에서 다른 포인터를 시작합니다 input.length - 1.
 - 포인터가 서로 같아질 때까지 while 루프를 사용합니다.
 - 루프가 반복될 때마다 포인터를 서로를 향해 이동합니다. 이는 첫 번째 인덱스에서 시작된 포인터를 증가시키거나, 마지막 인덱스에서 시작한 포인터를 감소시키거나, 둘 다를 의미합니다. 이동할 포인터를 결정하는 것은 우리가 해결하려는 문제에 따라 달라집니다.

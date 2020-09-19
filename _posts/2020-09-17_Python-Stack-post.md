---
title: "Stack"
date: 2020--09--17 15:00:00 -0400
categories: Python
---
Stack은 데이터의 삽입과 삭제를 배열의 끝에서만 데이터를 접근할 수 있는 선형 자료구조이다. 스택은 배열 인덱스 접근이 제한되며, 

데이터가 순서대로 저장되고 마지막에 넣은 요소가 처음 꺼내지는 후입선출(LIFO)의 구조이다.

Stack의 동작은 다음과 같고, 시간복잡도는 모두O(1)이다.

​```python

 push: 스택 맨 끝(맨 위)에 항목을 삽입한다.
 pop: 스택 맨 끝 항목을 반환하는 동시에 제거한다.
 top/peek: 스택 맨 끝 항목을 조회한다.
 empty: 스택이 비어 있는지 확인한다.
 size: 스택 크기를 확인한다.

```

​```python

class Stack(object):
.
    def__init__(self):
        self.items = []

​```


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
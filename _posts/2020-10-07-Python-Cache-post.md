---
title: "Python_Cache"
date: 2020-10-07 14:00:00 -0400
categories: Python Algorithm
---


카카오 코딩테스트 캐시문제를 풀어보기 전에 용어를 정리해보았다.

Cache를 알기 전에 Mapping이란 가상주소와 물리주소의

대응 관계 또는 가상주소로 물리주소를 찾아내는 것을 말한다.


    LRU 알고리즘이란

    운영체제에서 가상 메모리 관리를 위한 페이지 교체 알고리즘을 말한다.

    Cache란

    프로그램이 수행될 때 나타나는 지역성을 이용하여 

    메모리나 디스크에서 사용되었던 내용을 빠르게 접근할 수 있는 곳에

    보관 및 관리하고 이 내용이 다시 필요할때 빠르게 참조할 수 있도록 하는 것이다.

    Cache Hit란

    CPU가 참고하고자 하는 메모리가 캐시에 존재하고 있을 경우 Cache Hit라고 한다.

    Cache Miss란

    CPU가 참고하고자 하는 메모리가 캐시에 존재하지 않을때 Cache Miss라고 한다.



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
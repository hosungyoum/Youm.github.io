---
title: "Python[String]"
date: 2020-10-07 14:00:00 -0400
categories: Python Algorithm
---

join()

= A.join(B)는 리스트 B에 있는 문자열을 하나의 단일 문자열 A로 결합한다.

    ex) A = ["개발자", "공부"]
    " ".join(A)
    ="개발자 공부"

내장함수 reversed()매서드를 join()과 같이 사용할 수 있다.

    "".join((A))
    ="공부 개발자"

split()

= A.split(t,n)는 문자열 A에서 문자열 t를 기준으로 정수 n번만큼 분리한 문자열 리스트를 반환한다.

    ex) A = "공부-개발-파이썬"
        B = A.split("-")
      = B
      ["공부", "개발", "파이썬"]

 위의 설명처럼 n을 지정하지 않아도 예제처럼 t로 최대한 분리한다.     













[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
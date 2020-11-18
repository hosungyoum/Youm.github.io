---
title: "Swift[DataType]"
date: 2020-09-08 20:00:00 -0400
categories: Swift 
---
1. 정수형 데이터 타입

스위프트는 8비트, 16비트, 32비트, 64비트 정수를 지원하며, 각각의 데이터 타입은 Int8, Int16, Int32, Int64
애플은 특정 크기의 데이터 타입을 사용하기 보다는 Int데이터 타입을 사용하라고 권장한다.
모든 정수형 데이터 타입들은 해당 데이터 타입이 지원하는 최댓값과 최솟값을 알 수 있도록 범위 속성을 가지고 있다.

2. 부동소수점 데이터 타입

스위프트는 소수점이 있는 값을 저장할 수 있다. 예를 들어, 42134.11113은 부동소수점 데이터 타입으로 저장할 수 있다.
두 가지 부동소수점 데이터 타입을 제공하는데, Float, Double 이다.
저장될 값의 크기와 소수점 이하의 값을 얼마나 정확하게 표현해야 하느냐에 따라 결정된다.

3. 불리언 데이터 타입

참과 거짓을 처리하는 목적의 데이터 타입을 가지고 있다.

4. 문자 데이터 타입

문자, 숫자, 문장부호, 기호와 같은 하나의 문자를 저장하는데 사용한다.
스위프트에서 문자는 내부적으로 그래핌 클러스터의 형태로 저장된다. 그래핌 클러스터는 눈에 보이는 하나의 문자를 표현하기 위해
결합된 둘 이상의 유니코드 스칼라로 구성된다.

5. 문자열 데이터 타입

문자열 데이터 타입은 저장 메커니즘을 제공할 뿐만 아니라, 문자열 검색, 매칭, 연결, 그리고 수정 등의 다양한 문자열 편집 기능을 가지고 있다.
문자열은 문자열 보간이라는 개념을 이용하여, 변수, 상수, 표현식, 함수 호출을 조합하여 구성할 수도 있다. 

​```
var userName = "Hosung"
var inboxCount = 26
let maxCount = 100

var message = "\(userName) has \ (inboxCount) messages.

print(messge)

Hosung has  26 messages.가 출력될 것이다.

​```

6. 특수문자/이스케이프 시퀀스

표준 문자들뿐만 아니라, 개행, 탭 또는 문자열 내에 특정 유니코드 값을 지정하는 이스케이프 시퀀스라는 특수 문자도 있다.
이러한 특수 문자들은 \를 문자 앞에 작성한다. 이것을 이스케이핑이라고 한다.
기본적으로 \가 붙은 문자는 특수 문자로 간주된다. 만약 \ 문자를 쓰고 싶다면 밑에 예시처럼 사용하면 된다.

```
var escaping = "\n"
var backslash = "\\"

​```


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

---
title: "Swift[Struct, Class]"
date: 2020-11-11 15:30:00 -0400
categories: Swift 
---
아래 내용은 Apple에서 공개한 Swift 5.3을 참고하였습니다.


구조체는 하나 이상의 변수를 묶어서 새로운 자료형을 정의하는 것이다.
Swift는 기본 자료형 타입(Int, Float, Double, String, Array, Dictionary, Set)등 
모두 구조체 형태로 구현이 되어있다.

```Swift

struct 예제 {
        //구조체를 정의
}
​```

​```
struct Project {
    var width = 0
    var height = 0
}
​```

Apple 공식 문서에 Struct 자료 형태 사용 권장 내용은 아래와 같다.

1. 연관된 간단한 값의 집합을 캡슐화하는 것만이 목적인 경우
2. 캡슐화한 값을 참조하는 것보다 복사하는 것이 적합한 경우
3. 구조체에 저장 된 프로퍼티가 값 타입이며 참조하는 것보다 복사하는 것이 적합한 경우
4. 다른 타입으로부터 상속받거나 자신을 상속할 필요가 없는 경우


클래스는 객체 지향 프로그래밍에서, 데이터와 그 조작 절차인 메소드를 정리한 객체의 추형을 정의한 것이다.

```Swift

class Resolution {
        //클래스를 정의
}
​```

```Swift

class Video {
        var resolution = Resolution()
        var interlaced = false
        var frameRate = 0.0
        var name: String?
}
​```
[공통점]

1. 값을 저장하기 위해서 프로퍼티를 정의할 수 있다.
2. 기능 실행을 위해서 메서드를 정의할 수 있다.
3. 서브 스크립트 문법을 통하여 구조체 또는 클래스가 갖는 값에 접근하도록 서브 스크립트를 정의 할 수 있다.
4. 초기화될 때의 상태를 지정하기 위해서 이니셜 라이저를 정의할 수 있다.
5. 초기 구혀과 더불어 새로운 기능 추가를 위하여 익스텐션을 통하여 확장할 수 있다.
6. 특정 기능을 실행하기 위해서 특정 프로토콜을 준수할 수 있다.

[차이점]

1. 구조체는 클래스와 달리 상속을 할 수 없다.
2. 타입 캐스팅은 클래스의 인스턴스에서만 사용이 가능하다.
3. 디이니셜 라이저는 클래스의 인스턴스에만 사용할 수 있다.
4. 참조 횟수 계산은 클래스의 인스턴스에서만 적용된다.












Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

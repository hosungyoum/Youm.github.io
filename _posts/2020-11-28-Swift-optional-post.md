---
title: "optional"
date: 2020-11-28 20:00:00 -0400
categories: Swift
---

## Swift 

> 핵심만 골라 배우는 SwiftUI 기반의 iOS 프로그래밍을 참고했습니다
----------------------------------------------------

옵셔널 타입의 목적은 변수 또는 상수에 값이 할당되지 않은 상황을 처리하기 위해 
일관된 접근 방식을 제공하는 것이다.

    """
        var index: Int?
                        

index 변수는 정수 값이 할당되거나 아무런 값도 할당되지 않을 수 있다.
어떤 값도 할당되지 않더라도 옵셔널은 nil 값을 갖게 된다.

예를 만들어 살펴보겠다

    """
        var index: Int?

        index = 1

        var FoodArray = ["chicken", "pizza", "kimchi", "bibimbap"]

        if index != nil {
            print(FoodArray[index!])
         } else {
              print("index does not contain a value")
         }
                                                                

옵셔널에 값이 할당되었다면 해당 값이 옵셔널 내에서 (wrapped)이라고 말한다.
옵셔널 안에 래핑된 값을 사용할 때는 (forced unwrappong)라고 말한다.

위의 index 변수가 옵셔널 타입이기 때문에 변수명 뒤에 느낌표를 두어 값이 언래핑된다.
느낌표를 빼면 언래핑되지 않아 에러를 낼 것이다

    """
        Value of optional type 'Int' must be unwrapped to a value of type 'Int'
                                                                                

강제 언래핑 대신, 옵셔널로 할당된 값은 옵셔널 바인딩을 이용하여 
임시 변수나 상수에 할당 할 수 있다

    """
        var index: Int?

        index = 1

        var FoodArray = ["chicken", "pizza", "kimchi", "bibimbap"]

        if let likefood = index {
            print(FoodArray[likefood])
         } else {
              print("index does not contain a value")
         }    

여기서  index 변수에 할당된 값이 언래핑되어 likefood라는 임시 상수에 할당 되어 
배열에 대한 인덱스로 사용된다.
if 구문 실행이 끝나면 이 상수는 더 이상 존재하지 않게 되며, 동일한 이름을 사용해도
충돌하지 않는다.





   
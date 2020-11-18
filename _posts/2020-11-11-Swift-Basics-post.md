---
title: "Python[String]"
date: 2020-10-07 14:00:00 -0400
categories: Python 
---

Swfit에서 상수(constants)는 개발 전반에 걸쳐 사용되지만, 바꿀 필요가 없는 값을 안전하고 명확하게 만들어 준디.

Swift는 Object-C에 없는 고급 타입들도 도입했고 그것이 튜플(tuple)이다. 
튜플은 값들을 그룹지어 생성하고 전달할 수 있겍 해준다. 튜플을 사용하면 함수에서 여러개의 값을 단인할 복합 값의 형태로 반환할 수 있다.

Swift는 값이 없는 상태를 처리하는 옵셔널 타입도 도입했다. 옵셔널은 여기 값이 있으며, 그 값은 X입니다. 라고 하거나 여기에 값이 전혀 없습니다라고 말한다.

상수의 값은 일단 한 번 설정되면 바꿀 수 없지만, 변수는 나중에 다른 값으로 설정할 수 있다.
상수는 선언시 let키워드를 사용하며, 변수는 var키워드를 사용합니다. 
다음은 상수와 변수를 사용하여 로그인 시도 횟수를 추적하는 방법에 대한 예제입니다.

```Swift

let maxumunNumberOfLoginAttempts =  10
var currentLoginAttempt = 0

​```
위의 예제에서 로그인 시도로 허용된 횟수는 상수로 선언된 10회이며, 현재로그인 시도수는 0부터 시작한다.

var welcomeMessage: String

​```
var friendlyWelcome = "Hello!"
friendlyWelcome = "Bonjour!"; print(friendlyWelcome)
//friendlyWelcome의 값은 Bonjour! 로 바뀐다.
//세미콜론을 작성하면 여러 개의 분리된 구문을 한 줄에 쓸 수 있다.
​```






[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
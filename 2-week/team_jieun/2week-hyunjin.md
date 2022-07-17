# <객체(Object)>

서로 연관되어 있는 데이터들을 담아내기 위한 그릇

(배열과 유사하다)

key와 value로 구성된 프로퍼티의 집합

-프로퍼티: 속성이라는 뜻으로, js에서 객체 내부의 속성을 의미한다. “key : value”의 형식으로, 객체 안의 쉼표로 구분되어 할당됨

객체에는 객체를 담을수도, 함수를 담을 수도 있다.

이때 객체에 담긴 함수를 ‘메서드’라고 한다.

```jsx
//객체를 만드는 방법
var ages= {'hyunjin':21, 'jieun':20, 'juhyun':23};
            //key : value

//객체 속성에 접근하는 방법
ages['hyunjin'] >> 21
ages.hyunjin >> 21
```

# <모듈>

프로그램을 구성하고 있는 수많은 로직들을 재사용할 수 있도록 구역을 나누어서 별도의 ‘모듈’이라는 형태로 떼어내 또 다른 프로그램에 부품으로 사용함.

이때 부품 → 모듈

부품으로 사용하는 기법 → 모듈화

 - 간단하게 외부 스타일시트를 src를 이용해 연결하는 것과 같이 js도 src를 이용해 연결하는 것을 말함

모듈화 중 하나 : 코드를 여러 개의 파일로 만들어서 저장

모듈화 장점

 - 자주 사용되는 코드를 필요할 때마다 재활용할 수 있다.

 - 코드를 개선하면 이를 사용하고 있는 모든 애플리케이션의 동작이 개선된다.

 - 코드를 수정할 때 필요한 로직을 빠르게 찾을 수 있다.

 - 필요한 로직만을 로드해 메모리의 낭비를 줄일 수 있다.

 - 한번 다운로드 된 모듈은 웹브라우저에 의해서 저장되기 때문에 동일한 로직을 로드할 때 시간과 네트워크 트래픽을 절약할 수 있다. (브라우저에서만 해당)

  - 트래픽? 서버를 통해 최종 사용자에게 전달된 데이터의 양을 말함

js에서는 다른 언어들처럼 모듈이라는 개념이 분명하게 존재하지 않는다. 하지만 js가 구동되는 환경 (브라우저, node.js)을 호스트 환경이라고 하는데, 호스트환경에 따라서 js 로직을 파일로 분할해 마치 다른 언어에서의 모듈처럼 사용할 수 있는 방법을 제공하고 있음.

# <라이브러리>

자주 사용되는 로직을 재사용하기 편리하도록 잘 정리한 일련의 코드들의 집합

 - jQuery

 - D3.js

 - Bootstrap(부트스트랩)

- 프레임워크

 - react(리액트)

 - angular(앵귤러)

 - vue(뷰)

- 라이브러리 vs 프레임워크

가장 큰 차이점: 개발 흐름의 주도권을 누가 가지고 있는가?

-라이브러리는 자신에게 필요한 기능만 사용해도 되므로 개발 주도권이 개발자에게 있음

-프레임워크는 웹 개발을 시작하는 방법부터 기능을 구현하는 모든 것을 프레임워크에서 정해 놓은 대로 따라야하기 때문에 개발 주도권이 프레임워크에 있음

-쉽게 설명 → 라이브러리: 요리 서바이벌 프로그램에서 요리를 시작하기 전에 여러 양념들과 재료들을 정리해두고 제작자인 내가 가져와서 쓰는 느낌!

→ 프레임워크: 프로그램을 제작할 때 보통 따르는 기본적인 툴을 ‘프레임워크’라고 만들어두고, 내 의도에 따라 프레임워크를 수정하는 느낌 ~> 밀키트같은 존재

# <UI, API>

- UI, API
    
    UI(User Interface) = 사용자 인터페이스 : 사용자와 컴퓨터 프로그램이 서로 상호작용을 하기 위해 서로 입력과 출력을 제어하는 것
    
    ex) 버튼을 누르면 경고창이 뜰 때 버튼같은 장치
    
    API(Application Programming Interface) : 애플리케이션을 만들기 위해 프로그래밍을 할 때 사용하는 조작장치
    
    ex) alert() 경고창
    
    -경고창의 확인 버튼, x 모양의 닫기 버튼 등 우리가 의도하지 않아도 자동으로 만들어지는 부분이 있음. 이 점에서 alert라는 명령은 웹브라우저를 제어하기 위한 인터페이스이고, 이러한 인터페이스들을 조합해 애플리케이션을 만들 수 있음
    
    -일반 사용자들이 UI를 이용해 웹브라우저를 제어한다면, 개발자들은 API를 자신의 의도에 맞게 이용해 웹브라우저를 제어한다고 할 수 있음.
    
    - 레퍼런스와 튜토리얼
    
    프로그래밍을 공부하기 위한 자료는 크게 레퍼런스와 튜토리얼이 있다. 보통 튜토리얼은 언어의 문법을 설명하고, 레퍼런스는 명령어의 사전을 의미한다.
    
    -대표적인 JS API 레퍼런스 : MDN
    
    [JavaScript | MDN](https://developer.mozilla.org/ko/docs/Web/JavaScript)
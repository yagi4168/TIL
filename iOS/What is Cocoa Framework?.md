iOS 앱 개발을 시작하고 자료등을 찾아보면서 굉장히 많이 마주치는 단어가 있다. 그것이 바로 "코코아" 라는 단어다.<br>
코코아 프레임워크, 코코아 터치, 코코아 팟 등 여러가지가 자주 보이는데 이게 무엇일까?

<br>

# 프레임워크 (Framework)
프레임워크는 이름대로 Frame(틀) + Work(일하다)의 합성어이다. 합치면 "틀, 뼈대를 가지고 일한다."가 된다. <br>
즉, 프레임워크는 "일정한 형태의 틀. 제공받은 일정한 요소와 틀, 규약을 가지고 무언가를 만드는 일" 이라고 생각하면 될 것이다.

<br>

# 코코아 프레임워크(Cocoa Framework)
코코아 프레임워크는 애플에서 프레임워크들을 여러개 모아서 더욱 큰 프레임워크로 구성한 것 이다.

여기에서 "터치"기능과 관련된 디바이스의 애플리케이션을 개발할 때 사용하는 도구가 "코코아 터치 프레임워크"이다. 
일반적으로 iOS 개발을 할 때, 이 코코아 터치 프레임워크를 사용하게 된다. <br>
이 프레임워크 안에는 UIKit, Foundation 프레임워크 등이 포함되어있으며, 이를 사용하고자 한다면 import로 쉽게 불러올 수 있다.

- Foundation: 말 그대로 기반을 위한 도구들(데이터 타입, 콜렉션, OS기능 등)이 포함되어 있다.
- UIKit: iOS를 위한 기반을 제공하며, 인터페이스 그래픽을 구성하는 도구를 포함한다.

<br>

# 코코아팟(CocoaPods)

> **코코아팟 사이트에 올라와있는 글이다.**<br>
CocoaPods is a dependency manager for Swift and Objective-C Cocoa projects. It has over 84 thousand libraries and is used in over 3 million apps. CocoaPods can help you scale your projects elegantly.

코코아팟은 Swift와 Objective-C 코코아 프로젝트를 위한 의존성 매니저이다. 굉장히 많은 라이브러리를 가지고 있으며 굉장히 많은 애플리케이션에 사용되고 있다. 당신의 프로젝트가 우아하게 돌아가도록 도와줄 수 있다.

만약 코코아팟 없이 프로젝트를 생성하면, 오픈소스 프레임워크 중에 원하는 기능이 있을 때 해당 프레임워크를 수동으로 설치해야하며, 프로젝트 안에 로드시키는 과정이 반드시 필요하다.<br>
빌드 설정 또한 우리가 직접 건들어줘야하며, 버전이 업데이트 될 때마다 위 작업들을 다시 새로해주어야 하는 불편함이 생긴다.
이러한 불편함들을 해소해주기 위해 만들어진 것이 코코아팟이다.

코코아팟에 사용하고자 하는 라이브러리/프레임워크의 목록들을 텍스트로 작성해두면 알아서 설치와 업데이트를 진행하고, Xcode 프로젝트와의 연결 및 설정도 도와준다.

<br>

## 코코아(Cocoa)라는 이름의 유래
코코아 이름의 유래는 Java 언어의 이름이 커피원산지에서 따온 이름이라서, 애플 개발자는 어린이도 할 수 있도록 하자는 의미에서 코코아로 지었다고 한다.
# iOS_Study
숭실대 IT대생 5명이 모인 iOS 스터디.


# iOS_Study 목차

## 주제별 순서
  1. Swift 필수 문법 & UIKit 개념
  2. 주요 개념 학습 : 로컬 DB, 서버 통신, 비동기 처리, 스레드 관리
  3. MVC, MVVM 패턴을 비롯한 Design Pattern
  4. SwiftUI & RxSwift 찍먹
  5. Code Refactoring   
  
  
## 주제별 세부사항
  1. Swift 필수 문법 & UIKit 개념
    1.1 
  2. 주요 개념 학습 : 로컬 DB, 서버 통신, 비동기 처리, 스레드 관리, 토큰 관리
  3. MVC, MVVM 패턴을 비롯한 Design Pattern
  4. SwiftUI & RxSwift 찍먹
  5. Code Refactoring  
       
&nbsp;&nbsp;       
# 1. Swift 필수 문법 & UIKit 개념

## **파트소개**

- **자세한** **설명**
    
    **a. Swift도 자바와 같은 객체지향 언어입니다. 
    물론 함수지향의 성격도 있지만 기본적으로 객체지향 언어입니다. 
    객체지향을 기본적으로 알기에 Swift에서 추가된 문법만 깊게 공부하고, 나머지 개념은 가볍게 넘어가려합니다.**
    
    **b. UIKit에 대한 개념은 필수적입니다. 
    저는 프로젝트를 하며 그때그때 필요한 UIKit 정보를 검색하며 학습했지만, 전체적인 컴포넌트 요소들을 알고 그들의 내장 함수도 알고 있다면 개발하는데 수월할 것입니다.**
    

## 구체화

a와 b를 동시에 진행하려합니다.

**a. Swift 문법**

언어에 대해 이해하는 속도는 사람 마다 다르기 때문에  

완전 기본적인 문법은 스스로 추가해서 공부하시면 될 것 같습니다.

문법에 대한 스터디는 **“** **Unwrap & Optional, 제네릭, 클로저, 프로토콜, 확장 “** 파트는 함께 공부하고 
이외 파트는 자율적으로 진행하겠습니다.

아래 강의로 Swift 문법 스터디 진행하겠습니다.

[[무료] 개발하는 정대리 스위프트 기초 문법 - 인프런 | 강의](https://www.inflearn.com/course/%EC%A0%95%EB%8C%80%EB%A6%AC-%EC%8A%A4%EC%9C%84%ED%94%84%ED%8A%B8-%EA%B8%B0%EC%B4%88/dashboard)

**b. UIKit**

UIKit은 iOS 개발에 쓰이는 필수 오프젝트들을 제공하는 프레임워크입니다. 기본적인 Label, Button 부터 다양한 기능이 존재합니다. Apple 공식 페이지에도 UIKit에 대한 설명이 자세히 나와있지만 가독성이 떨어집니다.

따라서 Apple 공식 페이지에서 가이드라인을 제공받고 구글링을 통해 살을 붙이려합니다.

대면 스터디마다 개인적으로 UIKit 중 조사해올 부분을 정해서 서로 설명하는 방식으로 진행하려합니다. 

UIKit은 누가 얼마나 개발을 잘하는지와 상관없는 파트입니다. 조사를 많이하고 시간을 쓴 사람이 설명도 잘할 수 있는 파트입니다.

아래 링크는 Apple 공식 페이지이고

[Apple Developer Documentation](https://developer.apple.com/documentation/uikit/about_app_development_with_uikit)

이후 살을 붙이는 과정은 개인적으로 하여 스터디 시간에 설명하면 될듯 합니다.

스터디에서 공부한 UIKit의 오프젝트를 노션에 따로 정리하려 합니다.

아래는 Apple 공식 페이지에 있는 UIKit의 목차와 종류입니다.

### **App Structure**

**App and Environment** **-** ****Life cycle : 지우**** 

****Documents, data, and pasteboard : 동현****

****Resource management : 현아****

****App extensions : 윤빈****

****Interprocess communication : 준혁****

****Mac Catalyst : 준혁****

### **User Interface**

****Views and controls : 현아, 윤빈****

****View controllers : 동현, 준혁****

****View layout : 지우****

****Appearance customization****

****Animation and haptics****

****Windows and screens****

### **User Interactions**

****Touches, presses, and gestures****

****Menus and shortcuts****

****Drag and drop****

****Pointer interactions****

****Pencil interactions****

****Focus-based navigation****

****Accessibility for UIKit****

### **Graphics, Drawing, and Printing**

****Images and PDF****

****Drawing****

****Printing****

### **Text**

****Text Display and Fonts****

****TextKit****

****Keyboards and input****

****Handwriting recognition****

### **Deprecated**

****Deprecated symbols****

## 파트 진행 일정

12/19 ~ 1/9 ( 조정 가능하나 일단 4주 생각하고 있습니다. )

&nbsp;&nbsp;      
# 2. 주요 개념 학습 : 로컬 DB, 서버 통신, 비동기 처리, 스레드 관리, 토큰 관리

### a. 파트1에서 Swift 문법과 UIKit을 공부했다면, 우리는 프로젝트에서 화면 UI 구현까지만 할 수 있습니다. “로컬 DB, 서버 통신, 비동기 처리, 스레드 관리,토큰 관리” 이것들은 제가 프로젝트를 하며 알아야할 개념이라 생각해서 선정했습니다.

&nbsp;&nbsp;
# 3. MVC, MVVM 패턴을 비롯한 Design Pattern

### a. 파트 1,2를 공부하면 대략적인 기능은 개발할 수 있다고 생각됩니다. 하지만, 유지보수가 원활한 코드를 위해서 디자인 패턴 공부는 필수적입니다.

### b. 학습 방법 : 기본적인 학습 이후, 특정 서비스를 코드로 개발하지 않고 Model, View, ViewModel, ViewController 단위로 나누어 설계해보려 합니다. 이후 서로의 설계를 피드백하려 합니다.

&nbsp;&nbsp;
# 4. SwiftUI & RxSwift 찍먹

### a. UIKit을 확실히 공부하고 SwiftUI를 공부하는게 맞다고 합니다.
하지만, 궁금하니까… ㅎㅎ 찍먹만 해볼 생각입니다.

### b. RxSwift를 안쓰는 프로젝트를 찾기 힘들 정도로 많이 사용되는 기술입니다. MVVM 패턴을 쓰기 위해서는 꼭 필요한 기술이라고 합니다. 너무 깊게는 아니더라도 같이 공부해보면 좋을 것 같아 추가해두었습니다.

&nbsp;&nbsp;
# 5. Code Refactoring

### a. 마지막은 역시 남이 쓴 코드를 피드백해보면 확실히 배울것 같아 넣어두었습니다. 피드백 해볼 코드는 제가 개발하고 있는 Velog In Mobile 코드를 리펙토링 해보려합니다. 피드백 할게 많아 보여서요 ㅎㅎ.

### b. 학습 방법 : 제가 쓴 코드인 만큼, 제가 클래스 별로 코드를 설명하려합니다. 이후 해당 클래스의 코드 스타일이나 디자인 패턴에 대한 피드백을 하고 기회가 된다면 함께 리펙토링하는 과정도 생각하고 있습니다.

# JAVASCRIPT : PARALLAX EFFECT

![parallaxMain](https://github.com/YeoDaSeul4355/ParallaxEffect/assets/125419623/55ec17ce-4ab1-4882-8780-fc47c580e335)
<br><br>

> View Site : https://kebab000.github.io/web2023/javascript/parallax/parallaxEffect01.html

<br><br>

자바스크립트를 활용하여 패럴랙스(Parallax) 이펙트를 구현한 특별한 웹 사이트를 만들었습니다.화면을 스크롤할 때마다 명언 문구들이 화면에 다양한 효과와 함께 부드럽게 등장합니다. 
GSAP(GreenSock Animation Platform)와 자바스크립트를 활용하여 구현되었습니다. GSAP는 강력하고 유연한 애니메이션 라이브러리로, 웹 사이트에 효과적이고 멋진 애니메이션을 구현하기 위해 사용되었습니다.
<br><br>

## 사용 스택과 메서드
- HTML: HTML 언어를 사용하여 웹 페이지의 구조와 콘텐츠를 정의합니다.
- CSS: CSS(Cascading Style Sheets)를 사용하여 웹 페이지의 스타일을 지정합니다.
- JAVASCRIPT :
   - setActive(link): setActive() 함수는 링크가 활성화되었을 때 호출되는 함수로서, 메뉴 링크의 활성화 상태를 변경합니다. 모든 메뉴 링크에서 "active" 클래스를 제거하고, 클릭된 링크의 부모 요소에 "active" 클래스를 추가합니다.
- GSAP (GreenSock Animation Platform) :
  - gsap.utils.toArray(): GSAP의 유틸리티 메서드로서, 선택자를 기준으로 해당 요소들을 배열로 반환합니다. 이 코드에서는 ".parallax__nav ul li a" 선택자에 해당하는 링크들을 배열로 가져옵니다.
  - gsap.to(): GSAP 라이브러리의 메서드로, DOM 요소를 애니메이션하는데 사용됩니다. 해당 메서드를 통해 커서의 위치를 사용자의 마우스 위치에 맞게 업데이트하는 기능이 구현되었습니다.
  - ScrollTrigger.create(): GSAP의 ScrollTrigger 플러그인을 사용하여 스크롤 이벤트를 관리하고, 특정 요소들을 트리거로 설정합니다. 이 코드에서는 ScrollTrigger를 사용하여 특정 요소들이 스크롤되면 특정 애니메이션 효과를 적용하도록 설정합니다.

<br><br>

-  구현 내역

- 이질감 효과
- 나타나기 효과
- Pin 애니메이션 / Pin 배경 고정
- 가로 효과
- 가로/세로 효과
- 스무스 효과
- 메뉴 이동
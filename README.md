# 로또
## 진행 방법
* 로또 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 문자열 계산기 기능 요구사항 
- [x]문자열을 입력을 ""로 할시 0을 반환한다.
- [x]쉼표(,) 을 구분자로 가지는 문자열을 전달하는 경우 합을 반환한다.
- [x]콜론(:) 을 구분자로 가지는 문자열을 전달하는 경우 합을 반환한다.
- [x]쉼표(,) 또는 콜론(:) 을 구분자로 가지는 문자열을 전달하는 경우 합을 반환한다.
- [x]앞의 기본 구분자(쉼표, 콜론) 외에 커스텀 구분자를 지정할 수 있다.
- [ ]커스텀 구분자는 문자열 앞부분의 “//”와 “\n” 사이에 위치히여 지정한다.
- [x]커스텀 구분자는 결과 값은 구분한 수의 합이 반환되어야 한다.
- [x]문자열 계산기에 숫자 이외의 값 또는 음수를 전달하는 경우 RuntimeException 예외를 throw 한다.

## 로또 기능 요구사항
로또 구입 금액을 입력하면 구입 금액에 해당하는 로또를 발급해야 한다.
로또 1장의 가격은 1000원이다.

추가된 요구 사항
모든 기능을 TDD로 구현해 단위 테스트가 존재해야 한다. 단, UI(System.out, System.in) 로직은 제외
핵심 로직을 구현하는 코드와 UI를 담당하는 로직을 구분한다.
UI 로직을 InputView, ResultView와 같은 클래스를 추가해 분리한다.
함수(또는 메서드)의 길이가 10라인을 넘어가지 않도록 구현한다.
함수(또는 메서드)가 한 가지 일만 하도록 최대한 작게 만들어라.
배열 대신 컬렉션을 사용한다.
Java Enum을 적용한다.
모든 원시 값과 문자열을 포장한다
줄여 쓰지 않는다(축약 금지).
일급 컬렉션을 쓴다.
과제 진행 요구 사항

힌트
로또 자동 생성은 Collections.shuffle()를 활용한다.
Collections.sort()를 활용해 정렬 가능하다.
ArrayList의 contains()를 활용하면 어떤 값이 존재하는지 유무를 판단할 수 있다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)
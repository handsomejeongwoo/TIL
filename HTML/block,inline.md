# 인라인태그,inline tag

- 자신의 내용과 앞뒤 태그의 내용을 같은 라인에 출력하는 태그
  <br/>

- 구성 요소 역할을 한다.(출력 내용 역할)
  <br/>

- 내용물의 크기가 태그의 영역이 된다.
  <br/>

## 특징

- 사용자 정의 영역을 표현

- 정해진 역할이 없음

- 인라인 태그+CSS, Javascript
- 태그로 지정한 범위만큼만 브라우저에 출력된다.
- 인라인 태그는 블록 태그를 포함할 수 없습니다. 강제로 구현은 되지만 사용하지 않는 것이 좋다.

# 블럭 태그, Block Tag

- 자신의 내용과 앞뒤 태그의 내용을 다른 라인에 출력하는 태그

- 자신의 내용만으로 한 라인을 독점해서 출력하는 태그(\*)

- 영역(구조)을 만들때 사용 > 컨테이너 역할 > 레이아웃 구성(틀 만들기)

- 내용물의 크기와 상관없이 너비는 항상 100%, 높이는 내용물의 크기에 맞춰 변화

## 특징

- 사용자 정의 영역을 표현

- 정해진 역할이 없음

- 블럭태그 +CSS, Javascript

- 블록 태그 HTML 블록 태그는 태그를 삽입할 경우 항상 새로운 줄에서 시작합니다. 태그 영역의 길이가 아무리 짧아도 새로운 블록 태그는 다음 줄에서 시작됩니다.

- 블록태그는 인라인 태그를 포함할 수 있다.

# 태그 중첩 규칙

1. 블럭 태그는 자식으로 또다른 블럭 태그 or 인라인 태그를 가질 수 있다.

2. 인라인태그는 자식으로 또다른 인라인태그만 올 수 있다.(블럭태그는 올 수 없다.)

3. 예외 블럭 태그 중 p 태그는 자식으로 인라인 태그만 가질 수 있다.

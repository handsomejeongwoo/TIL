# readonly 란

- 값의 속성을 읽기 전용으로 설정해주는 Typescript의 타입시스템 기능이다.
- 함수가 매개변수로 받는 값을 변경없이 그대로 사용해야할 때 적합하며
- 외부 클래스나 함수에서도 호출이 가능하지만 값의 변경은 불가능하므로 내부에서 미리 값을 초기화 해줘야한다.

# readonly가 필요한 이유

JS는 암묵적으로 매개변수를 변경하지 않는다고 가정한다. 하지만 이러한 방법은
항상 명확하게하지난 않기 때문에 readonly를 명시적으로 선언하는 것이 컴파일러와
코드를 읽는 사람에세 좋다.

# const 와 readonly의 차이

## Const

- 변수 참조를 위한 것이다.
- 벼수에 다른 값을 할당할 수 없다.

## readonly

- 속성을 위한 것이다.

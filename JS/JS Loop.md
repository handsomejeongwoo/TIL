# 반복문
     반복문은 비슷하거나 동일한 구문을 반복해서 수행할 수 있는 구문이다. 대표적인 반복문은 다음 두가지이며,
      두 반복문은 구조 및 동작방식에서 차이를 보인다.
<br/>

+ while문
<br/>

+ for문
<br/>

# while문 
    키워드를 while을 이용해 만드는 구문  while문은 '주어진 조건이 참일 동안에 구문을 반복하는' 반복문이다.
## while문 기본형태
    while(조건){
        //조건이 true인 동안에 반복 수행할 코드
    }

    => 조건이란 불리언을 반환하거나 불리언으로 해석될 수 있는 표현식!

    => 반복 구문은 '루프' 라고 한다.
<br/>

# while문 예시
    let number =1 //number함수를 선언 함수에 1저장

    //  numberrk 3보다 작은 동안에는 반복해라
    while(number < 3){
        console.log(number) //출력한 다음
        number += 1 //number를 1씩 증가
    }
<br/>

# for문
<br/>

## for문은 구문 작성시 반복을 위해 필요한 세가지 요소를 한 곳에 모아 작성함으로써 보다 명시적으로반복 횟수를 표현할 수있는 직관적인 구문이다.

<br/>
    for(초기식; 조건식; 반복식){
        // 조건이 true인 경우 반복 수행할 코드
    }
    =>초기식:반복 조건의 초기화 작업
    =>반복식: 반복이 한 번 끝날 때마다 실행될 작업
<br/>

# for문 사용해보기
    for(let i=0;i<=3;i+=1) //for(i변수 선언 0저장; i가 3보다 작거나 같을때까지 돌린다. ; i는 1씩 증가) {
        console.log(i) //i를 콘솔에 출력
    } //false를 반환 할때까지 조건문은 계속된다.

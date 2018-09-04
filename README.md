# Swift
Study Swift

// ==== 1. var 와 let 의 차이점에 대해 서술하고 예시 작성 ===============

  // var(variable) 변수 선언 키워드 / 변수 값은 변경 가능
  
  // let(constant) 상수 선언 키워드 / 상수 값은 변경 불가능
  
  
  // var, let 선언
  
  // var name: type = 값 or var name = 값 (값의 타입이 명확하면 타입 생략 가능)
  
  // let name: type = 값 or let name = 값 ("")
  
  
  // 예시
  
  // let myAge = 31    --> let myAge = 20 (X) 오류 발생
  
  // var year = 2018   --> var year = 2020 (O) 변경 가능
  
  
// ==== 2. Swift 에서 사용하는 정수와 실수 타입(Types)의 종류에 대해 아는 대로 나열하고 차이점을 작성 ====
  
  // ******* (1) 정수 Int(Integers) **********
  
  // +정수, 0, -음수
  
  // var year: Int = 2018
  
  
  // ******* (2) 실수 Double & Float (Floating Point Numbers) ********
  
  // 소수점 숫자 표현
  
  // let pie: Double = 3.14...
  
  // Double : 소수점 최소 15자리까지 / Float : 소수점 6자리까지
  
  // 두 타입의 차이는 표현 할 수 있는 소수점 최대자리의 차이
  
  // Float가 꼭 필요한 경우가 아니라면 Double을 권장
  

// ==== 3. Unicode 란? ================================================
  
  // 각 나라별 언어를 모두 표현하기 위한 코드 체계
  
  // 문자마다 고유한 코드값을 제공하는 새로운 개념의 코드
  
  // 모든 문자를 16비트로 표현하므로 최대 65,536자를 표현할 수 있다.
  
// ==== 4. 반복문(Loop)의 종류와 예시 코드 ======================================================
  
  // ******** (1) While Loop : 조건이 참이면 계속 반복, 조건이 거짓이 될 때 반복 정지 ***********
  
  // while <Condition> {
  
  //      <Loop Code>
        
  //        }
  
  // =============== *** Example *** ==================
  
  // var sum = 1
  
  //  while sum < 55 {
  
  //  sum = sum + (sum + 1)
  
  //  }
  
  // result : Loop 가 5번 실행되면 sum = 63이 되어서 false 가 되므로 반복 종료 
  
  // ===================================================
  
  // ******** (2) Repeat - While Loop : While Loop 의 변형. 조건이 루프의 시작점이 아닌 끝부분에서 평가 받는다는 것이 다른점이다 **********
  
  // repeat {

  //  <Loop Code>
  
  //  } while <Condition Code>
  
  // =============== *** Example *** =====================
  
  // var sum = 1
  
  // repeat {
  
  // var sum = 1
  
  // sum = sum + (sum + 1)
  
  // } while sum < 55
  
  // result : Loop 가 Loop 가 5번 실행되면 sum = 63이 되어서 false 가 되므로 반복 종료
  
  // !!!!! 이렇게 보면 While Loop 와 Repeat-While Loop 가 차이가 없어 보이지만 !!!!!
  
  // !!!!! condition 이 'sum < 1' 로 주어지면 while Loop 는 실행되지 않지만   !!!!!
 
  // !!!!! Repeat-while Loop 는 한번 실행되어 'sum = 3' 의 값을 가지게 된다.   !!!!!
  
  // !!!!! 이처럼 조건에 따라서 다른 결과를 가져올 수 있으므로 활용하기 나름.         !!!!! 
  
  
  
// ==== 5. 타입 추론(Type Inference)이란? ====================================================
  
  //
  
// ===== 6. 논리연산자(Boolean Logic) 인 AND(&&)와 OR(||) 로 나올 수 있는 각각의 4가지 경우의 수 작성 ====

  // let a = 2 > 1 && 5 < 6   ----> true
  // let b = 2 < 1 && 5 > 6   ----> false
  // let c = 1 == 2 || 4 > 3  ----> true
  // let d = 1 == 2 || 4 < 3  ----> false
  


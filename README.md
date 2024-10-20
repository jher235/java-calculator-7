# java-calculator-precourse

## 구현 기능 목록

### 기능 
- [x] 입력 받기
  - 시작 메세지를 출력한다. 
  - 클라이언트의 입력 값 받아오기 
- [x] 구분자 및 커스텀 구분자를 기준으로 숫자 분리
  - 기본 구분자는 쉼표(,)와 콜론(:)이며 커스텀 구분자는 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 지정한다.
  - 커스텀 구분자는 한 입력에 한번만 받을 수 있도록 한다. ex)//;\n//!\n은 안된다.
  - //and\n와 같이 단일 문자가 아니더라도 구분자로 등록할 수 있다.
- [x] 숫자 더한 뒤 반환해주기
  - 분리한 숫자들을 더한 뒤 결과 값을 반환한다.
- [x] 결과 출력
  - 계산한 결과를 출력한다.

### 입력 
 - 구분자와 양수로 구성된 문자열

### 출력
 - 구분자로 나눠진 숫자들을 더한 값.

### 예외
 - 숫자, 구분자, 지정한 커스텀 구분자 외에 값이 입력으로 들어온 경우. 
   - IllegalArgumentException 을 발생시킨 후 애플리케이션을 종료한다.


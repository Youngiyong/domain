#Springboot-practice 에서 사용하는 Enum, Entity, Converter 정의 

### enum 생성 규칙

## 테이블 상태, 타입 값

- 2개 이상의 값으로 구성된 컬럼의 경우 접미어는 “_flag”를 사용한다.
    - ex)point_flag
- true, flase 값으로 구성될 경우 접두어를 “is_”를 사용한다.
    - ex) is_main

  ![2](../images/2.png)
### ENUM

- enum 클래스의 접두어는 “E”로 시작한다.
- 단순값만 나열하는 클래스일 경우 접미어를 “Type”으로 사용한다.

  ex)TestType
  ![1](../images/1.png)

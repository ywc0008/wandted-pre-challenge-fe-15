# wandted-pre-challenge-fe-15

## 챌린지 과제

### Q1. 내가 생각하는 클린 코드란?

내가 적은 코드가 남들이 볼 떄 읽기 쉬운 코드

### Q2. 내가 생각하는 (프론트엔드에서의) 클린 코드란?

컴포넌트 단위로 파일들이 나눠져 있고, 그 해당 파일에 적절한 컴포넌트 코드들이 적혀져 있는 것.

### Q3. 내가 클린코드보다 중요하게 생각하는 것은?

동료들과 약속한 규칙. 동작 가능한 코드.


### Q4. 다음 중 선호하는 방식과 그 이유는?

##### 1.

`Tab` vs `Space`
Tab입니다. 한번에 들여쓰기를 맞춰줘서 편하기 때문에 선호합니다.

##### 2.

`세미콜론 O` vs `세미콜론 X`
세미콜론 0이지만 자동완성을 이용해서 적는 편입니다.

##### 3.

`count++;` vs `count += 1;` vs `count = count + 1;`
`count += 1;` 1을 다른 것으로 바꿀 수 있어서 더 유용하게 사용 가능하다고 생각합니다.

##### 4.

`if (isLogin) {}` vs `if (isLogin === true) {}`
`if (isLogin === true) {}` 더 명확하게 나타내서 선호합니다.

##### 5.

`isLogin && <HelloWanted />` vs `isLogin ? <HelloWanted /> : <></>` vs `isLogin ? <HelloWanted /> : null` vs `isLogin ? <HelloWanted /> : undfined`
`isLogin ? <HelloWanted /> : null`를 선호합니다. 조건문이 false일 때 빈 것을 나타내기 위해서 null을 쓰는 것을 선호하고, ?연산자를 쓰는것을 선호합니다.

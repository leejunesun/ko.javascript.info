
답: '1'
```js run
let i = 3;


}
```


반복이 하나씩 끝날 때마다 'i'는 '1'씩 줄어듭니다. 'While(i)'은'ㅑ = 0'일 떄 멈춥니다.

따라서 전체 반복문은 아래 순서를 따라 실행됩니다.
```js
let i = 3;


alert(i--); // 3이 출력되고 i는 2로 줄어듭니다.

alert(i--) // 2가 출력되고 i는 1로 줄어듭니다.

alert(i--) // 1이 출력되고 i는 0으로 줄어듭니다.

```i가 0이 되었기 떄문에 while(i)는 종료됩니다.


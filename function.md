## Js.prototype
---





 ### **Array**
 - 형태 : ['일','이','삼'];
- 형태 : [1, 2, 3];
- 호출 : 변수명, 변수명[0], 변수명[0][0], (변수명[index])

|내장함수 명|기능|
|:--:|:--:|
|.length|index 크기|
|.forEach|callback 호출(순환처리)|
|.map|모든 요소에 대해 콜백 함수 실행 후 반환|
|.filter|모든 요소에 대해 콜백 함수 실행 후 true 요소 반환|
|.push / pop| 추가/삭제|
|.slice|모든 배열 요소 추출 후 반환|
|.splice|배열의 기존 요소를 삭제 또는 교체 후 반환|
|.reduce|모든 요소를 하나의 값으로 줄이기 위해 두개의 인수를 전달받는 콜백|
|.join|모든 요소 하나의 문자열 변경|
|.indexOf|첫 인덱스와 교체 반환|
|.lastindexOf|마지막 인덱스와 교체 반환|
|.includes|배열이 특정 요소 포함하고 있는지 판별|
|.find|전달 받은 함수와 같은 배열 요소 반환 false 경우 undefined 반환|
|.concat|해당 배열 뒤 전달 받은 배열 합침|
|.every|모든 요소 콜백함수 실행 후 전부 true 경우에만 true 반환|
|.some|모든 요소 콜백 함수 실행 후 하나라도 true면 true 반환|
|.fill|모든 배열 특정 값 변경|
|.shift|첫 요소 제거(총 길이변경)|
|.unshift| 첫 요소 추가 (총 길이변경)|
|.reverse| 배열역순 |
|.sort| 정렬(알파벳순)|

### **String**
- 형태 :'abcde', "abcde", `abced`;
- 호출 : 변수명, 변수명[0], (변수명[index])

|내장함수 명|기능|
|:--:|:--:|
|str.lenght|문자열 길이 반환|
|str.indexOf| 특정 문자나 문자열이 처음으로 등장하는 위치 반환|
|str.lastIndex|특정 문자나 문자열이 마지막으로 등장하는 위치 반환|
|str.includes|전달 받은 문자열이 포함되어 있는지 확인 후 bool 반환|
|str.split|전달 받은 구분자를 기준, 나눈 후 반환|
|str.substring|전달받은 인자의 시작, 종료 인덱스 바로 앞까지 문자열 추출 반환|
|str.substr|전달받은 인자의 시작, 종료 인덱스 바로 앞까지 문자열 추출 반환|
|str.toLowerCase|문자열 소문자 반환|
|str.toUpperCase|문자열 대문자 반환|
|str.trim|문자열 주위 공백 제거|
|str.math|--|
|str.replace|문자열을 검색 후 변경|
|str.concat|문자열 결합 후 반환|
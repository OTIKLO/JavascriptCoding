# JavascriptCoding
자바스크립트 관련 코드 모음

## 수학

#### Math.max()
최대값구하기
```javascript
//최대값 구하고 그 최대값의 인덱스 가져오는 예시
let max = Math.max(...array);
return [max, array.indexOf(max)];
```

#### Math.min()
최솟값 구하기

#### Math.ceil(x)
입력받은 숫자보다 크거나 같은 정수 중 가장 작은 정수를 리턴합니다.

#### Math.floor(x)
입력받은 숫자보다 작거나 같은 정수 중 가장 큰 정수를 리턴합니다.

#### Math.round(x)
소수점 이하의 값이 0.5보다 크면, 입력받은 수보다 다음으로 높은 절대값을 가지는 정수를 리턴합니다.

소수점 이하의 값이 0.5보다 작으면, 입력받은 수보다 절대값이 더 낮은 정수를 리턴합니다.

소수점 이하의 값이 0.5와 같으면, 입력받은 수보다 큰 다음 정수를 리턴합니다.

#### Math.pow(x, y)
x=밑 y=지수  toFixed()로 거듭 제곱 반올림

## 문자열

#### includes
  특정 문자열이 존재하면 true를 반환하며, 존재하지 않으면 false를 반환합니다.
```javascript
str.includes(searchString[, position])
```
+ searchString

  검색하고자 하는 문자열

+ position

  검색 시작 위치
  
#### indexOf
  indexOf 함수는 특정 문자열이 존재하면 첫 번째 index를 반환하며, 존재하지 않으면 -1을 반환합니다.
```javascript
str.indexOf(searchValue[, fromIndex])
```

+ searchValue

  검색하고자 하는 문자열입니다.

+ fromIndex

  검색 시작 위치

  매개변수의 값이 문자열의 길이(str.length)보다 크거나 같다면, 문자열을 검색하지 않고 -1을 반환
  
## 배열

push(): 배열의 마지막에 새로운 요소를 추가한 후, 변경된 배열의 길이를 반환
```javascript
array.push();
```

pop(): 배열의 마지막 요소를 제거한 후, 제거한 요소를 반환
```javascript
array.pop();
```

#### sort()
배열 오름차순, 내림차순
```javascript
array.sort()
```
숫자 오름차순, 내림차순
```javascript
arr.sort((a, b) => a - b);
arr.sort((a, b) => b - a);
```

# 문자열 라이브러리

## 문자열 관련 함수
str.length() -> 문자열의 길이를 구해줌 <br>
str.size() -> 해당 객체가 차지하는 메모리의 크기를 반환함 <br>
**C++에서은 '\0' 문자가 붙지 않는다.**

str.empty -> 문자열이 비었는지 아닌지를 검사<br>
str.append("추가할 문자열") -> 문자열의 끝에 새로운 문자열을 추가<br>
str.find(str) -> 원하는 문자열의 시작 위치를 알려준다. 찾지 못한다면, string::npos라는 상수를 반환한다.
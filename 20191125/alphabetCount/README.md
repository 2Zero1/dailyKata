# 문제 : 문자열 내 p와 y의 개수

1. 이해
    - s : 문자열 변수, 길이는 50이하의 자연수
    - answer : p와 y의 개수가 같으면 true, 다르면 false.

2. 계획
    - 전략 1
        - 대문자 또는 소문자로 변경하여 하나만 계산한다.
        - 문자열 s를 순회하면서 p와 y의 개수를 각각 센다.
        - 같은지 확인한다.
    - 전략 2
        - 대문자 또는 소문자로 변경하여 하나만 계산한다
        - 정수 배열을 0으로 초기화 하여, 문자열 s를 순회하면서 p가 나오면 +1, y나오면 -1
        - 결과값이 0이라면, 개수가 동일하므로 true, 이외엔 false
    - 전략 3
        - 정규 표현식을 사용하여, p와 y의 값을 구하고, 길이를 확인하여
        - 같으면 true, 이외엔 false
3. 실행
4. 반성.
    - 나중에 특정 알파벳의 개수를 센다면, match를 사용할 수 있다.
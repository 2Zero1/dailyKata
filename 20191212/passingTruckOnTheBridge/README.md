# 문제 : 다리를 지나는 트럭

## How To Solve

1. 이해
    - bridge_length : 다리의 길이
    - weight : 다리가 버틸 수 있는 최대 무게
    - truck_weights : 지나갈 트럭들의 무게
    - 트럭은 1초에 1만큼 움직임
    - 구해야 하는것 : 모든 트럭이 건너기 위해 최소로 걸리는 시간.
2. 계획
    - 매 초마다 현재 다리에 있는 모든 트럭의 무게를 확인하여, 다음 트럭이 들어갈 수 있는지 확인
        - 들어갈 수 있다면 다리에 들어감
        - 들어갈 수 없다면 패스
    - 위를 진행하면서 현재 트럭이 다리에 들어온 후의 시간을 증가시키며, 다리의 길이를 확인하여 나갈 수 있는지 확인하고 내보내준다.
    - 위의 것을 반복하고, 현재 다리 안에 or 아직 다리에 들어오지 못한 버스가 존재하다면, for문을 진행하고
    - 없다면 현재 count를 리턴한다.
3. 실행
4. 회고
    - 문제를 잘 쪼개지 못했다.
    - 테스트를 쪼개서 접근을 했지만, 아주 작게 만들었음에도 불구하고, 쪼개기 전의 테스트를 통과시키기 위한 코드를 다 넣어야 테스트를 통과시킬 수 있었음.
    - 어떻게 하면 문제를 테스트를 더 짧은 주기로 통과하는 테스트코드를 짤 수 있을까 ?
    - 어려운 문제가 나온다면, 필요로 하는 각각의 기능을 위한 테스트를 의도적으로 만들어줘야하는가 ? 고민 해봐야할것같다.



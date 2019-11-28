2019-11-28 구현할 기능 목록 정리
* Game
    * 게임의 모든 기능을 수행하는 클래스
    * 필드:
        1) 컴퓨터
        2) 플레이어
        3) 스트라이크 카운트
        4) 볼 카운트
    * 메소드:
        1) 게임 시작
        2) 컴퓨터와 플레이어의 숫자 비교
        3) 힌트 출력
        4) 게임 재개
     
* Computer
    * 상대방 클래스
    * 필드:
        1) 서로 다른 수로 이루어진 3자리의 수
    * 메소드:
        1) 랜덤으로 수 생성
        2) 리스트에 랜덤 수 넣기(추가)

* Player
    * 사용자에게 수를 입력받는 클래스
    * 필드:
        1) 서로 다른 수로 이루어진 3자리의 수
    * 메소드:
        1) 숫자 입력 받기
        2) 입력 받은 숫자의 길이 검사
        3) 입력 받은 숫자의 유효성 검사

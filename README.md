# melon-playlist
멜론 플레이리스트 예측 모델

## 프로젝트 소개
* 대회 정보 : https://dacon.io/competitions/official/235583/overview/
* 데이터 출처 : https://github.com/Blizzard/s2client-proto#downloads
* 대회에서 제공하는 데이터는 게임 플레이어의 행동 정보를 담고 있습니다. 이 데이터를 사용하여 게임에서 승리하는 선수를 예측합니다. 데이터는 5만여 개의 경기 리플레이 데이터로 이루어져 있으며, 각 리플레이 데이터는 총 경기 시간의 일부에 대한 인게임 정보를 포함합니다.

## Data
### train.csv / test.csv
* game_id : 경기 구분 기호
* winner : player 1의 승리 확률
* time : 경기 시간, 마침표(.)로 분과 초가 구분됩니다. ex) 2.24 = 2분 24초
* player : 선수
    - 0: player 0
    - 1: player 1
* species : 종족
    - T: 테란
    - P: 프로토스
    - Z: 저그
* event : 행동 종류
* event_contents : 행동 상세
    - Ability : 생산, 공격 등 선수의 주요 행동
    - AddToControlGroup : 부대에 추가
    - Camera : 시점 선택
    - ControlGroup : 부대 행동
    - GetControlGroup : 부대 불러오기
    - Right Click : 마우스 우클릭
    - Selection : 객체 선택
    - SetControlGroup : 부대 지정
### sample_submission.csv
* game_id : 경기 구분 기호
* winner : player 1의 승리 확률

## Environmnent
python 3.7 / windows 10 / ram 8gb / i5-8300h / gtx 1050


## Library

## References
https://sujinlee.me/professional-github/
https://www.bigcontest.or.kr/points/content.php#ct02

## 넣어야 할 것들
사용 예제, 개발 환경 설정 방법, 기여 방법, 변경 로그, 라이센스 및 작성자 정보

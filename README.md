# melon-playlist
* 목표 : 플레이리스트에 수록된 곡과 태그의 절반 또는 전부가 숨겨져 있을 때 주어지지 않은 곡들과 태그를 예측
* 기대 효과 : 예측 모델을 만든다면, 플레이리스트에 들어있는 곡이 주어졌을 때 이 모델이 해당 플레이리스트와 어울리는 곡들을 추천

## 프로젝트 소개
* 대회 정보 : https://arena.kakao.com/c/7
* 데이터 출처 : https://arena.kakao.com/c/7/data
* 대회에서 제공하는 데이터는 멜론 서비스에서 수집된 플레이리스트의 일부분입니다.

## Data
### 플레이리스트 메타데이터(train, val)
* 플레이리스트 제목
* 플레이리스트에 수록된 곡
* 플레이리스트에 달려있는 태그 목록
* 플레이리스트 좋아요 수
* 플레이리스트가 최종 수정된 시각
### 곡 메타데이터(song_meta)
* 곡 제목
* 앨범 제목
* 아티스트명
* 장르
* 발매일

## Environmnent
Python 3.7 / Windows 10 / / RAM 32gb / GTX 1050 Ti

## Library
* Tensorflow gpu 2.0 

## Model
* Autoencoder

## References
* https://github.com/Ikaroshu/movie_recommendation_engine/blob/master/Denoising_Autoencoder.ipynb
* https://arena.kakao.com/forum/topics/191

## 넣어야 할 것들
사용 예제, 개발 환경 설정 방법, 기여 방법, 변경 로그, 라이센스 및 작성자 정보

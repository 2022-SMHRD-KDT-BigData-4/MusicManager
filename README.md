# MusicManager(팀명: MP6)
![MusicManager_MP6](https://user-images.githubusercontent.com/104408853/182769205-264e3823-c067-4578-9be2-2bcd20e6dbaf.png)


## 1. 프로젝트명 : MusicManager
* 프로젝트 주제 : 사용자 음성 분석을 통한 노래방 선곡 추천 서비스
* 서비스 설명 : 사용자가 노래를 부르고 녹음하면, 음성 데이터 분석을 통해 노래의 장르와 사용자의 음역대를 예측하여 유사한 노래를 선곡할 수 있도록 맞춤 추천해주는 서비스.

## 2. 주요기능
* 장르 분석 기능 : 음원 데이터를 분석하여 특성 데이터를 추출 및 학습한 후, 음성 데이터를 입력하면 장르를 예측해주는 기능을 제공.
* 음역대 분석 기능 : 음원 데이터를 분리하여 보컬 데이터를 추출 후 음역대를 분석하여, 음성 데이터를 입력하면 사용자의 음역대를 예측해주는 기능을 제공.
* 선곡 추천 기능 : 사용자의 음성 데이터를 분석하여 노래의 장르와 음역대를 예측, 분석 결과를 종합하여 맞춤 선곡을 추천해주는 서비스를 제공.
* 분석 결과 저장 기능 : 사용자가 로그인을 하면, 최근 분석 결과를 리스트에 저장하여 사용자가 추후 다시 확인하거나 삭제할 수 있도록 함. 또한, 사용자는 유튜브 링크를 제공받아 노래를 듣고 연습할 수 있도록 하는 서비스를 제공.
* 추가 가능성 - 가사를 분석하여 유사한 분위기의 선곡을 추천하는 기능(미구현), 사용자가 추천받은 노래를 자신만의 플레이리스트에 저장하는 즐겨찾기 기능(미구현)

## 3. 개발환경
|구분|내용|
|------|---|
|사용언어|Java, HTML, CSS, JavaScript, Python|
|사용한 라이브러리| Pytube, Selenium, BeautifulSoup / Librosa, Spleeter, DBSCAN, praat-parselmouth |
|개발도구|Eclipse, VisualStudioCode, Jupyter, Colab, Spring Framework|
|서버환경|tomcat, AWS, Flask, Ubuntu|
|데이터베이스|MySQL|
|인공지능|tensorflow, DNN|

## 4. 아키텍처(구조)
![서비스아키텍쳐_MP6](https://user-images.githubusercontent.com/104408853/188761266-db05962e-83e5-4a11-9b3c-313a5fadfd64.png)



## 5. 기능 흐름도
### 서비스 흐름도(유스케이스)
#### SW 유스케이스
![유스케이스_MP6](https://user-images.githubusercontent.com/104408853/184092074-8c0a0e3c-ae3a-4454-891f-fbcbfad5bf0b.png)
#### 서비스 흐름도(웹 화면설계서)
![서비스흐름도_MP6](https://user-images.githubusercontent.com/104408853/184091761-7e05d68f-98ad-4326-9534-8cacccfa679e.png)
#### ER 다이어그램
![ER다이어그램_MP6](https://user-images.githubusercontent.com/104408853/184091893-1f6cfb3f-10da-4490-b87c-f8c2b24a45d0.png)

## 6. 동작 화면

### 로그인/회원가입/회원정보 수정
![로그인/회원가입/회원정보수정_MP6](https://user-images.githubusercontent.com/104408853/184093721-f9ec4482-2f6d-4ee7-8989-ab950e6ea885.png)

### 메인/상단 메뉴바(비로그인/로그인)/최근 분석 결과(로그인 시에만 활성화)
![메인/메뉴바/결과누적_MP6](https://user-images.githubusercontent.com/104408853/184094732-c26a2773-1710-4592-9747-e99934e2ea44.png)

### 녹음/녹음 완료/분석 결과
![녹음및분석_MP6](https://user-images.githubusercontent.com/104408853/184095560-4a2a8d46-03d5-429c-bd8c-1fc22f6a7dcf.png)

## 7. 제작 일정
![개발일정_MP6](https://user-images.githubusercontent.com/104408853/184096114-ae880633-eb59-4429-8328-411b827bd6e4.png)

## 8. 팀원 단위 업무 분장 및 결과표
![팀원소개_MP6](https://user-images.githubusercontent.com/104408853/184097230-63db25b7-648e-450f-aeee-1304278ed885.png)

## 9. 트러블슈팅
* 문제1<br>
 DNN 모델 사용 중 optimizer, activation 속성 수정 및 dropout 사용까지 시도했음에도 loss가 높고 과적합이 발생하는 문제를 겪음. -> 음원 데이터 특성에 관한 scatter 그래프를 시각화하여 label간의 중복되는 특성을 확인할 수 있었음, 이후 데이터 수집 및 전처리 과정을 다시 거쳐 상기 문제를 해결할 수 있었음.


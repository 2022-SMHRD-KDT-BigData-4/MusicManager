# MusicManager(팀명: MP6)
![MusicManager_MP6](https://user-images.githubusercontent.com/104408853/182769205-264e3823-c067-4578-9be2-2bcd20e6dbaf.png)


## 1. 프로젝트명 : MusicManager
* 프로젝트 주제 : 사용자 음성 분석을 통한 노래방 선곡 추천 서비스
* 서비스 설명 : 사용자가 노래를 부르고 녹음하면, 녹음된 데이터를 분석하여 노래의 장르와 사용자의 음역대를 분석하여 유사한 노래를 선곡할 수 있도록 추천해주는 서비스.

## 2. 주요기능
* 전문가 상담 서비스 : 사용자가 전문가 전문가 상담 메인 페이지에서 전문가 정보를 확인하고 선택하면, 전문가가 작성한 상세한 상담 정보를 확인할 수 있음. 1회 상담 또는 정기 상담을 선택하면, 채팅을 통해 1:1 상담이 이루어져 관상어에 대한 전문적인 조언을 얻을 수 있음. 상담 후에는 후기글을 작성하여 다른 사용자들과 경험을 공유할 수 있음.
* 장르 분석 기능 : 
* 음역대 분석 기능 : 
* 분석 결과 저장 기능 : 사용자가 로그인을 하면, 최근 분석 결과를 리스트에 저장하여 사용자가 추후 확인할 수 있도록 
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
![서비스아키텍처_아쿠아맨](https://user-images.githubusercontent.com/104408853/171079995-97d3bd63-20a8-42ad-97ca-5c2d2cf8b9e4.png)


## 5. 기능 흐름도
### 서비스 흐름도(유스케이스)
#### SW 유스케이스
![유스케이스_아쿠아맨](https://user-images.githubusercontent.com/104408853/170604777-f58a29b7-3a5a-47a1-b381-f2f5b8e9e3a5.png)
#### 서비스 흐름도(웹 화면설계서)
![서비스흐름도_아쿠아맨](https://user-images.githubusercontent.com/104408853/170604757-07fcb8f1-6528-4f07-adbf-218b32ce147d.png)
#### ER 다이어그램
![ER다이어그램_아쿠아맨](https://user-images.githubusercontent.com/104408853/170604797-942244a1-9074-4194-9809-582d990a23c6.png)

## 6 SW 동작 화면

### 일반 회원가입/전문가 회원가입/전문가 자격증명/로그인
![회원가입 및 로그인_아쿠아맨](https://user-images.githubusercontent.com/104408853/171081685-f0b349c9-e0aa-4618-a391-f634d4b5d9fb.png)

### 메인페이지(배너, 서비스 프로세스, FQA, 후기 게시판 홍보, 박람회 홍보, 팀원 소개)
![메인페이지정리_아쿠아맨](https://user-images.githubusercontent.com/104408853/170897885-84f71494-b5be-43e0-a6b4-e1b908f0903f.png)

### 전문가 정보 확인/상담 상세 정보 확인/1:1 채팅 상담
![전문가상담_아쿠아맨](https://user-images.githubusercontent.com/104408853/170604438-58b3537c-f446-460d-943f-72e69bfdd202.png)

### 관상어 백과 메인/관상어 상세 정보
![관상어백과_아쿠아맨](https://user-images.githubusercontent.com/104408853/170898474-0b155cde-6323-4421-94af-35c4a952e097.png)

### 후기 게시판
![후기게시판_아쿠아맨](https://user-images.githubusercontent.com/104408853/171081144-a31f3568-d7a3-44b7-a314-c4630b1eb3ae.png)


## 7 제작 일정
![프로젝트 일정_아쿠아맨](https://user-images.githubusercontent.com/104408853/170604975-f8566df0-5865-4387-bf17-ed637fc097d4.png)

## 8 팀원 단위 업무 분장 및 결과표
![팀원소개_아쿠아맨](https://user-images.githubusercontent.com/104408853/170604959-b7173905-5155-4ed4-af11-3db488e17a72.png)

## 9 트러블슈팅
* 문제1<br>
 프로젝트 개발 중 모르는 부분을 검색하였을 때, 현재 상황에는 적합하지 않은 정보들이 많이 나왔음. -> 팀원들과의 소통을 통해 경험과 정보를 공유하여 많은 부분을 해결할 수 있었음.
 
* 문제2<br>
 팀원들과 서로 생각하는 화면 구성이 달라 소통에 어려움을 겪음. -> Figma를 사용, UI를 팀원 모두가 함께 제작하고 공유해서 화면 구성을 통일하고 소통을 원활화할 수 있었음.


# KIS_documents
2023-1학기 창의설계프로젝트 관련 Document <br/>
최종 보고서: [link](https://github.com/StupidTalkingPotatoes/KIS_documents/blob/main/%EA%B2%B0%EA%B3%BC%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)

### 팀원 구성
|구분|학년|학번|이름|
|---|---|---|---|
|팀장|4|20180637|신예찬|
|팀원|4|20200158|김미령|
|팀원|4|20200370|김혜진|
|팀원|4|20200639|신승미|

### 목차
1. [시스템 구성도](#시스템-구성도)
2. [설계 문서](#설계)
3. [결과 화면](#결과-화면)
4. [논문](#논문)

# 시스템 구성도
![system_diagram](https://github.com/StupidTalkingPotatoes/KIS_documents/blob/main/%EC%8B%9C%EC%8A%A4%ED%85%9C%20%EA%B5%AC%EC%84%B1%EB%8F%84.png)

# 설계

## Usecase
### 1. 실시간 도착 정보 조회
1. 사용자는 버스 도착 정보를 조회할 구미시의 정류장에 대해 정류장명 또는 정류장 번호 중에 선택한다.
2. 사용자는 검색할 키워드를 입력한 후 검색 버튼을 누른다.
3. 웹 서비스는 검색 결과에 맞는 정류장 목록을 보여준다.
4. 사용자는 도착 정보를 조회할 정류장을 선택한다.
5. 웹 서비스는 해당 정류장에 대한 실시간 버스 도착 정보(노선 번호, 남은 시간, 남은 정류장 수)을 사용자에게 보여준다.
### 2. 실시간 위치 정보 조회
1. 사용자는 버스 노선 번호를 입력하고 검색 버튼을 누른다.
2. 웹 서비스는 검색한 키워드가 포함된 버스 노선 번호와 방면 목록을 보여준다.
3. 사용자는 위치 정보를 조회할 노선을 선택한다.
4. 웹 서비스는 해당하는 노선의 현재 버스의 위치를 사용자에게 보여준다.
### 3. 경로 탐색
1. 사용자는 출발지와 도착지를 입력하고 정확한 장소에 대해 선택한다.
2. 웹 서비스는 도보와 버스로 갈 수 있는 경로를 사용자에게 보여준다.
### 4. 주변 정류장 정보 조회
1. 웹 서비스는 사용자의 위치를 중심으로 하여 반경 500m 내의 정류장을 보여준다.

## Sequence Diagram
![sequence_diagram](https://github.com/StupidTalkingPotatoes/KIS_documents/blob/main/%EC%8B%9C%ED%80%80%EC%8A%A4%20%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8/(%EC%B5%9C%EC%A2%85)sequence_diagram.jpg)

## API
API Document 및 목업 서버 사용 안내: [link](https://documenter.getpostman.com/view/15047765/2s93ebTr39)

# 결과 화면
### 메인 화면
![main](https://github.com/StupidTalkingPotatoes/KIS_documents/blob/main/%EA%B5%AC%ED%98%84%20%EA%B2%B0%EA%B3%BC%20%EC%82%AC%EC%A7%84/1-%EB%A9%94%EC%9D%B8%ED%99%94%EB%A9%B4.png)
### 실시간 버스 도착 정보 조회 화면
![realtime-bus-arrival](https://github.com/StupidTalkingPotatoes/KIS_documents/blob/main/%EA%B5%AC%ED%98%84%20%EA%B2%B0%EA%B3%BC%20%EC%82%AC%EC%A7%84/4-%EC%8B%A4%EC%8B%9C%EA%B0%84%EB%8F%84%EC%B0%A9%EC%A0%95%EB%B3%B4%EA%B2%B0%EA%B3%BC2.png)
### 실시간 버스 위치 정보 조회 화면
![realtime-bus-location](https://github.com/StupidTalkingPotatoes/KIS_documents/blob/main/%EA%B5%AC%ED%98%84%20%EA%B2%B0%EA%B3%BC%20%EC%82%AC%EC%A7%84/7-%EC%8B%A4%EC%8B%9C%EA%B0%84%EC%9C%84%EC%B9%98%EC%A0%95%EB%B3%B4%EA%B2%B0%EA%B3%BC.png)
### 경로 탐색 화면
![path](https://github.com/StupidTalkingPotatoes/KIS_documents/blob/main/%EA%B5%AC%ED%98%84%20%EA%B2%B0%EA%B3%BC%20%EC%82%AC%EC%A7%84/9-%EA%B2%BD%EB%A1%9C%ED%83%90%EC%83%89%EA%B2%B0%EA%B3%BC.png)

# 논문
제목: 2023 한국정보기술학회 하계 종합학술대회 논문집 - 교통약자를 위한 TAGO API 기반 저상버스 정보 시스템 </br>
날짜: 2023.06.01 </br>
저자: 김미령, 김혜진, 신승미, 신예찬, 오병우 </br>
논문 보기: [Click](https://github.com/StupidTalkingPotatoes/Documents/blob/main/%EB%85%BC%EB%AC%B8/(%EC%A0%9C%EC%B6%9C%EB%B3%B8)%EA%B5%90%ED%86%B5%EC%95%BD%EC%9E%90%EB%A5%BC%20%EC%9C%84%ED%95%9C%20TAGO%20API%20%EA%B8%B0%EB%B0%98%20%EC%A0%80%EC%83%81%EB%B2%84%EC%8A%A4%20%EC%A0%95%EB%B3%B4%20%EC%8B%9C%EC%8A%A4%ED%85%9C.pdf)


# 탕후루 만들기 (Tanghulu Maker)
탕후루 만들기는 ‘애니팡’, ‘캔디크러쉬’와 같은 3-match 게임의 법칙을 따르는 퍼즐게임입니다.<br/>
원하는 방향으로 직선을 그어 없앨 수 있는 차별점을 주었습니다.<br/>
게임 로직에 따라 ‘오리지널 모드’와 ‘중력 모드’로 나뉩니다.
<br/>
## 다운로드
### [APPSTORE](https://apps.apple.com/us/app/tanghulu-maker/id6469285136) <br/>
### [GOOGLEPLAY](https://play.google.com/store/apps/details?id=com.GorabiStudio.TanghuluMaker)
<br/>

## 게임 설명
### 홈 화면
<img src=https://github.com/Eenrue/Eenrue/assets/128016413/1ff86753-9de4-4c68-93b1-e62e81145042 width="200" height="400"/>

<br/>

#### 버튼 설명
1. 배경 탕후루 전환 버튼
2. 음소거 버튼
3. 플레이 버튼
4. 모드 전환 버튼
5. 최고기록 표시(클릭하면 축하 이벤트)
6. 스틱 버튼 (인게임 이펙트 기능)
#### 화면 모션
1. 탕후루가 위 아래로 진자 운동을 진행 (용수철 함수 사용)
2. 눈이 지속적으로 움직이는 모션 (중력모드의 경우 아래로, 오리지널 모드의 경우 배경이 움직이는 방향으로)

### 스틱 화면
<img src=https://github.com/Eenrue/Eenrue/assets/128016413/4cab1a95-fead-4004-b642-7d6d62600167 width="200" height="400"/>
<br/>
각 스틱마다 인게임에서 과일들이 없어지는 이펙트가 바뀝니다.
<br/>
스틱을 얻는 조건은 중력모드로 특정 기준 점수 이상 도달해야 합니다.

### 게임 기본 규칙
<img src=https://github.com/Eenrue/Eenrue/assets/128016413/27cf260e-58e3-4919-b7d3-8394eec530d5 width="200" height="400"/>
<br/>
3개 이상의 동일한 N개의 과일들을 고르면 개수에 비례하는 2*N-3의 점수를 얻습니다

### 오리지널 모드
<img src=https://github.com/Eenrue/Eenrue/assets/128016413/37eca8ef-b3c2-49ca-bd94-cad486cefd0e width="200" height="400"/>
<br/>
60초의 시간제한 내에 최대한 많이 점수를 얻는 방식입니다.
<br/>
기존의 3-match 게임과는 다르게 과일들이 없어지면, 그 후로 다시 생기지 않습니다.
<br/>
이로 인해 전략적인 플레이가 가능해집니다.

### 중력 모드
<img src=https://github.com/Eenrue/Eenrue/assets/128016413/902be9b6-6def-4484-8f7e-84f3a5c03e3c width="200" height="400"/>
<br/>
제한시간이 없으며, 과일들이 모두 쌓이기 전에 최대한 빠르게 점수를 얻는 방식입니다.
<br/>
지속적으로 하늘에서 과일들이 떨어지며, 시간이 갈 수록 속도는 빨라집니다.

### 설정 화면
<img src=https://github.com/Eenrue/Eenrue/assets/128016413/65631ab9-da1f-4ff3-96c1-4ae737077c75 width="200" height="400"/>
<br/>
최고기록과 현재기록을 보여주며, 게임 설명을 확인할 수 있는 버튼과, 음소거 버튼이 있습니다.
<br/>
홈 화면 버튼, 재생하기 버튼, 재시작 버튼이 위치해있습니다.

## 디자인
스틱으로 인한 FX 이펙트 디자인과 폰트의 경우 UNITY ASSET을 이용했습니다.
<br/>
#### 이를 제외한 모든 버튼, 과일, 제목, 배경, 화면, 아이콘 등 디자인은 모두 Procreate를 통해서 픽셀아트를 스스로 제작하였습니다.

<br/>

## 🛠 관련기술
#### UNITY, C#, Admob

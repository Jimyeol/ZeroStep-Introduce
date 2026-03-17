# 타일 디자인 상세 요청서

## 📌 타일 디자인 공통 필수 사항
* **중앙 숫자 표시:** 기본적으로 모든 타일의 정중앙에는 텍스트(숫자)가 들어갈 공간이 있어야 합니다.
* 게임 플레이 중 숫자가 계속 바뀌므로, 배경 이펙트나 아이콘이 화려하더라도 중앙의 숫자가 가장 또렷하게 보여야 합니다. (단, Blackout 등 일부 정보가 가려지는 타일은 숫자 대신 `?`나 숨김 아이콘이 들어갑니다.)

## 📌 타일별 상세 특징 (총 9종)

### 1. Normal (기본 타일)
* 가장 기본이 되는 네모난 네온 숫자 타일입니다.
* 숫자에 따라 색상이 변하므로(ex. 1: 하늘색, 2~3: 민트, 4 이상: 마젠타), 너무 화려하지 않고 특수 타일들을 돋보이게 해주는 깔끔한 기준 톤이어야 합니다.

<img src="./normal.png" alt="Normal tile" width="260" />

### 2. CrossBlast (십자 폭발 타일)
* 인접한 상하좌우 4방향으로 타일의 Count를 -1 감소시키는 타일입니다.

<img src="./CrossBlast.png" alt="CrossBlast tile" width="260" />

### 3. ShortCircuit (방향 제한 타일)
* 정해진 방향으로만 이동할 수 있는 타일입니다.

<img src="./ShortCircuit.png" alt="ShortCircuit tile" width="260" />

### 4. Blackout (정보 숨김 타일)
* 숫자를 가리고 `가림` 로 표시되는 타일입니다.

<img src="./Blackout.png" alt="Blackout tile" width="260" />

### 5. Hidden (숨겨진 타일)
* 처음엔 비활성화되어 있다가 나중에 켜지는 타일입니다.

<img src="./Hidden-Igniter.png" alt="Hidden tile concept" width="260" />

### 6. Igniter (점화/스위치 타일)
* 밟으면 'Hidden 타일'을 작동시키는 스위치입니다.

<img src="./Hidden-Igniter.png" alt="Igniter tile concept" width="260" />

### 7. BlindCurtain (블라인드 타일)
* 밟으면 보드 전체의 숫자를 `?`로 가려버립니다.

<img src="./BlindCurtain.png" alt="BlindCurtain tile" width="260" />

### 8. FixedKnot (순서 잠금 타일)
* 반드시 '특정 순서'에만 밟아야 하는 기계적 잠금장치 타일입니다.

<img src="./FixedKnot.png" alt="FixedKnot tile" width="260" />

### 9. TwinLink (동기화 짝궁 타일)
* 서로 떨어져 있어도 하나의 쌍으로 연결된 타일입니다.

<img src="./TwinLink.png" alt="TwinLink tile" width="260" />

## 시연 영상

<video src="./play2.mp4" controls width="360"></video>

[영상 파일 열기](./play2.mp4)

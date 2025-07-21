# 김태연의 혼 프로젝트
'김태연의 혼 프로젝트'

제 친구인 '김태연' 이라는 소재와, 근처에 유명한 공포 방탈출인 '혼' 이라는 소재를 가지고 와서
만드는 첫 유니티 2D게임(쯔꾸르) 입니다.
게임에 나오는 맵 타일셋은 https://indiside.com/openforum_pdsg/1461744 케이디님의 작품을 이용했습니다.

<br>

## 제작 과정
### 충돌 구현
<div align="left">
  <img src="https://github.com/MiruHeon/Normal-Project/blob/main/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%201.png?raw=true" style="width: 300px;">
</div>
플레이어의 이동과 장애물 충동 구현은 rigidbody2d와 boxcollider2d 컴포넌트를 이용하여 충돌 이벤트를 구현했습니다.

### 이동 에니메이션 구현
<div align="left">
  <img src="https://github.com/MiruHeon/Normal-Project/blob/main/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%202.png?raw=true" style="width: 300px;">
</div>
플레이어 이동 에니메이션은 animator 컴포넌트를 이용해서 구현했습니다.

### 김태연의 캐릭터 칩셋

<div align="left">
  <img src="https://github.com/MiruHeon/Normal-Project/blob/main/KimTaeYeon.png?raw=true" alt="이미지" style="width: 300px;">
</div>
그림판과 도트 툴을 이용하여 제작했습니다.


### 카메라 이동 구현
<div align="left">
  <img src="https://github.com/MiruHeon/Normal-Project/blob/main/lerp%20%ED%95%A8%EC%88%98%20%EC%82%AC%EC%9A%A9.png?raw=true" style="width: 300px;">
</div>
카메라의 이동은 Lerp 함수 (시작값:끝값:이동값)을 이용하여 구현했습니다.

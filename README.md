<img width="305" height="312" alt="image" src="https://github.com/user-attachments/assets/6656a18b-b6be-4fb4-9288-36a2585f7ffc" /># 1.프로젝트 개요
프로젝트 제목 : 김태연의 혼

프로젝트 설명 : 첫 유니티 프로젝트로서 기본적인 캐릭터 이동 , 룸 이동 , 충돌 처리만 구현해보기로 계획, 친구인 '김태연' 이라는 소재와, 근처에 유명한 공포 방탈출인 '혼' 이라는 소재를 이용하고
게임에 나오는 맵 타일셋은 https://indiside.com/openforum_pdsg/1461744 케이디님의 작품을 이용했다.

# 2.팀원 소개
| 류용헌 |
|:------:|
| <img src="https://github.com/MiruHeon/Normal-Project/blob/main/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EC%9A%A92.png?raw=true" alt="류용헌" width="150"> |
| PL |

# 3.제작 과정
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

### 룸 이동 구현
<div align="left">
  <img src="https://github.com/MiruHeon/Normal-Project/blob/main/Room%20%EC%B2%98%EB%A6%AC.png?raw=true" style="width: 300px;">
</div>
원래는 씬으로 이동시키려고 했지만, 아직 미숙한 실력으로 인해 한 씬에서 모든걸 처리하는 시스템을 구현했습니다.

# 4.프로젝트 총평
처음으로 만든 유니티 2D게임이라서 새로운 작업 환경에 많이 당황하고, 고난도 겪었지만 혼자서 코드를 분석하고 써보는 과정에서 보람을 느꼈던것 같았다.
다음에는 씬 이동과 이벤트씬 추가까지 한번 해보고 싶다는 다짐을 하게 되는 계기가 되었다.

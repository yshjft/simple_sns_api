# 도커 공부 및 실습

## 프로젝트를 진행하려 했지만 이번 기회에 도커에 대해서 알아보고 실습해보려 합니다.

## 간단하게 도커의 개념 정리
도커란 컨테이너 기반의 오픈소스 가상화 플랫폼이다. 이러한 도커는 프로그램 배포 및 관리시 개발자들의 편리성을 높여주는 것으로 생각된다.

#### 1 . 도커는 어떠한 머신이든 간에 사용자가 원하는 환경을 시뮬레이션 해준다.

#### 2 . 독립적인 컨테이너를 통해 모둘로 관리가 가능하도록 해준다.
도커의 컨테이너는 독립적이다. 따라서 하나의 서버에 여러개의 컨테이너(ex. java 컨테이너, node.js 컨테이너)들이 존재할 수 있다.

## 도커 간단한 플로우 정리(?)

각 요소들이 설치된 모습 -> '이미지로 저장' -> 설정된 요소들은 도커에 의해 컨테이너라는 독립된 가상공간에 복원        
(저장된 '이미지'는 도커 허브에 저장하거나 다운로드하여 사용할 수 있다. 또한 이러한 '이미지'들이 함께 연결되어 사용 되도록 명령어 텍스트나 문서 형태로 저장할 수 있다.)

## 가상 컴퓨팅 VS 도커
도커와 가상 컴퓨팅은 굉장히 유사해보이지만 다르다.

<가상 컴퓨팅>      
하나의 물리적 컴퓨터 안에 각각 OS를 가동하는 가상 컴픁터들이 물리적 자원을 분할해서 사용한다. 성능의 한계가 발생하낟.

<도커>       
OS단까지 가지 않고 실행 환경만 독립적으로 돌리기 때문에 컴퓨터에 직접 요소를 설치하는 것과 별 차잉 없는 성능을 낼 수 있으며 가상 컴퓨팅 보다 훨씬 가볍고 빠르다


[참고 : https://nakyungim.tistory.com/2 , https://pkh11.medium.com/docker-%EB%8F%84%EC%BB%A4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80-8b93d1a46aa8 , https://www.youtube.com/watch?v=chnCcGCTyBg , https://www.youtube.com/watch?v=tPjpcsgxgWc]

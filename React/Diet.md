## 프로젝트 개요
- 프로젝트 명 : 다이트
- 프로젝트 기간 : 2023.01 ~ 2023.06 (6개월)
- 참여 인원 : 기획 1, 디자인 1, 프론트엔드 2, 백엔드 2
- 담당 역할 : UI & UX 구현, 데이터 바인딩 
- 주요 작업 내역
    - 성능 최적화
    - UI & UX 구현 (재사용 컴포넌트 위주 구현)
    - 라이브러리 커스터마이징(Calendar)
    - iOS - AOS 간 UI 크로스 플랫폼 
    - 데이터 연동
- 사용 기술
    - Reactnative
    - React.memo
    - React hooks
    - AsyncStorage
    - Async - await 비동기 톤신



## 프로젝트 소개
- 위다이트 프로젝트는, iOS & Android 플랫폼을 타겟으로 출시된 다이어트 고객 관리 헬스케어 어플리케이션 입니다. Reactnative로 제작되었고, 핵심기능으로는 음식물 사진을 찍으면, 칼로리 정보를 가져와 분석하는것, 상담사와 실시간으로 채팅을 할 수 있는 채팅기능 등이 있습니다.

<br/>

## 기여 내역
- 기존 프로젝트의 코드를 가져와서 마이그레이션을 통해 개발을 진행하였습니다. 그러다 보니 기존 패키지의 버전 충돌 문제, 최적화 문제 등 다양한 문제가 존재하였는데, 저는 주로 최적화 문제를 해결하는데 노력을 많이 하였습니다. 사용자 인터렉션에 따라 데이터 변경이 빈번한 기록, 분석 탭 화면에서, React.memo 사용하여 함수형 컴포넌트들이, 의존하는 props값이 변경될때만 re-rendering 을 시킬 수 있도록 구성하고, 쇼핑 탭에서는 AsyncStorage를 사용해서 이미지 캐싱을 통해 불필요한 API 호출을 줄였으며 Async - await 비동기 데이터 호출을 통한 통신속도 개선 등, 전체적으로 어플리케이션 성능 향상을 이루어 냈습니다.
- 홈, 기록, 채팅 웹뷰, 마이페이지 등 전체 UI 의 60% 제작하였습니다.
- Doing lab Foodlens API를 사용, 음식물 사진의 칼로리 정보 표시 기능, token 을 활용한 로그인 기능 구현 등 을 맡아서 진행하였습니다.
- iOS & Android 간 크로스 플랫폼 UI를 통해 플랫폼에 관계없이 동일한 UI를 제공할 수 있도록 하였습니다.

<br/>

## 앱 동작 화면
|First|Second|Third|Fourth|
|:---:|:---:|:---:|:---:|
|![Diet_tab1](https://github.com/JEON-Sungsu/JEON-Sungsu/assets/63297236/953e4c21-38b7-4a2d-a174-ba560302caaf)|![Diet_tab2](https://github.com/JEON-Sungsu/JEON-Sungsu/assets/63297236/faa6e5a4-d1b1-4051-9e73-5f860fa2382e)|![Diet_tab3](https://github.com/JEON-Sungsu/JEON-Sungsu/assets/63297236/7cb45b1b-3014-4936-aa34-ff18042b59b0)|![Diet_tab4](https://github.com/JEON-Sungsu/JEON-Sungsu/assets/63297236/d316bd6e-5ae2-4109-b49b-3ed97b4b58d6)|

<br/>

## 프로젝트 회고
- React와 비슷할거라고 생각하고 큰 걱정없이 시작했지만 UI 구현을 함에 있어서는 기존 React나 JSX와는 크게 달라서 초반에 적응하는데 매우 힘들었던것 같습니다.<br>
가장 힘들었던 부분은, reactnative의 디버깅 툴을 사용하기가 힘들어, 셀 수 없이 많이 발생하는 에러들 때문에, 일일이 구글링을 통해 찾아보며 더디게 프로젝트를 진행했던게 가장 힘든 기억으로 남아있습니다.
- 하지만 덕분에 어떻게든 문제해결을 위해서 노력하고, 몇시간이걸리든 며칠이 걸리든 해결해냄으로써 문제해결을 위한 포기하지 않는 자세를 지닐 수 있게 된 것 같습니다. <br> 이것 이외에도 업데이트를 지원하지 않는 라이브러리, 버전을 지원이 안되는 SDK, 불편한 Android emulator 등 다양한 문제가 많았지만, 어떻게든 해결해 나가려고 노력하는 법을 배웠습니다.
- 기술적으로는 최적화를 위해 필요한 일들, Memoization, Caching, Async-awit등의 방법들을 익혔고, Reactnative의 UI작성법, 각각의 OS에 맞게 UI를 구현하는법등을 배울 수 있었습니다. 

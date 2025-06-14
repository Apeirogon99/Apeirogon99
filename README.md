<div>

  <!--Header-->
  ![header](https://capsule-render.vercel.app/api?type=Waving&color=timeGradient&height=300&section=header&text=Apeirogon99&fontSize=90)
  
</div>

<div>
  <!--Body-->

  <div align="center"> <h1> 📁 PROJECTS </h1> </div>

  ## MMORPG
  개발 기간 : 2023.01 ~ 2023.11 (10 개월) </br>
  개발 인원 : 서버 (1명), 클라이언트 (1명) </br>
  개발 목표 : IOCP 네트워크 처리, 데이터베이스 연동 기반 MMORPG 서버 프레임워크 및 콘텐츠 개발 </br>
  기술 스택 : C++, MS-SQL, Unreal Engine4 </br>
  관련 링크 : [[게임서버 엔진]](https://github.com/Apeirogon99/ApeirogonServerEngine), 
             [[게임서버 콘텐츠]](https://github.com/Apeirogon99/Project_LD_Server),
             [[개발 일기]](https://apeirogon99.tistory.com/category/%5BMMORPG%5D) </br>
  결과 영상 : (아래 영상을 클릭하면 유튜브에서 재생됩니다) </br>
  [![Video Label](http://img.youtube.com/vi/V_tvPMT1-Mk/0.jpg)](https://youtu.be/V_tvPMT1-Mk)
  ### 구현 요약 : </br>
  #### System
  - [네트워크 처리]() : 
  - [데이터베이스 처리]() : 
  - [인공지능]() : 
  - [충돌 감지]() : 
  - [가시거리]() : 
  - [데드레커닝]() : 
  - [언리얼 엔진4 연결]() : 
  #### Tool
  - [위젯 관리]()
  #### Content
  - 전투
    - [일반/연속 공격]() : 
    - [패턴 공격]() : 
    - [몬스터 관리]() : 
    - [스킬]() : 
    - [버프/디버프]() : 
  - SNS
    - [채팅]() : 
    - [파티]() : 
    - [친구]() : 
  - 캐릭터
    - [캐릭터 커스텀]() : 
  - 아이템
    - [장비]() : 
    - [인벤토리]() : 
    - [수집]() : 
  - 계정
    - [회원가입 및 인증]() : 
    - [로그인]() : 
 
  
  ------
  ## 2D FPS
  개발 기간 : 2024.07 ~ 2025.01 (6개월) </br>
  개발 인원 : 기획 (1명), 서버 (2명), 클라이언트 (2명) </br>
  개발 목표 : .Net과 Docker를 활용하여 게임 매칭 및 컨테이너 기반 게임 세션 관리하기 </br>
  기술 스택 : C#, .NET, Unity, Docker, Redis, MySQL </br>
  관련 링크 : [[아웃게임 서버]](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer), 
             [[DB 관리 자동화]](https://github.com/Apeirogon99/SchemaStructor),
             [[개발 일기]](https://apeirogon99.tistory.com/category/%5BSurvival%20Horizion%5D) </br>
  결과 영상 : (아래 영상을 클릭하면 유튜브에서 재생됩니다) </br>
  [![Video Label](http://img.youtube.com/vi/444oGjuMZwc/0.jpg)](https://youtu.be/444oGjuMZwc)
  ### 구현 요약 : </br>
  #### System
  - [게임 서버 사이클](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer) : 클라이언트가 매칭을 거쳐 게임 서버에 접속되어 입장되고 종료되는 라이프 사이클
  - [매치메이킹](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/Matchmaker) : ASP.NET 백그라운드 서비스로 Redis Sorted Set을 활용한 매칭큐와 MMR 매치매이킹 시스템 구현 
  - [게임 서버 관리](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/GameServerManager) : 매칭 요청을 받아 ASP.NET으로 Redis에 등록된 컨테이너 상태를 받아 Docker에서 실행되고 있는 게임 방과 연결해주는 매니저
  - [유저 인증 및 관리](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/GsoWebServer) : 구글 인증을 통해 유저의 토큰을 관리하고 Redis에 임시 저장하여 다음 요청에 활용
  #### Tool
  - [DB 코드 제너레이터](https://github.com/Apeirogon99/SchemaStructor) : MySQL 데이터베이스 스키마를 분석하여 C# 모델 클래스, Enum을 자동으로 생성해주는 코드 제너레이터
  #### Content
  - [일일 미션]() : 
  - [레벨 보상]() :
  - [티켓]() :
  - [인벤토리]() : 
  
  ------
  <div align=center><h1>📚 STACKS</h1></div>
  
  <div align=center> 
    <img src="https://img.shields.io/badge/c-A8B9CC?style=for-the-badge&logo=c&logoColor=white"> 
    <img src="https://img.shields.io/badge/c++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
    <img src="https://img.shields.io/badge/unrealengine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white">
    <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 
    <br>
    <img src="https://img.shields.io/badge/dotnet-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"> 
    <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
    <img src="https://img.shields.io/badge/redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
    <br>
  </div>

  
</div>

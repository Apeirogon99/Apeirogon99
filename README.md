<div>

  <!--Header-->
  ![header](https://capsule-render.vercel.app/api?type=Waving&color=timeGradient&height=300&section=header&text=Apeirogon99&fontSize=90)
  
</div>

<div>
  <!--Body-->

  <div align="center"> <h1> 📁 PROJECTS </h1> </div>

  ## Dark Crown : Return of the Lich (논 타겟팅 액션 MMORPG)
  개발 기간 : 2023.01 ~ 2023.11 (10 개월) </br>
  개발 인원 : 서버 (1명), 클라이언트 (1명) </br>
  개발 목표 : IOCP + ADO를 이용한 I/O처리 서버 프레임워크 구현, 논 타겟팅 액션을 위한 시스템 및 MMORPG 콘텐츠 제작 </br>
  기술 스택 : C++, MS-SQL, Unreal Engine4 </br>
  관련 링크 : [[게임서버 엔진]](https://github.com/Apeirogon99/ApeirogonServerEngine), 
             [[게임서버 콘텐츠]](https://github.com/Apeirogon99/Project_LD_Server),
             [[개발 일기]](https://apeirogon99.tistory.com/category/%5BMMORPG%5D) </br>
  결과 영상 : (아래 영상을 클릭하면 유튜브에서 재생됩니다) </br>
  [![Video Label](http://img.youtube.com/vi/V_tvPMT1-Mk/0.jpg)](https://youtu.be/V_tvPMT1-Mk)
  ### 구현 요약 : </br>
  #### System
  - [서버 처리 과정]() : 네트워크 + 메인 로직 + 데이터베이스를 처리하는 서버 처리 과정
    - [메인로직 처리]() : 네트워크/DB 큐 처리, 월드 상태 업데이트
    - [네트워크 처리]() : IOCP모델을 통해 수신된 데이터 잡 큐에 저장
    - [데이터베이스 처리]() : ADO를 통해 MS-SQL 저장프로시저 실행
  - 전투 시스템
    - [몬스터 인공지능]() : FSM을 이용한 단순한 인공지능 적용
    - [충돌 감지]() : KD-Tree를 이용하여 충돌 감지
    - [기본/패턴 공격] : Shot -> Target -> Over 순서 적용
  - 동기화
    - [이동 동기화]() : 
    - [애니메이션 동기화]() : 
  - 최적화
    - [가시거리]() : 
  #### Tool
  - [위젯 관리]()
  #### Content
  - 전투
    - [스킬]() : 
    - [버프/디버프]() : 
  - SNS
    - [채팅]() : 
    - [파티]() : 
    - [친구]() : 
  - 캐릭터
    - [캐릭터 커스텀]() : 
  - 아이템
    - [수집]() : 
    - [장비]() : 
    - [인벤토리]() : 
  - 계정
    - [회원가입 및 인증]() : 
    - [로그인]() : 
 
  ------
  ## Survival Horizon (2D 익스트렉션 슈터)
  개발 기간 : 2024.07 ~ 2025.01 (6개월) </br>
  개발 인원 : 기획 (1명), 서버 (2명), 클라이언트 (2명) </br>
  개발 목표 : 실시간 매칭과 동적 게임 세션 배정을 통한 입장 구현, 아웃 게임 및 루팅, 아이템 관련 콘텐츠 제작 </br>
  기술 스택 : C#, .NET, Unity, Docker, Redis, MySQL </br>
  관련 링크 : [[아웃게임 서버]](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer), 
             [[DB 관리 자동화]](https://github.com/Apeirogon99/SchemaStructor),
             [[개발 일기]](https://apeirogon99.tistory.com/category/%5BSurvival%20Horizion%5D) </br>
  결과 영상 : (아래 영상을 클릭하면 유튜브에서 재생됩니다) </br>
  [![Video Label](http://img.youtube.com/vi/444oGjuMZwc/0.jpg)](https://youtu.be/444oGjuMZwc)
  ### 구현 요약 : </br>
  #### System
  - [게임 서버 사이클](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer) : 실시간 매칭과 동적 게임 세션 배정을 통한 게임 입장 사이클
    - [레이팅 기반 매칭 시스템](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/Matchmaker) : Redis 큐로 플레이어 대기열 관리, ASP.NET 백그라운드 서비스로 실시간 MMR 매칭 처리
    - [컨테이너 기반 게임 세션 관리](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/GameServerManager) : ASP.NET으로 Docker를 관리하여 동적 게임 세션 관리 및 입장 처리
  - [유저 인증 및 관리](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/GsoWebServer) : 구글 인증을 통해 유저의 토큰을 Redis에서 관리, 요청 시 유효 토큰인지 확인 
  #### Tool
  - [DB 코드 제너레이터](https://github.com/Apeirogon99/SchemaStructor) : MySQL 스키마 분석을 통한 C# 클래스, Enum 자동 생성
  #### Content
  - 아웃 게임
    - [일일 미션]() : 
    - [레벨 보상]() :
    - [티켓]() :
  - 인 게임
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

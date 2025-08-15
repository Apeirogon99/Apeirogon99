<div>
  
  <!--Header-->
  ![header](https://capsule-render.vercel.app/api?type=Waving&color=timeGradient&height=300&section=header&text=Apeirogon99&fontSize=90)

  <div align=center><h1>🚀 이런 개발자입니다</h1></div>
  
  <div align=center> 
      쾌적한 서버 환경을 통해 더 많은 유저분들에게 즐거운 경험을 주고싶은 게임 서버 개발자입니다.
  </div>
  
  <div align=center><h1>📚 기술 스택</h1></div>
  
  <div align=center> 
    <img src="https://img.shields.io/badge/c-A8B9CC?style=for-the-badge&logo=c&logoColor=white"> 
    <img src="https://img.shields.io/badge/c++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
    <img src="https://img.shields.io/badge/unrealengine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white">
    <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
    </br>
    <img src="https://img.shields.io/badge/dotnet-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"> 
    <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
    <img src="https://img.shields.io/badge/redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
    <br>
  </div>
  
  </div>

  <div align="center"> <h1> 📁 프로젝트 </h1> </div>
  
1. [Survival Horizon (2D 익스트렉션 슈터)](#survival-horizon-2d-익스트렉션-슈터) - 2024.07 ~ 2025.01 (6개월)  </br>

2. [Dark Crown : Return of the Lich (논 타겟팅 액션 MMORPG)](#dark-crown--return-of-the-lich-논-타겟팅-액션-mmorpg) - 2023.01 ~ 2023.11 (10 개월)  </br>
  
 # Survival Horizon (2D 익스트렉션 슈터)
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
  - [게임 서버 사이클](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/README.md#게임-서버-사이클) : 실시간 매칭과 동적 게임 세션 배정을 통한 게임 입장 사이클
    - [레이팅 기반 매칭 시스템](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/README.md#레이팅-기반-매칭-시스템) : Redis 큐로 플레이어 대기열 관리, ASP.NET 백그라운드 서비스로 실시간 MMR 매칭 처리
    - [컨테이너 기반 게임 세션 관리](https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer/README.md#컨테이너-기반-게임-세션-관리) : ASP.NET으로 Docker를 관리하여 동적 게임 세션 관리 및 입장 처리
  #### Tool
  - [DB 코드 제너레이터](https://github.com/Apeirogon99/SchemaStructor) : MySQL 스키마 분석을 통한 C# 클래스, Enum 자동 생성
  #### Content
  - 아웃 게임
    - [일일 임무](https://github.com/sulbos-GP/GunShooterOnline/blob/main/GSO_WebServer/README.md#일일-미션) : 하루마다 초기화되는 임무를 인 게임에서 업데이트하고 완료했다면 보상을 받을 수 있다
    - [레벨 보상](https://github.com/sulbos-GP/GunShooterOnline/blob/main/GSO_WebServer/README.md#레벨-보상) : 게임이 종료되면 퍼포먼스에 의한 경험치가 증가되고 레벨에 따른 보상을 얻을 수 있다
    - [티켓](https://github.com/sulbos-GP/GunShooterOnline/blob/main/GSO_WebServer/README.md#티켓) :게임에 들어가기 위해 필요한 티켓이 최대치 보다 작을 때 일정시간 마다 얻을 수 있다
  - 인 게임
    - [인벤토리](https://github.com/sulbos-GP/GunShooterOnline/blob/main/GSO_WebServer/README.md#인벤토리) : 그리드 방식의 인벤토리

  # Dark Crown : Return of the Lich (논 타겟팅 액션 MMORPG)
  개발 기간 : 2023.01 ~ 2023.11 (10 개월) </br>
  개발 인원 : 서버 (1명), 클라이언트 (1명) </br>
  개발 목표 : IOCP + ADO를 이용한 I/O처리 서버 프레임워크 구현, 논 타겟팅 액션을 위한 시스템 및 MMORPG 콘텐츠 제작 </br>
  기술 스택 : C++, MS-SQL, Unreal Engine4 </br>
  관련 링크 : [[게임서버 엔진]](https://github.com/Apeirogon99/ApeirogonServerEngine), 
             [[게임서버 콘텐츠]](https://github.com/Apeirogon99/Project_LD_Server),
             [[충돌 테스트]](https://github.com/Apeirogon99/CollisionDetection),
             [[이동 동기화]](https://github.com/Apeirogon99/MovementSync),
             [[가시거리]](https://github.com/Apeirogon99/AreaOfInterest),
             [[개발 일기]](https://apeirogon99.tistory.com/category/%5BMMORPG%5D) </br>
  결과 영상 : (아래 영상을 클릭하면 유튜브에서 재생됩니다) </br>
  [![Video Label](http://img.youtube.com/vi/V_tvPMT1-Mk/0.jpg)](https://youtu.be/V_tvPMT1-Mk)
  ### 구현 요약 : </br>
  #### System
  - [서버 처리 과정](https://github.com/Apeirogon99/ApeirogonServerEngine/blob/master/README.md#서버-처리-과정) : 네트워크 + 메인 로직 + 데이터베이스를 처리하는 서버 처리 과정
    - [메인로직 처리](https://github.com/Apeirogon99/ApeirogonServerEngine/blob/master/README.md#메인로직-처리) : 네트워크/DB 큐 처리, 월드 상태 업데이트
    - [네트워크 처리](https://github.com/Apeirogon99/ApeirogonServerEngine/blob/master/README.md#네트워크-처리) : IOCP모델을 통해 수신된 데이터 잡 큐에 저장
    - [데이터베이스 처리](https://github.com/Apeirogon99/ApeirogonServerEngine/blob/master/README.md#데이터베이스-처리) : ADO를 통해 MS-SQL 저장프로시저 실행
  - 전투 시스템
    - [몬스터 인공지능](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#몬스터-인공지능) : FSM을 이용한 단순한 인공지능 적용
    - [충돌 감지](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#충돌-감지) : KD-Tree를 이용하여 충돌 감지
      - [충돌 테스트](https://github.com/Apeirogon99/CollisionDetection) : Array, Quad-Tree, KD-Tree 비교 및 분석
    - [공격 방식](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#공격-방식) : Shot -> Target -> Over 통일된 공격 순서 적용
  - [이동 동기화](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#이동-동기화) : 데드레커닝을 이용한 동기화
    - [데드레커닝 개선](https://github.com/Apeirogon99/MovementSync) : 데드레커닝 방향전환으로 인한 위치 오차를 줄이기 위한 동적 동기화 적용
  - [가시거리](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#가시거리) : 트래픽을 줄이기 위한 가시거리 제작 및 활용
    - [가시거리 개선](https://github.com/Apeirogon99/AreaOfInterest) : 플레이어 시야기준 가시영역을 나누어 정보 및 주기를 나눠 트래픽 감소 적용
  #### Tool
  - [위젯 관리](https://github.com/Apeirogon99/Project_LD/tree/master/Source/Project_LD/Public/Widget) : 언리얼 엔진의 HUD를 이용하여 위젯 관리
  #### Content
  - 전투
    - [스킬](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#스킬) : 설치형, 차징, 대쉬, 패링 스킬 구현
    - [패턴](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#패턴) : 3페이즈 보스의 스킬 및 다크 나이트 애니메이션 구현
    - [버프/디버프](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#버프-디버프) : 캐릭터의 능력치 버프/디버프와 시야를 가리는 블라인드 구현
  - SNS
    - [채팅](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#채팅) : 주변에 있다면 채팅을 볼 수 있는 전체 채팅
    - [파티](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#파티) : 파티를 추가, 추방, 위임하고 던전을 같이 참여 가능
    - [친구](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#친구) : 친구를 추가하여 온라인 상태, 오프라인 상태 확인 가능
  - 캐릭터
    - [캐릭터 커스텀](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#캐릭터-커스텀) : 캐릭터의 외형을 변경하고 저장 및 로드할 수 있는 커스터마이징 시스템
  - 아이템
    - [루팅](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#루팅) : 등급별 아이템이 존재하고 줍고 버릴 수 있는 루팅 시스템
    - [장비](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#장비) : 장비에 따라 캐릭터의 스탯이 증가하고 시각적 외형 변경
    - [인벤토리](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#인벤토리) : 그리드 형식의 인벤토리 처리
  - 계정
    - [회원가입 및 인증](https://github.com/Apeirogon99/Project_LD_Server/blob/master/README.md#회원가입-및-인증) : 회원가입하고 이메일로 인증해야 최종적으로 가입되는 시스템
</div>

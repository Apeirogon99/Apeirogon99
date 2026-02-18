
<h1>About</h1>

<p><b>Backend Developer</b> | 대용량 트래픽과 시스템 설계에 관심이 많습니다</p>

<img src="https://github.com/user-attachments/assets/fdec3d6b-d9da-43d1-a2e3-a60c60eb3dae" width="200" alt="Apeirogon" />

<h3>Apeirogon</h3>

> 무한한 변을 가진 다각형은 원에 수렴합니다.<br>
> 완벽함에 도달할 수는 없지만, 가까워질 수는 있다고 믿습니다.<br>
> 매일의 노력이 하나의 변이 되어, 더 나은 개발자가 되고자 노력하고 있습니다.

<h2>Contact</h2>

<a href="mailto:your@email.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a> <a href="https://apeirogon99.tistory.com"><img src="https://img.shields.io/badge/Blog-FF5722?style=for-the-badge&logo=tistory&logoColor=white"></a>
  
<h2>Tech Stack</h2>

**Backend**

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white">

**Frontend**

<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white">

**Database**

<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white"> <img src="https://img.shields.io/badge/MS--SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"> <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">

**DevOps & Messaging**

<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"> <img src="https://img.shields.io/badge/K6-7D64FF?style=for-the-badge&logo=k6&logoColor=white">

**Game Development**

<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white"> <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"> <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white"> <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"> <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white"> <img src="https://img.shields.io/badge/Unreal Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white">

<h2>Projects - Backend Development</h2>

**FoodFinder** - 맛집 추천 서비스
| 기간 | 인원 | 기술 스택 |
|:---:|:---:|:---:|
| 2주 | 5인 (백엔드) | Spring Boot, JPA, Redis, MySQL |

> 쿼드트리 재귀 탐색 + Redis 그리드 캐싱으로 외부 API 호출 96% 감소, 응답속도 98% 개선

- 공공데이터 API 의존을 쿼드트리 기반 공간 검색으로 전환
- 위치 좌표를 그리드 키로 변환하여 Redis 캐시 적중률 극대화
- Dark Crown의 공간 분할 경험(KD-Tree/QuadTree 비교)이 설계 근거

<a href="https://github.com/Apeirogon99/FoodFinder">깃허브 + 정리</a>

---

**TimeDeal** - 대기열 관리 시스템
| 기간 | 인원 | 기술 스택 |
|:---:|:---:|:---:|
| 2주 | 5인 (백엔드) | Spring Boot, Spring Cloud, Redis, MariaDB |

> 서버 증설 없이 동시 구매 실패를 0건으로 만든 Redis 2단계 큐 유입 제어

- 대기열 → 통과열 구조로 DB 동시 접근을 100명 이하로 제한 (CouponRush 측정값 기반)
- Sorted Set score를 만료 타임스탬프로 활용한 O(log N) TTL 만료 처리
- SSE 기반 순번·예상 대기시간 실시간 전송

<a href="https://github.com/Apeirogon99/TimeDeal">깃허브 + 정리</a>

---

**CouponRush** - 선착순 쿠폰 발급 시스템
| 기간 | 인원 | 기술 스택 |
|:---:|:---:|:---:|
| 진행중 | 개인 | Spring Boot, MySQL, Redis, Kafka |

> DB 비관적 락(147 req/s)에서 시작해 Kafka 비동기 처리로 성공 응답 시간을 5.4s → 559ms로 개선하기까지의 과정

- DB Lock → Redis 분산락 → Kafka 순차적 아키텍처 확장과 각 단계의 병목 분석
- 분산 환경에서의 보상 처리 설계와 한계 정리
- K6 부하 테스트(동시 3,000명)를 통한 시나리오별 정량 비교

<a href="https://github.com/Apeirogon99/CouponRush">깃허브 + 정리</a>

---

**Flint** - 소셜 미디어 플랫폼
| 기간 | 인원 | 기술 스택 |
|:---:|:---:|:---:|
| 1개월 | 4인 (백엔드) | Spring Boot, JPA, QueryDSL, Vue.js, MariaDB |

> 상호 팔로우 시 발생하는 데드락을 락 순서 고정으로 원천 차단하고, LIKE 검색 성능 30% 개선

- 양방향 팔로우의 순환 대기를 `Math.min/max` 락 순서 고정으로 해결
- `%keyword%` → `keyword%` 전환으로 인덱스 활용 검색 최적화
- 커서 기반 페이지네이션으로 무한 스크롤 구현

<a href="https://github.com/Edurican/Flint">깃허브 + 정리</a>

---

<h2>Projects - Game Development</h2>

**Survival Horizon** - 2D 익스트랙션 슈터
| 기간 | 인원 | 기술 스택 |
|:---:|:---:|:---:|
| 2024.07 ~ 2025.01 (6개월) | 5인 (기획 1 · 서버 2 · 클라이언트 2) | C#, .NET, MySQL, Redis, Docker |

> Redis Sorted Set 매칭 큐와 Docker 컨테이너 상태 머신으로 멀티플레이어 라이프사이클 구현

- MMR 기반 범위 매칭 + 대기 시간에 따른 허용 범위 점진 확장
- 컨테이너 준비 전 접속 버그를 상태 단계 분리(초기화 → 세팅 → 대기 → 할당)로 해결
- 이 프로젝트의 Redis 큐 경험이 이후 TimeDeal 대기열 설계로 이어짐

<a href="https://github.com/sulbos-GP/GunShooterOnline/tree/main/GSO_WebServer">Server</a> · <a href="https://github.com/Apeirogon99/SchemaStructor">DB Tool</a> · <a href="https://youtu.be/444oGjuMZwc">Demo</a>

---

**Dark Crown : Return of the Lich** - 논타겟팅 액션 MMORPG
| 기간 | 인원 | 기술 스택 |
|:---:|:---:|:---:|
| 2023.01 ~ 2023.11 (10개월) | 2인 (서버 1 · 클라이언트 1) | C++, MS-SQL, Unreal Engine 4 |

> IOCP 기반 서버 프레임워크를 직접 설계하고, 공간 분할·동기화 최적화로 실시간 전투 구현

- I/O 멀티스레드 + 로직 싱글스레드 구조의 서버 엔진 직접 구현 (Java NIO, epoll과 동일 모델)
- KD-Tree / QuadTree / Array 충돌 감지 성능 비교 → 이후 FoodFinder 쿼드트리 적용의 배경
- Dead Reckoning 동적 주기 조절로 위치 오차 27% 감소, 이중 가시영역으로 트래픽 62% 절감

<a href="https://github.com/Apeirogon99/ApeirogonServerEngine">Server Engine</a> · <a href="https://github.com/Apeirogon99/Project_LD_Server">Content Server</a> · <a href="https://youtu.be/V_tvPMT1-Mk">Demo</a> <br>
<a href="https://github.com/Apeirogon99/CollisionDetection">충돌 감지 비교 - 객체와 상황에 따른 효율적인 공간 분할 전략 고찰</a> <br>
<a href="https://github.com/Apeirogon99/MovementSync">이동 동기화 개선 - 순간 전송량 57%↑ 대비 위치 오차 27%↓ 트레이드오프 연구</a> <br>
<a href="https://github.com/Apeirogon99/AreaOfInterest">이중 가시영역 - 동기화 품질 유지하면서 트래픽 62% 절감</a>

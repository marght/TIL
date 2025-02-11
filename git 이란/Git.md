#  1. Git 의 탄생배경

​	`Git`은 리누스 토르발즈(리눅스를 만드사람)가  만든 `분산 버전 관리 시스템` 입니다.

​	`Git`이 탄생한 배경에는 재미있는 일화가 있습니다. 리눅스커널에서 `BitKeeper`라는 분산 버전 관리 시스템

​	을 사용 하였습니다. `BitKeeper`은 유료였지만 리눅스커뮤니티에는 무료로 사용하던 와중 커뮤니티내의

​	한 개발자가 `BitKeeper`의 통신 프로토콜을 리버스 엔지리어링을 하여 해킹하는 사건이 발생되자 

​	`BitKeeper`은 리눅스커뮤니티에 더이상 무료로 사용할 수 없도록 유료 전환을 하였습니다.

​	하지만 `BitKeeper`을 대체할 시스템은 필요하던 와중 토르발즈가 `단 2주`만에 만든 시스템이 `Git`입니다.

<br>

​	빠른시간에 만들었지만 `Git`은 `BitKeeper`의 장점은 수용하고 단점은 보안해서 나온 시스탬입니다.

​	아래의 내용은 `Git`이 추구하고자 했던 방향입니다.

​		- 단순한 구조와 빠른 속도

​		- 비선형적 개발 방식 추구

​		- 완벽한 분산형 시스템

<br>

<br>

# 2. Git, GitHub 이란?

​	`Git`의 탄생배경처럼 `Git`은 분산 버전 관리를 위해 탄생한 시스템 입니다. 

​	특히 `Git`은 로컬 환경에서 프로젝트를 진행하면서 코드를 수정하면서 버전을 관리해주는 프로그램입니다.

​	그렇다면 `Github`는 무엇일까요?  `Git`을 활용해 로컬에서 진행한 내용을 클라우드 방식으로 버전을 관리하는

​	원격저장소 입니다. 

<br>

# 3. Git 영역

​	`Git 영역`에는 `작업공간`(Working Directory), `준비공간`(Staging area), `저장소`(Repository)가 있습니다.

​	그림으로 보면 아래와 같이 나타낼수 있습니다.

​	![](C:\Users\dsw99\OneDrive\바탕 화면\img.png)

​		출처 : https://uxgjs.tistory.com/182

- 작업공간(Working Directory) 
  - 현재 작업(코드 작성,수정 등)이 이루어지는 공간입니다.
  - Git이 관리는 영역이기는 하지만 추적하고 있지 않는 상태 입니다.

<br>

- 준비공간(Staging area)
  - 작업공간에서 작업한 내용(코드 작성, 수정)이 저장소에 Commit되기 전에 거치는 공간입니다.
  - 즉 변경사항이 있는 파일을 `git add` 한 파일들이 존재하는 영역 입니다.

<br>

- 저장소(Repository)
  - `저장소`는 2가지 영역이 있습니다. `로컬 저장소`  와 `원격 저장소`가 있습니다.
  - commit된 내용이 저장되어 있는 위치입니다.
  - 로컬 저장소(Local Repository)는 개인PC에 파일이 저장되는 곳입니다.
  - 원격 저장소(Remote Repository)는 클라우드에 저장되어 다른 사람과 공유하기 위한 저장소입니다.

<br>

# 4. Git의 상태

- Untracked : `Git`이 변경사항을 추적하고 있지 않는 상태 입니다.
- Tracked : `Git`이 변경사항을 추적하고 있는 상태로 3가지 상태가 있습니다.
  - Modified : 마지막 변경사항과 비교하여 변경 내용이 있는 상태 입니다.
  - Unmodified : 마지막 변경사항과 비교하여 변경 내용이 없는 상태 입니다.
  - Staged : 변경사항이 있는 파일이 `git add`를 통해 `준비공간`에 올라와 있는 상태 입니다.

​		



​					

  


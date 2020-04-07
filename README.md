# git 이란 ?

프로그램 등의 소스 코드 관리를 위해 2005년에 개발된 분산 버전 관리 시스템(DVCS)."리누스 토르발스"가 BitKeeper 유료화에 자극받아 리눅스 커널 프로젝트에 사용하기 위해 개발.
네트워크에 접근하거나 중앙 서버에 의존하지 않고도 사용 가능.

### [ Git 의 목표 ]

* 빠른 속도
* 단순한 구조
* 비선형적인 개발 (수천 개의 동시 다발적인 브랜치)
* 완벽한 분산
* 리눅스 커널 같은 대형 프로젝트에도 유용할 것 (속도나 데이터 크기 면에서)



## VCS 타입(종류)

원시 버전 관리
* 파일 복사 후 별도 저장

LVCS ( 로컬 버전 관리 시스템 )
* 버전을 개인별로 관리 : 협업이 어렵고 그 사람의 데이터가 잘못되면 모든 이력 상실

CVCS ( 중앙집중식 버전 관리 시스템 )
* 하나의 서버에 여러 클라이언트들의 파일을 저장하여 관리
* 중앙 서버에 큰 영향을 받음
* 대표적으로 CVS / SVN

DVCS ( 분산 버전 관리 시스템 )
* 로컬 저장소와 원격 저장소를 각각 가지는 버전 관리 시스템. 다수의 원격 저장소를 가질 수 있음
* 기존 VCS 에 비해 강력한 브랜치 병합 기능을 가지며, 중앙 서버에 의존적이지 않음
* 대표적으로 Git / Mercurial

## Git 데이터 작동방식 

![Snapshot](/image/gitimage.jpeg)
 Git - Snapshot (출저 : 패스트캠퍼스) 


# git 사용하기 

### git 설치하기 
[https://sourceforge.net/projects/git-osx-installer/](https://sourceforge.net/projects/git-osx-installer/)

버전확인 방법 
`git --version`, `->` `git version 2.24.1 (Apple Git-126)` 


---
### 버전관리를 들어보지 못한 사람들을 위한 DVCS - Git
[https://www.slideshare.net/ibare/dvcs-git](https://www.slideshare.net/ibare/dvcs-git)

### 출저 : 패스트캠퍼스 


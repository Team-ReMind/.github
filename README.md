# 🌟 서비스명


<br><br>

## 🌟 서비스 한 줄 소개


<br>

## 🕊️ 팀명

### 

### 팀원 소개



<br>

## 👩‍👩‍👧‍👦 R&R

| 분야 | 이름 | 포지션 |
| --- | --- | --- |
| 기획 | 배예진 | 📈서비스 기획 - 유저리서치, 경쟁사 분석 및 타겟 분석, 서비스 타겟층 정의 |
| 기획 | 김채진 | 📊서비스 기획 - 프로젝트 매니징, 유저리서치, 비즈니스 모델 |
| 기획 | 김서 | 📋 서비스 기획 -문제 정의 및 솔루션 제시, 유저리서치 |
| 디자인 | 김규리 | 📢 서비스 디자인 |
| 디자인 | 박정환 | 📢 서비스 디자인 |
| 개발 | 송승희 | 📱 Android 개발 , 앱 화면 UI 구현, 서버 연동 |
| 개발 | 이상민 | 🖥️ Server 개발,  DB 구축,  API 개발 |
| 개발 | 박진우 | 🖥️ Server 개발,  DB 구축,  API 개발 |

<br>

## 🔎 목적 및 필요성






## **🔍 System Architecture**
![remind 아키텍처](https://github.com/Team-ReMind/.github/assets/77064618/33b74fb9-397d-47d8-806b-f28c375c60d7)

<br><br>

## 🔑기술 스택

### 🖥️Android
 ![Android Studio](https://img.shields.io/badge/Android%20Studio-%233DDC84?logo=androidstudio&logoColor=white)
 ![Retrofit](https://img.shields.io/badge/Retrofit-%23009020)
 ![Jetpack](https://img.shields.io/badge/Jetpack%20-%234285F4?logo=jetpackcompose&logoColor=white)
<br/>

#### Android OS
- 가장 널리 사용되는 모바일 운영체제로 서비스 제공합니다.

#### Clean Architecture
- Domain Layer (비즈니스 로직, Usecase, Repository 포함), Data Layer (Repository 구현체, 데이터 입출력 Data Source, Entity 포함), Presentation Layer (MVI 패턴 사용) 

#### Dagger-Hilt
- Clean Architecture의 각 계층에서 필요한 객체 생성 및 의존성 주입을 위한 Dagger-Hilt 사용합니다.

#### Android Jetpack
- ViewModel, Navigation, Flow, LiveData, Work Manager, Data Store, DataBinding, Compose 등을 포함하는 Android Jetpack 라이브러리 활용합니다.

#### Retrofit:
- RESTful API 호출을 위한 Retrofit 사용합니다.
  
<br/><br/>
  
### 💻Backend
- ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000.svg?style=flat-square&logo=intellij-idea&logoColor=white)
      ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat-square&logo=Java&logoColor=white)
      ![Springboot](https://img.shields.io/badge/Springboot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
      ![Shell Script](https://img.shields.io/badge/Shell_Script-%23121011.svg?style=flat-square&logo=gnu-bash&logoColor=white)
      ![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=flat-square&logo=Gradle&logoColor=white)
      ![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
      ![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=JSON%20web%20tokens)
- ![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=flat-square&logo=mysql&logoColor=white)
      ![docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
      ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=Hibernate&logoColor=white)
- ![GitHub Actions](https://img.shields.io/badge/Github%20Actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)
    ![Nginx](https://img.shields.io/badge/Nginx-%23009639.svg?style=flat-square&logo=nginx&logoColor=white)
- ![NCP](https://img.shields.io/badge/Naver%20Cloud%20Platform-2DB400?style=flat-square&logo=naver&logoColor=white)
   - ![NCP Server](https://img.shields.io/badge/NCP%20Server-%230db7ed.svg?style=flat-square&logo=naver&logoColor=white)
       ![Container Registry](https://img.shields.io/badge/NCP%20Container%20Registry-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
       ![Db](https://img.shields.io/badge/NCP%20CloudDB%20for%20Mysql-527FFF?style=flat-square&logo=Amazon%20RDS&logoColor=white)
     ![Object Storage](https://img.shields.io/badge/NCP%20Object%20%20Storage%20-569A31?style=flat-square&logo=Amazon%20S3&logoColor=white)
     
<br/>

#### Spring Data JPA 
- 자바에서 db bender에 종속되지 않고 객체 중심으로 애플리케이션 개발 가능합니다.

#### RDS mysql 
- 일정량 무료로 사용할 수 있으며 클라우드 인스턴스화 할 수 있습니다.
#### S3
- 필요한 데이터를 어디서나 쉽게 저장하고 검색할 수 있도록 해줍니다.
#### Docker 
- CICD를 진행 할 때 실행 가능한 서버 애플리케이션을 도커를 통해 컨테이너화 시켜 서버 환경에서 쉽게 실행할 수 있게 합니다.
#### Docker-compose 
- EC2 인스턴스 내부에서 빌드할 docker image 쉽게 관리할 수 있게 합니다.
#### git action 
- Github에서 제공하는 CICD 프로세스로 젠킨스와 같은 별도의 파이프라인을 구축할 필요 없다는 장점이 있습니다.
#### Spring Security 
- Spring boot와 통합하여 사용자 인증과 인가에 대한 보안 요구사항을 쉽게 처리하도록 도와줍니다.
#### Naver Cloud Platform
- Kusitms X Naver Cloud Platform 협업으로 제공받은 크레딧을 활용하여 서버 구축을 하였습니다.
#### NCP Server
- 스프링부트 어플리케이션 배포를 위한 서버 입니다. 크레딧을 활용하여 높은 사양의 서버를 구축했습니다.
#### NCP Container Registry
- 스프링부트 어플리케이션 이미지를 관리 및 배포하는 클라우드 환경입니다.
#### NCP CloudDB for MySQL
- MySQL 환경의 클라우드 데이터베이스입니다.
#### NCP Object Storage
- 스프링부트 어플리케이션 이미지를 저장하는 클라우드 환경입니다.

<br/><br/>

### 📑Co-working Tool
  - ![swagger](https://img.shields.io/badge/swagger-85EA2D.svg?style=flat-square&logo=swagger&logoColor=white)
      ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=flat-square&logo=notion&logoColor=white)
      ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)



<br><br>

## 🔖 Naming Rules
### 🖥️Frontend
## 🔖 Naming Rules
- 파일 : CamelCase + SnakeCase
- 클래스명 : PascalCase
- 함수/변수명 : CamelCase

### 💻Backend
- **Packages**
  - 항상 소문자로 생성하기
- **Classes**
  - 명사여야 한다.
  - 복합 단어의 경우 각 단어의 첫글자는 대문자.
  - 완전한 단어를 사용하고, 두 문자어와 약어는 피한다.
- **Interfaces**
  - 인터페이스 이름도 클래스 이름과 같은 대문자 규칙을 적용한다.
- **Methods**
  - 동사여야 한다.
  - 복합 단어의 경우 첫 단어는 소문자로 시작한다.
- **Constants**
  - 클래스 상수로 선언된 변수들과 상수들의 이름은 모두 대문자로 쓰고 각 단어는 언더바 ("_")로 분리한다.
-** Variables**
  - 변수 이름의 첫번째 문자는 소문자여야 한다.
  - 언더바 또는 달러 표시 문자로 시작하는 것이 허용 되기는 하지만, 사용하지 말자.
  - 짧지만 의미있게 짓는다.
  - 변수의 사용 의도를 알 수 있도록 의미적으로 짓는다.
  - 한문자로만 이루어진 변수는 암시적으로만 사용하고 버릴 변수를 제외하고는 피한다.
  - 임시 변수의 이름은 integer는 i,j,k,m,n 을 사용하고 character는 c,d,e를 사용한다.
- **ETC**
  - DB 테이블: **lower_snake_case**
  - ENUM, 상수: **Upper_snake_case**
  - 컬렉션(Collection): **복수형**을 사용하거나 **컬렉션을 명시한다**. (Ex. userList, users, userMap)
  - LocalDateTime: 접미사에 **Date**를 붙인다.

<br><br><br>

## **🗂️ Commit Convention**


Ex) `git commit -m "feat(#8) : 앱 설치 플로팅 배너 추가" `

- `feat` : 새로운 기능 추가
- `fix` : 버그 수정
- `chore` : 빌드 업무, 패키지 매니저, 라이브러리, dependencies 설정
- `docs` : 문서 수정 - <i>README.md, .github, ..etc</i>
- `design` : 사용자 UI 디자인 변경 - <i> CSS</i>
- `style` : 기능 수정 없는 코드 스타일 변경
- `refactor` : 코드 리팩터링
- `test` : 테스트 코드, 리펙토링 테스트 코드 추가
- `ci` : ci 설정 파일 수정
- `perf` : 성능 개선
- `rename` : 파일 혹은 폴더명 변경



<br>

## **🐬 Git Flow**
- `main` : 출시 가능한 프로덕션 코드의 브랜치
- `feature` : 기능을 개발하는 브랜치
- `hotfix` : 출시 버전에서 발생한 버그를 수정하는 브랜치

  브랜치 네이밍 : `feat/이슈번호`

<br>

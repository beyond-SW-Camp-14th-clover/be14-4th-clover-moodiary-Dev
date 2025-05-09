# 📖 Mood:iary

<center>
  <img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/mainhome.png" width="900" />
</center>

<br><br>

## 👨‍💻 DEVELOPERS

|<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/page1.jpeg" width="100" height="100"> |<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/page2.jpg" width="100" height="100"> | <img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/page3.jpg" width="100" height="100">|<img src="https://github.com/user-attachments/assets/4ba8ac89-69c0-4384-a2fb-a1f98e0e7a6d" width="100" height="100"> | <img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/page4.jpg" width="100" height="100"> |
| :------------------------------------: | :-------------------------------------: | :-----------------------------------: | :--------------------------------------: | :-----------------------------------: |
| [고성연](https://github.com/Gombo2) | [강수지](https://github.com/yehang218) | [이청민](https://github.com/Bluesky3125) | [김성민](https://github.com/SungMin-hub) | [고윤석](https://github.com/minsun24) |

<br>

## 📜 목차

#### [💡 Tech Stack](#-Tech-Stack) <br>
#### [📢 프로젝트 설명](#-프로젝트-설명) <br>
#### [🛠️ 주요 기능](#-주요기능) <br>
#### [🙆‍♀️ 요구사항 명세서](#-요구사항-명세서) <br>
#### [💭 DDD 설계](#-DDD-설계) <br>
#### [🗃️ DB 모델링](#-DB-모델링) <br>
#### [🪄 Figma](#-Figma) <br>
#### [🛜 CI/CD 프로젝트 아키텍처](#-Server) <br>
#### [🚩 젠킨스 파이프라인 파일 스크립트 코드](#-단위-테스트) <br>
#### [📱 CI/CD 테스트](#-API-테스트) <br>
#### [🍪 개인 회고록](#-개인-회고록) <br>

<br>

## 💡 Tech Stack
### 🌿 Backend
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### 🌿 Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge)
![Vue Router](https://img.shields.io/badge/Vue_Router-4FC08D?style=for-the-badge)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge)

### 🗃️ Database
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### ☁️ AWS
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazonaws&logoColor=white)

### 🛠️ Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 📢 프로젝트 설명

### 1. 프로젝트 주제

**하루하루의 감정을 기록하고 분석하여 정리하는 하루일기**

### 2. 프로젝트 설명

**Mood:iary**는 사용자의 일상 감정을 기록하고 분석하여, 나만의 감정 패턴을 시각적으로 확인할 수 있는 감정 일기 웹 서비스입니다. 감정 기록 외에도 감정 기반 행동 추천, 귀여운 펫 캐릭터 시스템, AWS 배포, JWT 보안 인증 등 다양한 기능을 제공합니다.

---

## 🛠️ 주요 기능

- ✅ 감정 일기 작성 및 수정
- ✅ AI 기반 감정 분석 및 추천 제목 생성
- ✅ 최근 감정 기반의 활동 추천
- ✅ 감정 캐릭터(펫) 설정 및 교체
- ✅ JWT 인증 로그인/회원가입
- ✅ 이메일 기반 비밀번호 재설정
- ✅ 사용자 정보 수정 및 계정 삭제
- ✅ S3 이미지 업로드 기능

---

## 🙆‍♀️ 요구사항 명세서

🔗 [요구사항 명세서 바로가기](https://docs.google.com/spreadsheets/d/18n2OJHiRjAZ0b6NBGHlsgf-LoMMUqmXSKnpa_4X8NSc/edit?gid=0#gid=0)


---

## 💭 DDD 설계

### 1. Domain Event Storming

<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/DDD1.png" width="900" />
<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/DDD2.png" width="900" />
<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/DDD3.png" width="900" />


---

## 🗃️ DB 모델링

<img src="https://github.com/user-attachments/assets/178fc0f0-47e7-4347-b687-b8cf4c596820" width="900" />

---

## 🪄 Figma

🔗 [Figma 디자인]

<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/Figma.png" width="900" />

---

## 🛜 CI/CD 프로젝트 아키텍처

<img src="https://github.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/raw/main/image/image%20(1).png" width="900" />

---

## 🚩 젠킨스 파이프라인 파일 스크립트 코드

```groovy
pipeline {
    agent any

    tools {
        gradle 'gradle'
        jdk 'openJDK17'
    }

    environment {
        GITHUB_URL = 'https://github.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-BE.git'
    }

    stages {
        stage('Preparation') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'docker --version'
                    } else {
                        bat 'docker --version'
                    }
                }
            }
        }
        stage('Source Build') {
            steps {
                git branch: 'main', url: "${env.GITHUB_URL}"
                bat '''
                    xcopy /B /Y "C:\\workspace\\be14-4th-clover-moodiary-BE\\moodiary\\src\\main\\resources\\application.yml" "moodiary\\src\\main\\resources\\application.yml"
                '''
                script {
                    dir(path: 'moodiary') {
                        if (isUnix()) {
                            sh "chmod +x ./gradlew"
                            sh "./gradlew clean build"
                        } else {
                            bat "gradlew.bat clean build"
                        }
                    }
                }
            }
        }
        stage('Container Build and Push') {
            steps {
                script {
                    dir(path: 'moodiary') {
                        withCredentials([usernamePassword(credentialsId: 'DOCKERHUB_PASSWORD', usernameVariable: 'DOCKER_USER', passwordVariable: 'DOCKER_PASS')]) {
                            if (isUnix()) {
                                sh "docker build -t ${DOCKER_USER}/moodiary-boot:${currentBuild.number} ."
                                sh "docker build -t ${DOCKER_USER}/moodiary-boot:latest ."
                                sh "docker login -u ${DOCKER_USER} -p ${DOCKER_PASS}"
                                sh "docker push ${DOCKER_USER}/moodiary-boot:${currentBuild.number}"
                                sh "docker push ${DOCKER_USER}/moodiary-boot:latest"
                            } else {
                                bat "docker build -t ${DOCKER_USER}/moodiary-boot:${currentBuild.number} ."
                                bat "docker build -t ${DOCKER_USER}/moodiary-boot:latest ."
                                bat "docker login -u %DOCKER_USER% -p %DOCKER_PASS%"
                                bat "docker push ${DOCKER_USER}/moodiary-boot:${currentBuild.number}"
                                bat "docker push ${DOCKER_USER}/moodiary-boot:latest"
                            }
                        }
                    }
                }
            }
        }
    }
    post {
        always {
            script {
                if (isUnix()) {
                    sh 'docker logout'
                } else {
                    bat 'docker logout'
                }
            }
        }
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
```

## 📱 CI/CD 테스트

<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/CICD%ED%85%8C%EC%8A%A4%ED%8A%B8.png" width="900" />



## 😊 개인 회고록

<h2>🍪 개인 회고록 - 고성연</h2>
<p>
  
**이번 프로젝트에서 맡은 역할**

- 다이어리 서비스 회원 정보 관련 기능 구현
- Spring Security를 통한 인증 인가 처리
- Pinia를 통한 사용자 권한 저장
- 일기 전반적인 로직 오류 수정

**잘한 점**

- 요구사항 명세서를 기준으로 기준에 맞는 기능들을 구현하고 적재적소에 배치함
- 다른 도메인에서 회원 정보를 사용하기 용이하게 토큰에 필요 정보 저장 및 매핑을 해 놓음
- 저번 프로젝트에서 하지 못했던 전반적인 백엔드 및 프론트 DB 연결과 함께 로그인 상태 저장 통해 실제 사용자 요청이 DB에 잘 반영이 됨

**아쉬운 점**

- 기획 단계에서 정확하게 방향을 잡지 않아 중간 개발 단계에서 테이블 스키마 변경 및 기능이 너무 자주 바뀜
- 전체적으로 로그인후 사용가능하게 인가 처리를 하였으나, GPT API 감정분석 결과를 가져오는 부분에서 해결을하지 못해 전체 허가로 변경한 부분이 아쉬움
- 의견 조율에 있어서 자기주장이 너무 강했음

**배운 점**

- 기능을 제안하고 실제 개발 단계에서 로직을 고민해서 거기서 결정해도 충분하다는 것을 깨달음
- 배포 환경과 함께 실제 버전관리를 통해 지속적인 업데이트와 배포의 과정을 배울 수 있었음
- 써보지 않았던 S3, json 파일을 통한 화면 스타일 저장 등 여러 기술을 배울 수 있었음.

**다음 프로젝트에 적용하고 싶은 점**

- 기획 단계에서 문서화를 통해 정해놓은 틀 안에서 진행하고, 그후 우선순위를 적용하여 MVP가 제작된 뒤 순차적으로 단계를 두어 리팩토링
- 코드 리뷰 시 대충 보는것이 아닌 각 PR에 대해 정확히 보고 리뷰를 작성하는 습관 만들기
</p>


<hr/>

<h2>🍪 개인 회고록 - 강수지</h2>
<p>

</p>

<hr/>

<h2>🍪 개인 회고록 - 이청민</h2>
<p>
  
**이번 프로젝트에서 맡은 역할**
- 행동 추천 가중치 관련 로직 구현
- 마이 페이지 일부 구현
- Docker, K8S, Jenkins 등 CI/CD 관련 설정

**잘한 점**
- 가중치 추천 로직을 구현하는데 많은 고민을 했고, AI를 활용하지 않는 선에서 마음에 드는 결과물을 만듦.
- 상당한 시행 착오 끝에 Docker, K8S, Jenkins로 이어지는 CI/CD 파이프라인을 완성함.

**아쉬운 점**
- 기획에 상당히 긴 시간을 들였지만 정작 정해진 것은 별로 없었고, 정해진 것도 프로젝트가 진행되며 계속 변경되었음.
- 가중치 추천은 괜찮았지만, 정작 가중치를 반영하는 부분이 제대로 완성되지 않았던 점.
- 수업 시간에 배운 CI/CD 중 일부분만 구현하는데 성공하고, 그 뒤의 Argo CD 등은 손도 대지 못한 점.

**배운 점**
- ChatGPT API나 S3 Bucket API 등을 사용한 코드를 보며 대략적인 사용 방법을 배웠음.
- CI/CD를 직접 해보며 어느 부분이 걸림돌이 되는지 확인할 수 있었음.

**다음 프로젝트에 적용하고 싶은 점**
- Github의 프로젝트는 무조건 최상위 폴더에 바로 프로젝트가 있도록 설정하기, 처음에 그렇게 되지 않았다면 무조건 리팩토링하기. Dockerfile을 만들 때, Jenkins 파이프라인 코드를 작성할 때, 최상위 폴더에 바로 프로젝트가 있지 않고 폴더를 한 번 거치는 것이 생각보다 큰 걸림돌이 되었다.
- 기획을 최대한 구체적으로 하기, 그리고 결정된 부분에 대해 나중에 판단하지 않기. 생각할 수 있는 사소한 부분을 최대한 정해두어야 실제로 구현하면서 멈추는 부분이 생기지 않는다. 기획할 때 결정한 부분을 구현하면서, 나의 생각과 결정한 내용이 다르다고 해서 계획을 고치거나 타협하지 않아야겠다.
</p>

<hr/>

<h2>🍪 개인 회고록 - 김성민</h2>
<p>
  
**이번 프로젝트에서 맡은 역할**

- 공유 일기 관련 전반적인 기능, 페이지 구현
- AWS S3를 통한 이미지 업로드 처리 기능 구현

**잘한 점**

- 요구사항을 기능 단위로 분배하고 명확하게 정리하여 개발 전반의 방향성을 잘 잡음
- CQRS 패턴을 적용하여 데이터 변경과 조회를 분리하고 도메인 책임을 명확히 나누는 구조를 잘 설계함
- 기획에 미처 생각하지 못한 디테일한 부분들에 대해 빠른 피드백과 회의를 거쳐 품질을 높임

**아쉬운 점**

- 급하게 개발하는 나머지 브랜치, 이슈, PR의 Rule을 제대로 지키지 못하고 개발한 것이 아쉬웠음
- 느슨한 기획으로 중간에 변동 사항이 너무 많았음
- 팀원간의 의견 충돌 시 중재를 잘 하지 못한것이 아쉬웠음

**배운 점**

- 협업 환경에서는 명확한 커뮤니케이션과 문서화가 중요하다는 것을 깨달음
- 프론트와 백엔드 간의 데이터 흐름을 배울 수 있었음
- 이미지 업로드, S3 연동 그리고 JSON 구조 설계등의 구현 경험을 쌓을 수 있었음

**다음 프로젝트에 적용하고 싶은 점**

- 초기 요구사항 정의와 화면 흐름 설계에 더 많은 시간을 투자하여 명확한 기능 정의와 와이어 프레임 작성하여 전체 프로젝트의 효율을 높이고자 함
- 프로젝트 초기에 WBS를 적극적으로 활용하여 전체 작업의 우선 순위와 역할 분담을 명확히 하여 일정 관리를 효율적으로 하고자 함
- 단위 테스트 작성을 습관화 하여 기능별 테스트 코드를 함께 작성해 코드의 안전성과 신뢰성을 확보하고자 함
</p>

<hr/>

<h2>🍪 개인 회고록 - 고윤석</h2>
<p>
  
**이번 프로젝트에서 맡은 역할**

- 프론트엔드 구현
    - 나의 일기 작성 / 수정 / 삭제, 조회 페이지
    - 감정 분석 컴포넌트
    - 월간, 주간 일기 페이지
    - 펫 변경, 상호작용 관련 페이지

- 백엔드 구현
    - 나의 일기 작성 / 수정 / 삭제, 조회 등 기능 전반 구현
    - 나의 일기 월간, 주간 조회 기능 및 대시보드
    - 펫 변경 기능 및 상호작용 시 감정 분석, 행동추천 기능 연결
    - GPT API를 연결해 감정 분석 데이터 추출

**잘한 점**

- 프론트와 백엔드 간 유기적 연계를 통해 일기, 펫 서비스의 기능 전반 완성
- GPT API 연계로 감정 분석 데이터를 추출해 활용
- 도메인 간 결합 시 발생한 예기치 못한 문제를 꾸준히 해결하며 문제 대응 능력 향상

**아쉬운 점**

- 초기 설계 시 기능 간 상호작용과 의존성에 대한 충분한 고려 부족
- 구현 과정에서 팀원 간 서로의 이해 차이를 빠르게 파악하지 못함
- 일부 코드에서 최적화와 가독성 개선의 여지를 충분히 고려하지 못함

**배운 점**

- 단순 구현을 넘어 기획 단계에서의 설계 정교화의 중요성 인식
- 협업에서 기술적 요구와 내용을 명확히 소통하는 능력의 필요성 체감
- AI 기반 시스템의 데이터 처리 및 통합 설계·개발 경험 축적
- 문제를 회피하지 않고 적극적인 자세로 부딪히며 성장하는 경험

**다음 프로젝트에 적용하고 싶은 점**

- 각 기능이 서로에게 미치는 영향을 고려한 보다 정교한 설계
- 팀 내 소통에서 상호 간의 생각을 명확히 정리·공유
- 처음부터 유지보수성, 리팩토링을 생각해 가독성 높은 코드 작성
- 더 다양한 문제 상황을 경험하고 능동적으로 대처하는 역량 강화
</p>

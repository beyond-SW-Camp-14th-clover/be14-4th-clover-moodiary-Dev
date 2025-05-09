# 📖 Mood:iary

<center>
  <img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/mainhome.png" width="900" />
</center>

<br><br>

## 👨‍💻 DEVELOPERS

|<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/page1.jpeg" width="100" height="100"> |<img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/page2.jpg" width="100" height="100"> | <img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/page3.jpg" width="100" height="100">|<img src="https://github.com/user-attachments/assets/4ba8ac89-69c0-4384-a2fb-a1f98e0e7a6d" width="100" height="100"> | <img src="https://raw.githubusercontent.com/beyond-SW-Camp-14th-clover/be14-4th-clover-moodiary-Dev/main/image/page4.jpg" width="100" height="100"> |
| :------------------------------------: | :-------------------------------------: | :-----------------------------------: | :--------------------------------------: | :-----------------------------------: |
| [고성연](https://github.com/Gombo2) | [강수지](https://github.com/yehang218) | [이청민](https://github.com/Bluesky3125) | [김성민](https://github.com/swjang7269) | [고윤석](https://github.com/minsun24) |

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

🔗 [Figma 디자인 링크](https://miro.com/app/board/uXjVIBMEE4Y=/)

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
 2주 남짓한 짧은 시간동안 굉장히 많은 시행착오를 겪었지만, 갖은 고난과 역경을 딛고 유의미한 결과물을 도출하는 데에 성공했다. 우리 팀원들이 아니었다면 결코 이뤄내지 못할 성과였을 것이다. 각각 일기와 공유 일기 파트를 맡아주신 윤석님과 성민님, ChatGPT API를 담당해주신 수지님, 이번에도 역시 회원과 인증/인가 처리를 맡아주신 성연님께 감사의 말씀을 올린다.
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
이번 프로젝트에선 나름대로 핵심 기능 중 하나인 일기 기능과 펫 기능을 맡아서 구현할 수 있는 기회를 잡았다. 처음엔 단순한 기능이라고 생각해서 솔직히 어렵지 않게 구현할 수 있다고 생각을 했었던 것 같다. 하지만 기한이 정해진 프로젝트에서 팀원들과의 협업을 하게 되면서 얽혀있는 기능들끼리 서로 영향을 주고 받게 되니 단순하다고 생각했던 기능에서 발생하는 오류들을 해결하기 위해 꽤나 고생을 했다. 이번에 하면서 느낀 것이 기획 단계에서부터 좀 더 정교하게 설계할 순 없었을까라는 자기반성을 하게 됐고 좀 더 가독성이 좋게, 팀원들이 직관적으로 이해할 수 있도록 코드를 어떻게 구성할 것인가에 대해 좀 더 고민해 봐야 할 것 같다는 생각을 하게 됐다. 그리고 팀원들과의 구현 단계에서 서로 복잡한 생각들을 가지고 대화를 하다 보니 구현 계획상의 의사소통 문제가 생겨 이해하고 있는 기능의 형태가 달라 문제가 될 뻔했지만 감사하게도 팀원들의 이해와 도움으로 이 상황을 잘 이겨냈다. 그렇지만 개발 단계에서 필요한 말들이 어떤 것인지 아직 판단하는 능력이 부족해 팀원들에게 내 의견과 상황을 잘 전달하지 못했던 것 같아서 이 부분이 스스로에게 아쉽고 다음 프로젝트를 하는 데 있어서 개선해야 할 부분이라고 생각한다. 좋은 팀원들을 만나 좋은 프로젝트를 할 수 있어 좋았고 나도 우리 팀원들에게 좋은 팀원이 되고 싶다는 욕심이 있다. 오류를 잘 해결하기 위해 더 많은 오류를 만나는 상황에 놓이도록, 팀원들과의 의사소통하는 과정에서 조금 더 신경 써서 전달 사항을 전달하도록, 수동적인 태도로 일관하기보다 적극적으로 부딪쳐 문제들을 극복할 수 있는 능력을 기르는 쪽에 방향성을 둔 개발자가 되고 싶다.
</p>

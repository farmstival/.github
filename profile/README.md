# 농촌 체험 예약 플랫폼

## 목차

- [1. 프로젝트 소개](#1-프로젝트-소개)
    * [개요](#개요)
    * [기획배경 및 기대효과](#기획배경-및-기대효과)
- [팀원 소개](#팀원-소개)
- [역할 분담](#역할-분담)
- [2. 기술 스택](#2-기술-스택)
- [3. UserFlow 작성](#3-UserFlow-작성)
- [4. 기능 명세서](#4-기능-명세서)
- [5. ERD](#5-ERD)
- [6. 테이블 다이어그램](#6-테이블-다이어그램)
- [7. 화면설계](#7-화면설계)
- [8. 프로젝트 회고](#8-프로젝트-회고)

## 👩‍🏫1. 프로젝트 소개

#### 개발기간
2024/08/01 ~ 2024/08/30

### 개요

최근 분석에 따르면 2021년 이후부터 국민들의 국내 여행 수요가 증가하였다고 합니다. 특히 코로나19 이후 감염 위험이 적은 '농촌'이 떠오르며 '촌캉스(농촌 + 바캉스)'와 같은 여행 트렌드가 주목받았습니다. 또한 농촌 여행을 통해 휴식, 경험, 학습을 중시하는 런케이션(Learning + Vacation)을 추구하는 경향이 강해졌으며, '체험', '경험', '힐링'과 같은 키워드가 높은 언급량을 보였습니다. 이에 따라 농촌 여행도 새로운 트렌드에 맞춰 끊임없이 변화하고 있으며, 변화하는 트렌드를 반영한 농촌 지역 활성화를 위해 본 프로젝트를 진행하게 되었습니다.

### 기대효과 및 활용 분야

- 변화하는 농촌 여행 트렌드에 따라 체험 정보와 주변 여행지, 지역별 축제에 관한 정보를 다양하게 제공할 수 있습니다.
- 농촌 체험 정보 제공뿐만 아니라 체험 예약 기능을 포함하여 체험을 예약하고 실제 방문까지 이어질 수 있도록 합니다.
- 농촌 방문객 증가를 통해 관광 산업을 발전시키고, 새로운 일자리 창출과 더불어 농촌 지역 활성화를 도모합니다.
- 관광객 유입으로 인한 농촌 지역 인프라 개선을 기대합니다.
- 농촌의 다양한 체험 활동을 통해 농촌 문화의 보존뿐만 아니라 농촌 자원의 활용도를 증가시킵니다.
- 농촌으로의 여행을 통해 바쁜 삶 속에서 휴식과 힐링, 그리고 평소 접하기 어려운 다양한 경험을 제공합니다.

## 👨‍👩‍👧‍👦 팀원 소개
|<img src="https://avatars.githubusercontent.com/u/163953938?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/132132524?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/136600208?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/154653812?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/163940532?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/164159618?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/163953803?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|[@hyeon12](https://github.com/hyeon12)|[@heyejiyang](https://github.com/heyejiyang)|[@kth232](https://github.com/kth232)|[@soeunl](https://github.com/soeunl)|[@siwon9](https://github.com/siwon9)|[@Yunda0204](https://github.com/Yunda0204)|[@beom33](https://github.com/beom33)|
## 역할 분담

|개발자|UI|기능|
|------|---|---|
|서정현|테스트2|테스트3|
|양예지|테스트2|테스트3|
|강태현|테스트2|테스트3|
|이소은|테스트2|테스트3|
|최시원|테스트2|테스트3|
|이진표|테스트2|테스트3|
|유준범|테스트2|테스트3|
## 💻2. 기술 스택

✅ Programming Languages
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">

✅ Front-end Development <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
<img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=Thymeleaf&logoColor=white">

✅ Back-end Development <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white">
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">

✅Database <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">

✅Devops <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a>
&nbsp;&nbsp;<a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a>

## 3. UserFlow 작성

## 4. 기능 명세서
📄[기능명세서](https://www.notion.so/c9d367c479054e918154883713dd2164?pvs=4)

![image](https://github.com/user-attachments/assets/3817d092-281e-49f4-a7b2-c3d494cf8098)


![image](https://github.com/user-attachments/assets/c4b20239-b600-4ade-b09d-4f21cccaa65c)



## 5. ERD
![farm_chon](https://github.com/user-attachments/assets/76e8731a-15ac-41b6-a1f1-d81249a20a3f)

## 6. 테이블 다이어그램

## 7. 화면설계

## 8. 프로젝트 회고

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

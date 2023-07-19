# Database_Project
- 오라클 데이터베이스를 이용한 교육센터 운영 프로그램 제작

# 프로젝트 소개
- 교육센터를 운영하기 위한 기능들을 고색의 요구사항에 맞춰 개발하고, 이 기능들을 모아 하나의 프로그램으로 관리할 수 있게 한다.
- 교육센터에서의 업무를 효율적으로 처리, 관리할 수 있게 하여 운영에 편리함을 증진시킨다.

# 개발기간
- 2023-03-27 ~ 2023-04-07

# 기술 스택
### Environment
<img src="https://img.shields.io/badge/Eclipse IDE-2c2255?style=for-the-badge&logo=EclipseIDE&logoColor=white"/> 

### Language & Framework
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/> 

### Database
<img src="https://img.shields.io/badge/Oracle Database-f80000?style=for-the-badge&logo=Oracle&logoColor=white"/> 

# 데이터 구조
<img src="3. 개념도 & ERD/화면 캡처.PNG">

<hr>

### 개요
1. 관리자가 기초 정보를 기반으로 과목과 과정을 개설하고 과목에 맞는 교사를 배정하면 교육생들의 출결과 성적을 관리할 수 있는 기능.
2. 교사가 과목별 시험과 교육생의 시험 성적, 과제 등을 관리하고 자신의 강의 스케줄을 조회할 수 있는 기능.
3. 교육생이 자신의 출결, 성적 과제 등을 조회하고 상담일지와 교사평가를 관리하고 조회할 수 있는 기능.

# 대표적인 기능
### 📘 관리자 - 특정 교사 정보 조회
<img src="9. 최종 요약본/p4_2.PNG">
- 쿼리문을 통해서 데이터베이스에 저장되어 있는 교사의 정보 중에 특정 교사의 정보를 조회를 한다.

#### 결과
<img src="9. 최종 요약본/p4_4.PNG">

<hr>

### 📘 교사 - 강의를 마친 교사 자신의 과목 목록 조회
<img src="9. 최종 요약본/p4_1.PNG">
- 쿼리문을 통해서 데이터베이스에 저장되어 있는 교사 자신의 과목 목록을 조회 할 수 있다.

#### 결과

<img src="9. 최종 요약본/p4_3.PNG">

<hr>

## ❗ 아쉬웠던 점
### 오라클 데이터베이스 단독 사용
- 자바의 JDBC를 활용하여 오라클 데이터베이스와 함께 사용하는 것이 아닌 오라클 데이터베이스만 단독으로 사용하는 프로젝트여서 콘솔화면으로만 통해서 결과값을 나타나줘야되는게 너무 아쉬었다. 

## 💡 문제 해결을 위한 노력
### Git 활용 능력
- 여러 테이블에 거쳐서 갖고와야 되는 데이터는 여러 번의 inner join을 통해서 데이터에 접근하였다.

# teencoder-project
> 청소년을 위한 IT 커뮤니티 웹 TeenCoder.

<br>

## 개발 환경(Development Environment)
- IDE : IntelliJ IDEA Community Edition
- Language : JAVA 11 (JDK 11.0.18)
- Framework : Spring Framework 5.3.20, MyBatis 3.5.6
- Build Tool : Maven 3.8.0
- DBMS : MySQL 8.0.31 for Linux
- WAS : Apache Tomcat 9.0

<br>

## 주요 기능(Main Function)
- 회원(member)
    - 로그인(login)
    - 로그아웃(logout)
    - 회원가입(join)
    - 회원목록(list)
    - 회원정보 조회(detail)
    - 회원정보 수정(update)
    - 회원정보 삭제(delete)

- 게시판(board)
    - 게시글 작성(write)
    - 게시글 목록(list)
    - 게시글 조회(detail)
    - 게시글 수정(update)
    - 게시글 삭제(delete)
    - 게시글 페이징(paging)

<br>

## MySQL DataBase 계정 생성 및 권한 부여
```SQL
create database teencoder;
create hoong@localhost identified by '8888';
grant all privileges on teencoder.* to hoong@localhost;
```

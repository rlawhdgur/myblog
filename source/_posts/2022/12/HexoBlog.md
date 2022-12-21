---
title: Hexo 블로그 만들기
date: 2022/12/21 15:34:25
categories:
- Hexo
- Baseball
tags:
- Hexo
- Fight
- Shocking
---

# Hexo 블로그 만들기

## Hexo Blog 만들기

- [https://dschloe.github.io/settings/hexo_blog/](https://dschloe.github.io/settings/hexo_blog/)

## 필수 파일 설치

### node.js 다운로드

- node.js 검색 및 다운로드
    
    ![Untitled](/images/2022/12/HexoBlog/Untitled.png)
    
- Add to PATH 클릭 후 다운로드
    
    ![Untitled](/images/2022/12/HexoBlog/Untitled%201.png)
    
- node.js 설치 완료 후 간단하게 확인해본다.
    - **$ node -v**

### Git 다운로드

- git 설치 완료 후 간단하게 확인해본다.
    - **$ git —version**

![Untitled](/images/2022/12/HexoBlog/Untitled%202.png)

### Hexo 설치

- 아래의 코드를 입력해 hexo설치를 한다.
    - **$ npm install -g hexo-cli**

![Untitled](/images/2022/12/HexoBlog/Untitled%203.png)

![Untitled](/images/2022/12/HexoBlog/Untitled%204.png)

## Github에서 Repositories 생성

- Repository name에서 Owner 이름과 같게 만들어야 한다.
- **Owner.github.io**

![Untitled](/images/2022/12/HexoBlog/Untitled%205.png)

## 블로그 만들기

- **$ hexo init myblog**
- **$ cd myblog**
- **$ npm install**
- **$ npm install hexo-server —sava**
- **$ npm install hexo-deployer-git —sava**
    
    ![Untitled](/images/2022/12/HexoBlog/Untitled%206.png)
    
    ![Untitled](/images/2022/12/HexoBlog/Untitled%207.png)
    

## myblog Visual Studio Code

- 블로그 URL 정보 설정을 한다.

![Untitled](/images/2022/12/HexoBlog/Untitled%208.png)

- Github 연동 설정을 한다.

![Untitled](/images/2022/12/HexoBlog/Untitled%209.png)

## Github에 배포하기

- 배포 전, [localhost:4000](http://localhost:4000) 접속을 통해 화면이 나오는지 확인해본다.
- **$ hexo server**
    
    ![Untitled](/images/2022/12/HexoBlog/Untitled%2010.png)
    
    - $ **hexo generate**
    
    ![Untitled](/images/2022/12/HexoBlog/Untitled%2011.png)
    
- 화면 확인이 된 이후에는 github에 배포한다.
- **$ hexo deploy**
    
    ![Untitled](/images/2022/12/HexoBlog/Untitled%2012.png)
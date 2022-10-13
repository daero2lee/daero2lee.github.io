---
title:  "[Jekyll] 블로그 포스팅하는 방법"
excerpt: "md 파일에 마크다운 문법으로 작성하여 Github 원격 저장소에 업로드 해보자. 에디터는 Visual Studio code 사용! 로컬 서버에서 확인도 해보자. "

categories:
  - Blog
tags:
  - [Blog, jekyll, Github, Git]

toc: true
toc_sticky: true
 
date: 2022-10-12
last_modified_at: 2022-10-12
---
# gitflow 정리

git은 형상관리를 위한 도구이다.

gitflow는 프로젝트를 진행하면서 형상관리하는 방법을 편리하게 해준다.

git flow init 으로 시작하면

develop

hotfix

release

등의 branch를 생성한다.

개발은 develop에서 feature를 생성하고 시작한다.

git flow feature start {feature-name}으로 시작한다.

```ex) git flow feature start learning-center-caller```
---
title: "Welcome to Jekyll!"
date: 2017-10-20 08:26:28 -0400
categories: jekyll update
---

작성일 : 2019-02-08

a yo.

# 이거 보고 했다.
# https://dreamgonfly.github.io/2018/01/27/jekyll-remote-theme.html

깃허브 가입하고 
스타트 프로젝트 하고
리파지토리 네임에 eaaaaasy.github.io 라고 써주고
Jekyll 테마에서 맨 처음거 누르고 https://github.com/topics/jekyll-theme
_config.yml 복사해서 만들고
remote_theme : mmistakes/minimal-mistakes 주석해제
url                      : "https://eaaaaasy.github.io"
baseurl                  : ""
# Site Settings
locale                   : "en-US"
title                    : "Site Title"
title_separator          : "-"
name                     : "Your Name"
description              : "An amazing website."
url                      : "https://yourname.github.io" # the base hostname & protocol for your site e.g. "https://mmistakes.github.io"
baseurl                  : "" # the subpath of your site, e.g. "/blog"
repository               : # GitHub
이렇게 수정하고
index.html 복사해서 만들고
지금 쓰고 있는 파일 만들어서 쓰는 중이다.
상단에 
저거 꼭 써주랜다.

깃허브 웹사이트
깃허브 SPA

정적사이트
SPA
정적사이트 생성기

https://blog.cometkim.kr/posts/%EB%82%98%EB%A7%8C%EC%9D%98-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EA%B0%9C%EB%B0%9C%ED%95%98%EA%B8%B0/0-%ED%94%8C%EB%9E%AB%ED%8F%BC-%EC%84%A0%EC%A0%95/
Static Site Generator
잘나가는 개발자들은 다들 GitHub Page로 정적 사이트 하나쯤은 올려두는 것 같다. 이유는 다양하겠지만 일단 평소에 마크다운과 Git을 자주 사용하는 개발자라면 평소에 쓰던 마크다운 에디터 하나로 CMS를 대체하기 충분하기 때문일 것이다.

가장 인기있는 생성기는 Jekyll지만, Ruby 언어로 되어있기 때문에 남들이 만들어놓은 테마나 플러그인만 끄적이면서 시간 보내지 않으려면 Ruby를 본격적으로 공부하거나 다른 생성기를 찾아야 할 것 같았다.

어차피 사이트에 자바스크립트는 들어갈테니 요새 파고있는 리액트로 직접 만들면 어떨까 싶었지만 싶었지만 이 경우 서버사이드렌더링이 꼭 필요했다.

두번 렌더링한다구요? 네.

사실 서버사이드렌더링은 SPA의 장점을 포기하고 리액트를 템플릿 엔진처럼 사용하는 방법이라고 착각하고 있었지만, Subicura님의 블로그 글을 읽고 제대로 이해하게 됐다.

하지만 리액트 한 번 써보겠다고 블로그에 백엔드까지 추가하기엔 배보다 배꼽이 더 커지는 것 같다.

https://subicura.com/2016/06/20/server-side-rendering-with-react.html


어차피 할 줄 아는게 없으니 다 해보자.

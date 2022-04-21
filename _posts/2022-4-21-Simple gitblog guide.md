---
layout: post
title: Simple gitblog guide
---

## Repository name

- GitID@github.com
- 위와 같이 repository name을 설정하면 깃블로그 주소는 GitID.github.io로 자동 설정

## Theme

- Jekyll-now 적용
  [https://github.com/barryclark/jekyll-now](https://github.com/barryclark/jekyll-now)
- 원하는 테마 fork 또는 download하여 repository에 붙여 넣기

## Blog setting / Posting

- Github repository에서 \_config.yml 내용 수정 (직관적으로 변경 가능)
- Posting의 경우 \_posts 폴더에 .md (markdown) 파일을 추가

## Local 환경 설정

### Ruby 설치

```bash
$ brew install rbenv
$ rbenv versions
```

### Jekyll and plug-ins 설치

```bash
$ gem install github-pages
```

### Jekyll server on

```bash
$ jekyll serve
```



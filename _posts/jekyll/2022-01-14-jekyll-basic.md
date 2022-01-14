---
layout: post
current: post
cover: assets/built/images/jekyll_logo.png
navigation: True
title: jekyll GITBLOG MAINTANANCE
date: 2022-01-14 00:00:00
tags: [jekyll]
class: post-template
subclass: "post tag-python"
author: jwoo5264
---

# GITBLOG MAINTANANCE

---

[https://moon9342.github.io/jekyll-start](https://moon9342.github.io/jekyll-start)

---

## version

[ruby 2.6.9](https://rubyinstaller.org/downloads/)

[node 11.15.0](https://nodejs.org/download/release/v11.15.0/) `[node-v11.15.0-x64.msi](https://nodejs.org/download/release/v11.15.0/node-v11.15.0-x64.msi)다운`

[jekyll](http://jekyllthemes.org/themes/jasper2/)

[lunr.js](https://github.com/iceameri/iceameri.github.io/blob/master/assets/js/lunr.js)

[Google Search Console](https://developers.google.com/search#?modal_active=none)

---

# SETTINGS

## 환경변수

> JEKYLL_ENV / production

![Untitled](assets/built/images/jekyll/jekyll_0.png)

## 명령어

> **_bundle install_**

> **_bundle exec jekyll serve_**

> npm install

css minify (node.js)

> npm install --global gulp-cli
> npm install --save-dev gulp
> gulp-v #(버전확인)
> gulp css #(css 수정후 실행)

> **_gem install rouge_**

rouge 수정

> \*\*\*rougify help style
> rougify style monokai.sublime > assets/css/syntax.css

                     (available themes)***

>

- 바꿀시 syntax.css삭제 후 명령

available themes:
base16, base16.dark, base16.light, base16.monokai, base16.monokai.dark, base16.monokai.light, base16.solarized, base16.solarized.dark, base16.solarized.light, bw, colorful, github, gruvbox, gruvbox.dark, gruvbox.light, igorpro, magritte, molokai, monokai, monokai.sublime, pastie, thankful_eyes, tulip

---

## Gemfile 수정

gem ‘wdm’, ‘≥ 0.1.0’ 추가

> gem ‘wdm’, ‘≥ 0.1.0’

![Untitled](assets/built/images/jekyll/jekyll_1.png)

---

## 수정해야할 부분

1. subscribe 관련한 모든 부분 Search로 수정

```jsx
{% if site.subscribers %}
            <a class="subscribe-button" href="#subscribe">Search</a>
{% endif %}
```

수정한파일

authors.yml

tags.yml

navigation.html

default.html

python-table-of-contents

\_posts/\*

index.md

assets/built/image/\*

assets/css

\_config.yml

Gemfile

search.html

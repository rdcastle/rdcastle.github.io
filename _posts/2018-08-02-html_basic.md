---
layout: post
title: "html_basic"
subtitle: ""
date: 2018-08-02
author: RDcastle
category: html
tags:
finished: true
---

# HTML basic

> 개요

  - 공부순서: 생활코딩(웹앱만들기, HTML), HTML5 교재, 실습

> HTML은 무엇인가?

  - 대표적인 HTML 문서는 index.html 형태로 저장됨
  - 이 index.html 파일은 웹서버의 DocumentRoot 디렉토리(폴더) 하위에 위치한다
  - 각 웹서버마다 DocumentRoot는 다를 수 있다
  - 브라우저가 웹서버에 메인 페이지 호출하면,
  - 웹서버는 가장 먼저 index.html 파일을 읽어들여 브라우저에 전송한다
  - 브라우저는 HTML 문법에 따라 해석하여 페이지 출력

> 기본문법

  1. 기본개념, 링크, HyperTextMarkupLanguage(HTML)
      'Link' 는 HTML 의 본질!
      HTML 의 본질은 웹의 본질! > 결국 링크를 이용한 능동적 페이지변환이 본질

    `HyperText - 문서와 문서가 '링크'로 연결되어 있다는 의미
              - 링크로 인해 여러 문서들이 그물망처럼 연결된 거대한 구조 == 웹
    Markup Language - 언어긴 언어인데 Markup(Tag)된 언어!

          -----------------------------------------
          Markup: 마크업(문서의 활자, 조판 지정 표시)
          Tag: 사람, 사물을 묘사하거나 부가 설명하기 위한 꼬리표, 표시, 어구
          -----------------------------------------

              - 즉, 브라우저에 내가 원하는 내용을 전달하기 위한 문서(마크업)면서
              - 세부적인 묘사나 부가설명을 위한 꼬리표(태그) 기능이 포함된 '언어'

        ex) 안녕하세요 <strong>RDcastle</strong> 입니다
                      시작태그  컨텐트   끝태그`

  2. Tag 상에 HTML 속성 추가하기
      Tag 의 기본적인 문법을 약간 심화시킨 것

    - 'a' Tag: 링크를 나타내는 대표적인 태그
              링크를 타고 또다른 공간(문서)으로 이동할 수 있다
              어디로 가는지 지정해주기 위해 href 속성을 추가해줘야 한다

          ~~~
          RDcastle's main page:
            <strong><a href="http://rdcastle.github.io" target="_blank">여기</a></strong>입니다</p>
          ~~~

    - List Tag: 목록화를 시키기 위한 속성 태그
                <li></li> 사이에 원하는 텍스트를 써주면 된다
                이 리스트들을 순서가 있는 리스트로 그룹화하려면
                'ol' 태그를 사용하고, 아니라면 'ul' 태그를 사용한다
                (ordered list, unordered list 의 약자)

                ~~~
        			<ol>
        				<li>이 페이지는</li>
        				<li>생코에서</li>
        				<li>배운</li>
        			</ol>
        			<ul>
        				<li>문법으로</li>
        				<li>만들어</li>
        				<li>봤습니다</li>
                ~~~

    - 초입에 나온 '!DOCTYPE html' 은 HTML5 표준안을 명시해주는 태그이다
      다른 버전의 표준안들도 존재한다(표현법이 다르다)

    - 'head' 나 'body' 도 일종의 태그이며, 수많은 태그들이 존재한다
      일일히 외우기 보다는 필요에 의해서 하나씩 학습해나갈 것(가벼운 마음으로!)

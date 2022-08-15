---
layout: post
title:  "영어 문서 번역 팁 정리"
---

영어로 된 공식 문서 혹은 스택 오버플로우를 읽다 보면, 매끄럽게 번역하는 방법이 몇 가지 존재한다. 그래서 기억날 때마다 이 포스트에 기록해두고자 한다.

1. ```A defines B... === A is B...```: A는 B를 정의한다 -> A는 B다

    아래는 protocol에 대한 Swift 공식 문서의 설명이다.
    > A protocol defines a blueprint of methods, properties, and other requirements that suit a particular task or piece of functionality.

    이 공식 문서를 친절하게 번역한 [링크](https://jusung.gitbook.io/the-swift-language-guide/language-guide/21-protocols)도 있는데, 여기서는 아래와 같이 번역했다.

    > 프로토콜은 특정 기능 수행에 필수적인 요소를 정의한 청사진(blueprint)입니다.

    실제로 Swift에서의 프로토콜은 일종의 청사진이다. 어떤 개념에 대해 '~을 정의한다'처럼 헷갈리게 표현한 문서가 종종 있는데, 사실상 '~이다'로 해석해도 같은 의미이다.
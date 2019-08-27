---
layout: post
title: IntelliJ 에서 spring-boot-devtools 의 hotswap 기능 활용하기
subtitle: 세팅방법
tags: [spring-boot, spring-boot-devtools, IntelliJ]
---

1. Dependency 추가
    - Gradle 의 경우
        ```groovy
        implementation 'org.springframework.boot:spring-boot-devtools'
        ```

2. Run Configuration 설정
    - ![guide1](img/201908/20190827_01.png)
    
3. Debug 모드로 Boot 구동 후 정상 작동 확인    
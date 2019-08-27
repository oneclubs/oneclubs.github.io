---
layout: post
title: IntelliJ 에서 spring-boot-devtools 의 hotswap 기능 활용하기
subtitle: 세팅방법
tags: [spring-boot, spring-boot-devtools, IntelliJ]
---

#### Add Dependency
- With Gradle
    ```groovy
    implementation 'org.springframework.boot:spring-boot-devtools'
    ```

#### Edit Run Configuration
- [Spring Boot] > Running Application Update Policies
    - On 'Update' action : **Hot swap classes and update trigger file if failed**
    - On frame deactivation : **Update classes and resources**
     
- ![guide1](/img/201908/20190827_01.png)
        
#### Run boot application by debug mode
- change java file and watch what happened. 
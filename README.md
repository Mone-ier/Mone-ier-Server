<h1 align="center">Mone-ier</h1>
<p>
  <a href="https://github.com/Mone-ier/Mone-ier-Server/blob/main/README.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/Mone-ier/Mone-ier-Server/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
</p>

> 스스로 지출을 기록하고 예산 설정, 고정 지출 등을 기록하여 한 눈에 수입과 소비를 모아볼 수 있는 가계부 애플리케이션

### 🏠 [Homepage](https://github.com/Mone-ier/Mone-ier-Server)

## Author

👤 **이소명 (Daisy)**

* Website: https://velog.io/@leesomyoung
* Github: [@LeeSoMyoung](https://github.com/LeeSoMyoung)

## 기술 스택
* Backend Language - Spring Boot 3.0.5
* MySQL 8.0.28
* OS - ubuntu 20.04
* Web Server - NginX 1.18.0

## 📖 project directory
```
Mone-ier-Server
    > gradle
    > src
        >main.java.com.daisy.moneier
            > config
                | BaseException.java Controller, Service에서 Response 용으로 공통적으로 사용 될 익셉션 클래스
                | BaseResponse.java // Controller 에서 Response 용으로 공통적으로 사용되는 구조를 위한 모델 클래스
                | BaseResponseStatus.java // Controller, Service에서 사용 할 Response Status 관리 클래스 
        > main.resources
            | application.properties
            
        > test.java.com.daisy.moneier
            | MoneierApplicationTests.java
    gradlew
    gradlew.bat
    settings.gradle
    build.gradle
    .gitignore // git에 올라가지 않는 파일들
```

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2023 [이소명(Daisy)](https://github.com/LeeSoMyoung).<br />
This project is [MIT](https://github.com/Mone-ier/Mone-ier-Server/blob/main/LICENSE) licensed.

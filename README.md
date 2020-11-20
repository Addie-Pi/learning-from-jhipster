# Learning From JHipster

這是一個學習專欄，會從建立Maven專案開始，然後循序漸進的使用Spring Boot建立一個管理系統。
文章會都放在Medium的平台上： [#learning-from-jhipster](https://medium.com/learning-from-jhipster)

一篇文章一個主題，每個主題會接續前面的主題的程式碼繼續修改，
所以在文章中提到的程式碼都會開branch以方便查看每一次都做了那些修改。

由於Medium的文章列表的使用體驗滿糟糕的XDD，所以這裡會依照文章的次序排列，並加上文章所對應的branch名稱以及每次修改的內容：

| Medium Article | Branch Name | Compare |
| ------ | ------ | ------ |
| [起源](https://medium.com/learning-from-jhipster/%E8%B5%B7%E6%BA%90-10638422db6c) | - | - |
| [JHipster快速介紹(Spring Boot)](https://medium.com/learning-from-jhipster/jhipster%E5%BF%AB%E9%80%9F%E4%BB%8B%E7%B4%B9-spring-boot-4287f29087d0) | [JHipster_0_CreateProject](https://github.com/albert-hg/learning-from-jhipster/tree/JHipster_0_CreateProject) | [link](https://github.com/albert-hg/learning-from-jhipster/compare/master...JHipster_0_CreateProject) |
| [(0) 用Maven建立專案](https://medium.com/learning-from-jhipster/0-%E7%94%A8maven%E5%BB%BA%E7%AB%8B%E5%B0%88%E6%A1%88-1f504f9a712b) |[Spring_0_Maven_CreateProject](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_0_Maven_CreateProject)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/master...Spring_0_Maven_CreateProject) |
| [(1) Maven的生命週期(Phase, Plugin, Goal)](https://medium.com/learning-from-jhipster/1-maven%E7%9A%84%E7%94%9F%E5%91%BD%E9%80%B1%E6%9C%9F-phase-plugin-goal-d69a2591dc45) | - | - |
| [(2) 使用 Maven 將 Plugin Goals 綁定至 Phase](https://medium.com/learning-from-jhipster/2-%E5%B0%87-plugin-goals-%E7%B6%81%E5%AE%9A%E8%87%B3-phase-13c6b6b8d9bd) | [Spring_1_Maven_BindGoalsToPhase](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_1_Maven_BindGoalsToPhase) | [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_0_Maven_CreateProject...Spring_1_Maven_BindGoalsToPhase) |
| [(3) 使用 Maven Wrapper](https://medium.com/learning-from-jhipster/3-%E4%BD%BF%E7%94%A8-maven-wrapper-f4b7e460278) | [Spring_2_MavenWrapper](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_2_MavenWrapper)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_1_Maven_BindGoalsToPhase...Spring_2_MavenWrapper) |
| [(4) Java Web 的歷史淵源](https://medium.com/learning-from-jhipster/4-java-web-%E7%9A%84%E6%AD%B7%E5%8F%B2%E6%B7%B5%E6%BA%90-2e324135c808) | - | - |
| [(5) 建立 Spring Boot 專案](https://medium.com/learning-from-jhipster/5-%E5%BB%BA%E7%AB%8B-spring-boot-%E5%B0%88%E6%A1%88-e7291a050ea1) | [Spring_3_ImportSpringBoot](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_3_ImportSpringBoot)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_2_MavenWrapper...Spring_3_ImportSpringBoot) |
| [(6) Web Starter開發API - Controller](https://medium.com/learning-from-jhipster/6-web-starter%E9%96%8B%E7%99%BCapi-controller-2c0e46cac7ed) | [Spring_4_UsingWebStarter](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_4_UsingWebStarter)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_3_ImportSpringBoot...Spring_4_UsingWebStarter) |
| [(7) 使用 Springfox 導入Swagger 3.0.0](https://medium.com/learning-from-jhipster/7-%E4%BD%BF%E7%94%A8-springfox-%E5%B0%8E%E5%85%A5swagger-3-0-0-e1067cb1c565) | [Spring_5_ImportSwagger](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_5_ImportSwagger)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_4_UsingWebStarter...Spring_5_ImportSwagger) |
| [(8) Spring Boot的Properties與Profile](https://medium.com/learning-from-jhipster/8-spring-boot%E7%9A%84properties%E8%88%87profile-8cab3cd06856) | [Spring_6_SpringProperties](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_6_SpringProperties)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_5_ImportSwagger...Spring_6_SpringProperties) |
| [(9) Java Logging 的歷史與戰爭](https://medium.com/learning-from-jhipster/9-java-logging-%E7%9A%84%E6%AD%B7%E5%8F%B2%E8%88%87%E6%88%B0%E7%88%AD-e18150540d29) | - | - |
| [(10) Spring Boot 預設使用的 Logging 探討](https://medium.com/learning-from-jhipster/10-spring-boot-%E9%A0%90%E8%A8%AD%E4%BD%BF%E7%94%A8%E7%9A%84-logging-%E6%8E%A2%E8%A8%8E-8cb7a9738484) | [Spring_7_DefaultLogging](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_7_DefaultLogging)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_6_SpringProperties...Spring_7_DefaultLogging) |
| [(11) Spring Boot 使用 Logback 或 Log4j2](https://medium.com/learning-from-jhipster/11-spring-boot-%E4%BD%BF%E7%94%A8-logback-%E6%88%96-log4j2-e655b320a2c8) | [Spring_8_UsingLogging](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_8_UsingLogging)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_7_DefaultLogging...Spring_8_UsingLogging?diff=split) |
| [(12) Spring Boot 使用 Devtools](https://medium.com/learning-from-jhipster/12-spring-boot-%E4%BD%BF%E7%94%A8-devtools-ece4df0de531) | [Spring_9_SpringBootDevtools](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_9_SpringBootDevtools)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_8_UsingLogging...Spring_9_SpringBootDevtools) |
| [(13) 甚麼是 JDBC、ORM、 JPA、ORM框架、Hibernate](https://medium.com/learning-from-jhipster/13-%E7%94%9A%E9%BA%BC%E6%98%AF-jdbc-orm-jpa-orm%E6%A1%86%E6%9E%B6-hibernate-c762a8c5e112) | - | - |
| [(14) 深入 JDBC、Connection Pool，並導入 H2 DB](https://medium.com/learning-from-jhipster/14-%E6%B7%B1%E5%85%A5-jdbc-connection-pool-%E4%B8%A6%E5%B0%8E%E5%85%A5-h2-db-939adee9c50) | [Spring_10_ImportH2DB](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_10_ImportH2DB)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_9_SpringBootDevtools...Spring_10_ImportH2DB) |
| [(15) Spring Boot 連接至 PostgreSQL 與 HikariCP 的常見使用設定](https://medium.com/learning-from-jhipster/15-spring-boot-%E9%80%A3%E6%8E%A5%E8%87%B3-postgresql-%E8%88%87-hikaricp-%E7%9A%84%E5%B8%B8%E8%A6%8B%E4%BD%BF%E7%94%A8%E8%A8%AD%E5%AE%9A-546bba379c8e) | [Spring_11_ConnectToPostgreSQL](https://github.com/albert-hg/learning-from-jhipster/tree/Spring_11_ConnectToPostgreSQL)| [link](https://github.com/albert-hg/learning-from-jhipster/compare/Spring_10_ImportH2DB...Spring_11_ConnectToPostgreSQL) |


| [<ArticleName>](<link>) | [<BranchName>](<link>)| [link](<compareLink>) |
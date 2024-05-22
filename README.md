[SPRING-DATABASE]

### Docker
### Services : mysql, redis, app  
  

---
### BootRun X / BootJar 사용
이름을 app.jar / (build.gradle.kts)
```kotlin
tasks.named<BootJar>("bootJar") {
archiveFileName.set("app.jar")
}
```
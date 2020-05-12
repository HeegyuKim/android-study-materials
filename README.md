# android-study-materials
개인적으로 공부하면서 안드로이드 학습에 유용하다고 생각되는 자료들을 모았습니다.<br>

## Gradle
맨날 쓰는 그래들이지만 제대로 된 사용법도 몰랐고 Kotlin으로 그래들 파일을 만들 수도 있었네요.
- [Gradle Tutorial for Android: Getting Started](https://www.raywenderlich.com/249-gradle-tutorial-for-android-getting-started)<br>
- [Gradle's Kotlin DSL](https://medium.com/swlh/gradles-kotlin-dsl-buildsrc-4434100a07d7)

## Kotlin
- [Kotlin KTX](https://developer.android.com/kotlin/ktx)

### Coroutine
- [viewModelScope()](https://developer.android.com/kotlin/ktx#viewmodel) - viewModelScope() 함수는 백그라운드 스레드에서 네트워크 요청을 하는 코루틴을 실행합니다. 라이브러리는 모든 설정 및 상응하는 범위 삭제를 처리합니다.

### Flow
RxJava를 대체할 Kotlin의 무기인듯?? 기존 코루틴으로는 조금 부족했던 RxJava의 기능들을 제공...
- https://proandroiddev.com/kotlin-flow-benefits-over-rxjava-b220658f1a92
## Android Runtime(ART)
### DalvikVM, APK, AAB

- [DVM vs JVM](https://towardsdatascience.com/jvm-vs-dvm-b257229d18a2)
- [안드로이드 컴파일 방식](https://medium.com/@logishudson0218/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-%EC%BB%B4%ED%8C%8C%EC%9D%BC-%EB%B0%A9%EC%8B%9D-dalvikvm-art-b5d64350489f)

APK

## Android Architecture Component(AAC)
### Navigation
- [[Android Jetpack] AAC Navigation Component - 1. Navigation 소개,구성 및 개요 , BackStack관리](https://namjackson.tistory.com/28)
### LiveData
- [LiveData - (developer.android.com)](https://developer.android.com/topic/libraries/architecture/livedata?hl=ko)
### ViewModel


## Pattern and Architecture
### ReactiveX
- [RxJava Github](https://github.com/ReactiveX/RxJava)
- [RxJava란? - 기본구조](https://juyoung-1008.tistory.com/38)
- [리액티브 프로그래밍 도입기: 사운드 클라우드 아키텍처(realm.io)](https://academy.realm.io/kr/posts/gotocph-mattias-kappler-reactive-architecture-android/)

### Dependency Injection(DI)
#### Dagger
- [Dagger Github](https://github.com/google/dagger)
- [(번역)쉬운 Dagger2](http://pluu.github.io/blog/android/2017/01/12/android-dagger/)
- [[Android, Dagger2] DI 기본 개념과 Dagger2 사용 예제 - 놈!놈!놈!](https://black-jin0427.tistory.com/104)

#### Koin

### 


## Database
### Room
### Realm
- [Realm](https://realm.io/docs/java/latest/)

## Image
### Glide
- [Glide](https://github.com/bumptech/glide)
### Fresco
- [Fresco](https://frescolib.org/)

## Network
### OkHttp
### Retrofit2

## CI & CD
### Unit Test
- [JUnit5](https://johngrib.github.io/wiki/junit5-nested/)
- [Spek Framework](https://www.spekframework.org/specification/)

### CircleCI
- [안드로이드 앱 품질 높이기](https://www.androidhuman.com/lecture/quality/2016/10/03/android_quality_part1_circleci/)
- [CircleCI로 GitHub CI 구성](https://blog.themuser.xyz/circleci%EB%A1%9C-github-ci-%EA%B5%AC%EC%84%B1/)

## 개발 방법론
### TDD
### BDD

# 좋은 글
- [Software Engineer Leveling Matrix](https://h3h.github.io/leveling-matrix/?fbclid=IwAR2hnMZK8uFiOpjSTWRW_IbwX5Wxt200kZ3VcSr_gaaA4oCvNgmiobphkqk)

# TODO
- Android Lint
- Unit Test, UI Test
- Architectrue(MVVM, MVI)
- 방법론
- ART, DVM
설명도 같이 쓰면 좋을듯

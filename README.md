# help
org 관리를 위한 정보 모음

## Packages

### Gradle 에서 Github Packages 로 배포하기.
> [공식문서](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-gradle-registry)

#### 배포하기
1. `plugins` 에 `id 'maven-publish'` 추가
2. `publishing` 추가하며, github packages 주소와 접속계정 설정
#### 사용하기
1. `repositories` 에 github packages 주소와 접속계정 설정
2. gradle refresh 로 라이브러리 잘 가져오는지 확인



## Cody
Tools for publishers

## Warning
  - 이 프로젝트는 완전히 작성되지 않았습니다. 그러므로 완전히 잘되진 않습니다.
  - Windows는 아직 지원하지 않습니다. (앞으로는 할 예정)

## 사용법

##### 1. install ruby
do it your self, please

##### 2. initialize cody
```sh
./cody setup
```

##### 3. start cody
```sh
./cody
```
##### 4. livereload


##### 5. deploy your code
```sh
./cody deploy [folder path]
```

### Deploy시 주의할점
  - _ 로 시작되는 폴더는 템플릿용 폴더로 간주하고 삭제됩니다.

## Todo
#### 우선순위 높음
  - 서버랑 바인딩
  - OSX 작동여부 확인
  - 실제 프로젝트 적용후 여러가지 테스트(5.14일부터)

#### 우선순위 낮음
  - less, coffeescript 지원
  - Gemfile, Guardfile등이 들어나지 않고 사용
  - cody_conf.json 생성되도록 만들기
  - 잼으로 배포하거나 말거나

## feature
  - code complie
  - live reload
  - Cody::ERB extend syntex
    - layout
    - block
    - include
    - partial (검증이 완전히 안됨)
    - model
  - Cody::Deploy (incomplete)

## Supported compile format
  - erb
  - scss
  - js

## Will support format
  - Less
  - Coffee Script

## gemfile
ERB부분만 제가 작성하였고 그외의 부분은 잼을 사용합니다.
  - compass
  - therubyracer
  - uglifier
  - guard
  - guard-sass
  - guard-uglifier
  - guard-livereload
  
## will use gemfile
  - less
  - guard-less
  - coffeescript
  - guard-coffeescript
  
# 손상배 201840119

## [10월 06일]
> **학습내용**

### > npm install axios

  axios 설치

브라우저 주소창에 [**yts.ls**](http://yts.ls) 라고 입력 영화 데이터 api 사이트 접속

api 를 사용하려면 axios 를 import 한 다음 , componentDidMount()함수에서

axios로 api를 호출

```jsx
import axios from "axios"

componentDidMount(){
	//영화 데이터 로딩
	axios.get('https://yts.mx/api/v2/list_movies.json')}
```

시간이 필요하다는 것을 알리기 위해서는 async, await 키워드가 필요

자바스크립트에게 시간이 필요하다는 것을 알리려면 async 를 ()앞에 붙이고,

실제 시간이 필요한 대상인 axios.get() 함수에는 await를 붙인다

```jsx
getMovies = async() => {
	const movies = await axios.get('https://yts.mx/api/v2/list_movies.json')
}

componentDidMount() {
	this.getMovies()
}
```

### > npm install axios

  axios 설치

브라우저 주소창에 [**yts.ls**](http://yts.ls) 라고 입력 영화 데이터 api 사이트 접속

api 를 사용하려면 axios 를 import 한 다음 , componentDidMount()함수에서

axios로 api를 호출

```jsx
import axios from "axios"

componentDidMount(){
	//영화 데이터 로딩
	axios.get('https://yts.mx/api/v2/list_movies.json')}
```

시간이 필요하다는 것을 알리기 위해서는 async, await 키워드가 필요

자바스크립트에게 시간이 필요하다는 것을 알리려면 async 를 ()앞에 붙이고,

실제 시간이 필요한 대상인 axios.get() 함수에는 await를 붙인다

```jsx
getMovies = async() => {
	const movies = await axios.get('https://yts.mx/api/v2/list_movies.json')
}

componentDidMount() {
	this.getMovies()
}
```

## [9월 29일]
> **학습내용**
## 상대경로 이미지 삽입 방법

public 폴더에 image 폴더 생성

<img src="image/[이미지이름]"> 형태로 태그를 작성하면 된다.

---

**npm install prop-types**

Pakage.json 파일을 열어 dependencies 키에 있는 값을 살펴보자

Prop-types가 등록되어 있으면 정상적으로 설치 완료

Prop-types는 컴포넌트가 전달받은 props가 원하는값인지 확인해 주는 역할을 한다.

### prop-types 적용하기

importPropTypes from 'prop-types'; 를  App.js 파일 맨위에 추가

## state로 숫자 증감 기능 만들어 보기

- props는 정적인 데이터만 다룰수 있다
- state는 동적인 데이터를 다루기 위해 사용된다.
- state는 class형 컴포넌트에서 사용된다.

---

##**[09월 08일]
> 학습내용**

**npx create-react-app name** 

*으로 터미널 실행 앱만들기*

1. 프로젝트 폴더는 node_modules, public, src로 이루어져 있다
2. 이 중 node modules는 사용 x 주로 public src사용

npm start 로 서버실행

##[09월 01일]
>학습내용
>

###  node 최신 다운로드 및 설치

[NodeJs 다운로드](https://nodejs.org/ko/ "다운로드") 

```
node -v // 최신인지 버전확인
```

[Vue.js 바로가기](https://kr.vuejs.org/v2/guide/index.html "가이드")

### vue 설치하기

```
npm install vue
npm install -g @vue/cli
```

### vue cli 업그레이드

```
npm update -g @vue/cli
```

### vue 프로젝트 생성
```
vue create 프로젝트명
```

### vue 실행
```
npm run serve
 local - http://localhost:8080/ 
```
### vue 빌드

```
npm run build
```

### Vue 디버깅툴
[여기](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)

```
크롬 개발자 도구에서 Vue 확인 가능
```

### vue UI 
VUE CLI용 새로운 시각적 애플리케이션인 Vue UI를 사용해서 설치 가능함
```
vue ui
 Vue 사용자 인터페이스가 시작되고 브라우저에서 새 창 열림. 
```


###  플러그인
```
vue add vuetify
vue add router
vue add vuex (중앙집중방식의 데이터 처리 및 공유를 위한 플러그인
vue add axios   (데이터 로딩 및 업로드 처리 플러그인)
```


### 폴더구조
```
├── dist // 빌드시 최후로 생성되는 디렉토리
│   ├── css
│   ├── img
│   └──  js
├── public
│   └── index.html -->  HTML 시작 페이지
├── src
│   ├── assets --> 공용 css 파일이나 이미지
│   ├── components --> 여러페이지에서 공용으로 사용하는 컴포넌트 모아둠
│   ├── plugins 
│   ├── router --> 라우터 설정관리
│   ├── store ---> ??
│   ├── views ---> Vue 파일관리
│   ├── app.vue ---> 최상위 vue 파일
│   └── main.js --> vue 인스턴스를 새로 만들고 시작하는 부분, 전역으로 처리하는 부분은 여기서 처리
├── package.json --> npm 의존성 모듈 목록 및 프로젝트 기본 설정 포함.
└── README.md
```
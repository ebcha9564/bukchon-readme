# 북촌한옥 마을 소개 웹사이트

## 프로젝트 소개
- 프로젝트 목적: 외국인 관광객을 대상으로 북촌한옥마을의 전통미와 관광정보를 시각적으로 효과적으로 전달하기 위한 웹사이트 제작
- 기획 방향:
  - 한국 전통 건축의 미(美)와 현대적 UI의 조화
  - 전통문화에 대한 이해를 돕고 방문을 유도하는 사용자 흐름 설계
  - 다양한 디바이스에서 최적화된 반응형 웹 구현
- 이 프로젝트는 외국인 관광객을 타깃으로, 한국의 전통 문화와 한옥의 매력을 효과적으로 소개하기 위한 북촌한옥마을 웹사이트 리디자인 작업이었습니다
- 용자가 한옥과 전통문화에 대해 자연스럽게 흥미를 느끼고 실제 방문까지 이어질 수 있도록, 정보 전달력과 시각적 몰입감을 동시에 고려한 구성에 중점을 두었습니다.

## 팀원 구성

## 1. 개발 환경
- Front : HTML, SCSS, JavaScript ES6+, Swiper.js, Fullpage.js
- 버전 및 이슈관리 : Github, Github Project
- 협업 툴 : Notion, Github Wiki
- 서비스 배포 환경 : Netlify
- 디자인 : Figma

## 2. 채택한 개발 기술과 브랜치 전략
### Css Preprocessor:
- SCSS(Sass)는 CSS의 확장 언어로, 더 구조적이고 효율적인 스타일링 작업을 가능하게 해줍니다. 이번 프로젝트에서는 유지보수성과 재사용성을 고려해 SCSS를 채택했습니다. 변수, 중첩(Nesting), 믹스인(Mixin), 분리된 파일 구조(Partial & Import)를 활용함으로써 복잡한 스타일 코드도 논리적으로 정리할 수 있었고, 동일한 스타일 속성을 반복적으로 작성하는 시간을 줄일 수 있었습니다. 특히 반응형 웹 구현 시 미디어 쿼리를 컴포넌트별로 정리하고, 색상이나 간격 같은 디자인 토큰을 변수로 관리할 수 있어 협업과 유지보수에 큰 이점을 얻을 수 있었습니다.
### 브랜치 전략
- Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용했습니다.
- main, develop, Feat 브랜치로 나누어 개발을 하였습니다.
- main 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
- develop 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
- Feat 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 각 브랜치를 삭제해주었습니다.
## 3. 프로젝트 구조
├── README.md
├── .eslintrc.js
├── .gitignore
├── .prettierrc.json
├── package-lock.json
├── package.json
│
├── public
│    └── index.html
└── src
     ├── App.jsx
     ├── index.jsx
     ├── api
     │     └── mandarinAPI.js
     ├── asset
     │     ├── fonts
     │     ├── css_sprites.png
     │     ├── logo-404.svg
     │     └── logo-home.svg
     │          .
     │          .
     │          .
     ├── atoms
     │     ├── LoginData.js
     │     └── LoginState.js
     ├── common
     │     ├── alert
     │     │     ├── Alert.jsx
     │     │     └── Alert.Style.jsx
     │     ├── button
     │     ├── comment
     │     ├── inputBox
     │     ├── post
     │     ├── postModal
     │     ├── product
     │     ├── tabMenu
     │     ├── topBanner
     │     └── userBanner
     ├── pages
     │     ├── addProduct
     │     │     ├── AddProduct.jsx
     │     │     └── AddProduct.Style.jsx
     │     ├── chatList
     │     ├── chatRoom
     │     ├── emailLogin
     │     ├── followerList
     │     ├── followingList
     │     ├── home
     │     ├── join
     │     ├── page404
     │     ├── postDetail
     │     ├── postEdit
     │     ├── postUpload
     │     ├── productEdit
     │     ├── profile
     │     ├── profileEdit
     │     ├── profileSetting
     │     ├── search
     │     ├── snsLogin
     │     └── splash
     ├── routes
     │     ├── privateRoutes.jsx
     │     └── privateRoutesRev.jsx  
     └── styles
           └── Globalstyled.jsx
## 4. 역할 분담

## 5. 개발 기간 및 작업 관리




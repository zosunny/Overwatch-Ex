# Overwatch-Ex

## 프로젝트 리팩토링(Refactoring)
즉, 결과의 변경 없이 코드의 구조 재조정

### 1. css -> scss
1) npm 프로젝트로 변환
```bash
npm init -y
npm i parcel-bundler -D
```
2) main.css -> main.scss 로 변환
3) package.json
```json
"scripts": {
    "dev": "parcel index.html",
    "build": "parcel build"
  },
```
4) index.html에서 파일명 변경
```html
<!-- <link rel="stylesheet" href="./main.css">  -->

<link rel="stylesheet" href="./main.scss">
```

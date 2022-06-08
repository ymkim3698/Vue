***

## VisualStudio Code : `Start Vue`

[VS Code Vue install guide](https://haenny.tistory.com/247?category=899432)

[Node js install guide](https://haenny.tistory.com/245?category=802977)

1. `Node js` 설치
2. VS Code -> 플러그인
> 1. Vetur
> 2. HTML CSS Support
> 3. Vue 3 Snippets
3. VS Code -> 터미널
* `node --version, npm --version`
4. `npm install -g @vue/cli`
5. `vue create my-app`
* 방향키로 Vue3 선택 후 Enter

## 서버 시작

1. VS Code -> 터미널
2. cd my-app
3. `npm run serve`

## 서버 종료

1. VS Code -> 터미널
2. `Ctrl + C` -> y

## Git 연동

1. git 설치
2. github 레파지토리 생성 - `기본설정`
3. VS Code -> 터미널
4. cd my-app
5. `git init`
6. `git remote add origin [url]`
7. `git add .`
8. `git commit -m "[comment]"`
9. `git push origin master`
* 단계 별로 천천히 진행 추천

***

# my-app

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

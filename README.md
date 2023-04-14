# monorepo
모노레포를 최대한 빠르게 만들어보자

## 순서 (Commit 순)

1. yarn set version berry (폴더 초기화)
2. yarn init (폴더 초기화)
3. package.json에 workspaces 작성
4. 첫 프로젝트 package/project1 을 생성 (yarn create vite)
5. 첫 프로젝트에서 yarn
6. root에서 yarn add -D typescript prettier eslint
7. root에서 yarn dlx @yarnpkg/sdks vscode (꼭 6번 한 후 하기)
8. tsconfig를 root(base)와 package project(extends)로 구분
9. 공용 모듈 프로젝트 생성 package/common 에 yarn init
10. package/common에 모듈 하나 생성하고, package/project1에 연동
11. package/project1 혹은 package/common에서 yarn 하면 둘이 연동됨
12. common에 있는 모듈불러오는 방법

## 참고 자료

https://minify.tistory.com/40

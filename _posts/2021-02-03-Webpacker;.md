---
layout: post
title: 2021-02-03
category: 공부 기록
tag: [Webpecker, github.io, Lanyon, Rails, error]
---

Rails - 다양한 오류.. 
github.io 개발블로그 다시 구성 - Lanyon 테마 사용

### Rails ERROR

You could try using --skip-broken to work around the problem -> 해결안됨 <br>
Nodejs 삭제 후 다시 시도 -> 성공 <br>
참고 링크<br>
[nodejs 최신 버전 설치](https://coding-ggangfe.tistory.com/39)<br>
[npm, node 삭제](https://blog.daum.net/dosman1/2003)<br>
[npm 설치](https://mainia.tistory.com/5637)<br>

#### Webpacker::Manifest::MissingEntryError in Articles#index 오류<br>
error Command "webpack" not found.<br>
-> yarn run test (https://classic.yarnpkg.com/en/docs/cli/run) <br>
->command not found: babel<br>
@babel/plugin-transform-destructuring' <br>
@babel/plugin-transform-runtime<br>
@babel/plugin-transform-regenerator<br>
@babel/preset-env'<br>
Bable 플러그인 오류 다수 <br>

#### @rails/webpacker' from 'config/webpack/environment.js 오류<br>
->webpack-cli Error BrowserslistError: 오류<br>
->webpack 5.20.1 compiled successfully in 64 ms <br>
webpack 오류 해결 완료 <br>
webpack -w  [참고링크](https://www.inflearn.com/questions/17158)

#### WARNING in configuration -> 해결
The 'mode' option has not been set, webpack will fallback to 'production' for this value. Set 'mode' option to 'development' or 'production' to enable defaults for each environment.
You can also set it to 'none' to disable any default behavior. Learn more: https://webpack.js.org/configuration/mode/ 

ERROR in main 
Module not found: Error: Can't resolve './src' in '/Users/son-eunsu/RubymineProjects/blog1'

실패
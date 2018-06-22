# Webpack 간단 요약

![image](https://trello-attachments.s3.amazonaws.com/5af268949010e31ac06a7770/5aff04c0111c9efc2102804d/698df8db42652ec031b93b8952bfbfe8/what-is-webpack.png)

## 정의 
서로 연관 관계가 있는 웹 자원들을 js, css, img와 같은 static한 자원으로 변환해주는 모듈 번들러. 코드베이스가 커지면 필연적으로 코드를 쪼개는 행위(코드의 모듈화)가 필요하다. 이 모듈들 사이에 의존성이 존재 할 것이며 모듈간의 의존성을 해석하고 잘 작동하는 정적 에셋으로 만드는 과정이 모듈 번들링이다.

## 사용 이유
1. Web Task manager + 모듈 관리
2. 자바스크립트 모듈화의 필요성(전역 변수 충돌, 로딩 순서 등!)
3. 모듈간의 관계를 청크(chunk) 단위로 나눠 필요할 때 로딩

## 철학
1. 모든것이 모듈!(js, css, html ... )
2. Load only "what" you need and "when" you need(초기에 모든것을 읽어들이지 않는다!)
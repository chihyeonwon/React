## 리액트 프로젝트
[스타일 참고한 레포지토리](https://github.com/AlanBinu007/Netflix_Clone_ReactJs)
```
스타일을 참고한 레포지토리에서 적당히 원하는 스타일로 고쳐서 만든 프론트엔드 작업영역이다.
```
## API 연결하기
#### constants.js
![image](https://github.com/chihyeonwon/React/assets/58906858/024f99d0-3342-4247-82d4-ec27f1414785)
```
API 폴더의 constants.js 파일에서 YOUR-API-URL 부분을 호스팅 중인 도메인 주소(http://www.oneflix.link)로 수정한다. 
```
## GitHub Pages로 배포하기
![image](https://github.com/chihyeonwon/React/assets/58906858/0cceb3f1-5cf9-43a4-97d5-c3b8bc995001)
```
리포지토리의 Setting - GitHub Pages - Branch 에서 None으로 되어있는 부분을 main으로 수정하고 save한다.
```
#### package.json 수정
![image](https://github.com/chihyeonwon/React/assets/58906858/3270c042-d069-4b82-b1c1-c0cf6c260bcb)
```
package.json의 homepage 항목의 YOUR-GITHUB-PAGES-URL 부분을 리포지토리 설정에 해당하는 URL로 바꿔준다.
http://chihyeonwon.github.io/React
```
#### yarn 설치
![image](https://github.com/chihyeonwon/React/assets/58906858/9848de54-923f-43f8-874c-5c0ef8c6e237)
```
터미널에 다음 명령어를 입력하여 yarn 패키지를 먼저 설치한다. 
```
#### yarn deploy
![image](https://github.com/chihyeonwon/React/assets/58906858/7aaf6869-66ff-4e1f-9a3c-64aaf3af4928)
![image](https://github.com/chihyeonwon/React/assets/58906858/0fb754da-cfc0-4536-934f-9fc1b1014c32)
```
yarn deploy 명령어를 사용하여 GitHub Pages에 배포가 되면 아래와 같은 메시지가 나온다.
```
#### gh-pages Branch 변경
![image](https://github.com/chihyeonwon/React/assets/58906858/f37aa77f-8c63-4c53-a206-9620a625d395)
```
다시 GitHub Pages로 와서 브랜치를 main에서 yarn deploy 명령어 이후에 새롭게 생긴 gh-pages 브랜치로 설정한다.
```
#### yarn deploy

```
다시 한번 deploy 명령어를 실행한다.
```

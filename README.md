React Webpack - Template
======================
React로 Front-end UI 개발을 시작할 때 기본적으로 사용할 템플릿 프로젝트입니다.<br>
하나의 번들로 묶어 배포 할 서비스를 설정하여 사용합니다.<br>
배포되는 산출물은 pureye4u에 의해 개발/관리되며 자유롭게 사용할 수 있습니다.<br>
단, pureye4u의 동의 없이 임의로 수정하여 사용된 코드에 대해서는 유지보수 및 산출물의 품질을 보증할 수 없으니,<br>
추가/수정 요청 및 문의, 버그 신고는 [[Issues]](https://github.com/pureye4u/webpack-react-default/issues)을 이용해주세요.<br>
<br>
##개발 프로세스
1. Template 프로젝트에 작성되어 있는 node.js package 설정 파일을 수정해주세요<br>
- 해당 서비스 또는 프로젝트에 맞게 package.json 파일을 열어  name, version, description, repository 항목을 수정합니다.<br>
2. node.js 모듈을 설치해주세요<br>
- 프로젝트 디버깅과 빌드를 위해 사용되는 기본 node.js package 들을 설치합니다.<br>
: $ npm install<br>
3. html, css, image 와 같은 Asset 요소들을 작성합니다.<br>
- ./src/www/ 하위에 작성<br>
4. ECMA6 Script 문법을 사용하여 웹 어플리케이션을 개발합니다.<br>
- ./src/app/ 하위에 작성, 처음 엑세스하는 루트 파일은 app.js 입니다.<br>
5. 개발 테스트를 진행합니다.<br>
- Webpack Dev Server 를 사용하여 개발한 내용을  테스트합니다.<br>
: $ npm start<br>
6. 번들을 만듭니다.<br>
- 개발이 완료되면 번들로 빌드합니다.<br>
: $ npm run build<br>
7. 웹 어플리케이션을 배포합니다.<br>
- 완성된 번들을 서비스에 반영하기 위해 배포를 진행합니다.<br>
- ./build 를 웹서버에 연결합니다.<br>

<div align=center>
  <h2>💚Vue.js로 만든 웹을 배포하기💚</h2>
  <br>
  <h3>1. 서버가 있는 웹 사이트</h3>
  <ul>
    <li>New Terminal => npm run build 입력</li>
    <li>dist 폴더에 있는 HTML, CSS, JS 파일을 서버에 업로드한다.</li>
  </ul>
  <br>
  <hr>
  <h3>2. 서버가 없을 때 깃허브에 배포</h3>
  <ul>
    <li>레퍼지토리를 생성</li>
    <li><strong>vue.config.js 파일을 생성한 뒤 레퍼지토리 경로를 입력한다.</strong>
        <p>module.exports={ 
              publicPath: '/vue_blog_published',
           }
        </p>
    </li>
    <li>New Terminal => npm run build 입력</li>
    <li>dist 폴더에 있는 HTML, CSS, JS 파일을 레퍼지토리에 업로드</li>
    <li>레퍼지토리 => settings => Pages => branch main으로 변경 후 save!</li>
  </ul>

</div>

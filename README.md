# delivery-site
포트폴리오를 위한 프로젝트(배달의 민족 웹사이트)
배달의 만족은 6인으로 구성된 팀에서 구현하였습니다.<br/>
동영상 시연 링크 : https://youtu.be/KG3El0cXFDA <br/>

[이방원(본인)이 구현한 부분]<br/>
▷ findid_pw.jsp, findid_pw_ok.jsp, findid_pw_ok2.jsp (계정 아이디 및 패스워드 찾는 기능 <br/> 
▷ info_modi.jsp, info_modi_ok.jsp (계정 정보 수정 기능)<br/> 
▷ inquire_history_regist.jsp, inquire_history_regist_ok.jsp (1:1 문의 기능) <br/>
▷ mypage_login.jsp, mypage_login_ok.jsp(마이페이지 들어가기 전 다시 한 번 로그인하는 기능) <br/>


<br/>

#### 1) 프로젝트 구조도(흐름도)
<br/>


![배민 구조도](https://user-images.githubusercontent.com/74960408/146306733-43f86760-1808-460c-8de3-69fbf8f8806e.jpg)


#### 2) 프로젝트 구현 (작성자가 작업한 것 위주)

(1) 계정 찾기
<br/>

![edit_myInfo](https://user-images.githubusercontent.com/74960408/146307224-b05fab7f-184b-4753-8de2-a21edd9e4ffa.jpg)

<br/>

위의 페이지는 아이디를 찾는 페이지이다. 위의 입력란에 정보를 입력하면 된다.

<br/>

![id](https://user-images.githubusercontent.com/74960408/146307390-274b018a-ea5d-4f04-aba7-145f2a5d6588.jpg)

<br/> 
위의 페이지는 이전에 입력한 정보로 찾은 아이디이다.
<br/>
<br/>
(2) 1:1 문의하기
<br/>

![moon2_write](https://user-images.githubusercontent.com/74960408/146307581-e8516db4-166a-484f-8338-84fee7ada36e.jpg)

<br/>
1:1문의 페이지에서 [질문하기] 버튼을 클릭하면 위와 같이 질문을 할 수 있도록 구현돼있다.
<br/>
<br/>

![moon2_list](https://user-images.githubusercontent.com/74960408/146307750-20b0040e-8bd1-4257-aefd-2af4724ce179.jpg)

<br/>
질문하기를 통해 질문을 남기면 위와 같은 질문내용과 답변 대기 중의 내용을 볼 수 있다.
<br/>
<br/>
(3) 정보수정하기
<br/>

![edit_myeveryThing](https://user-images.githubusercontent.com/74960408/146307841-7e6d8921-86d6-405e-ab1d-698e35ff3093.jpg)

<br/>
위의 페이지는 접속유저의 정보를 수정하는 기능을 가지고 있다.<br/>
비밀번호 외의 다른 목록에는 db에 있는 기존의 정보(변경하려고 하기 전의 정보)가 입력되어져 있다. 

<h1>힐링주 - <img style="width:50px; height:50px;" src="https://github.com/user-attachments/assets/13580612-435b-47c5-8b11-b18fa0ec6d9f"></h1>

환경문제와 더불어 늘어나는 멸종 위기 동물을 보호하고 관리하는 시설로 개설된 동물원으로서 더 많은 이용객에게 홍보하고, 방문객 수를 늘릴 수 있도록 한 웹 서비스입니다.

기간 : 6/28 ~ 7/19  참여 인원 : 5명
<hr/>
<h1><img style="width:50px; height:50px;" src="https://github.com/user-attachments/assets/910bd2e9-b86c-4e64-93a6-d6a81d062410">&nbsp;&nbsp;&nbsp;&nbsp;목차</h1>
1.기술스택<br/><br/>
2.프로젝트 주요 기능<br/><br/>
3.ERD 설계도<br/><br/>
4.맡은 기능<br/><br/>
5.기능별 코드 소개<br/><br/>
<hr/>
<h2>1.사용 기술 스택</h2>

<h3 align="center">>운영체제</h3>
<div align="center">
  <img src="https://img.shields.io/badge/window 10-3A76F0?style=flat-square" height="25">
</div><br/>
<h3 align="center">>FrontEnd</h3>
<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white" height="25">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" height="25">
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" height="25">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white" height="25">    
</div><br/>
<h3 align="center">>BackEnd</h3>
<div align="center">
  <img src="https://img.shields.io/badge/java 11-4B4B77?style=flat-square" height="25">
  <img src="https://img.shields.io/badge/oracle sql-4479A1?style=for-the-badge&logo=mysql&logoColor=white" height="25">
</div><br/>
<h3 align="center">>FrameWork/Library</h3>
<div align="center">
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" height="25">
  <img src="https://img.shields.io/badge/myBatis-333333?style=flat-square" height="25">
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" height="25">
</div><br/>
<h3 align="center">>DataBase</h3>
<div align="center">
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" height="25">
</div><br/>
<h3 align="center">>Tool</h3>
<div align="center">
  <img src="https://img.shields.io/badge/sqlDeveloper-4479A1?style=flat-square" height="25">
</div><br/>
<h3 align="center">>WAS</h3>
<div align="center">
  <img src="https://img.shields.io/badge/apachetomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white" height="25">  
</div><br/>
<h3 align="center">>Collaboration</h3>
<div align="center">
  <img src="https://img.shields.io/badge/googledrive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" height="25">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" height="25">
  <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" height="25">
  <img src="https://img.shields.io/badge/erdcloud-000000?style=flat-square" height="25">
</div>
<hr/>
<h1>2.프로젝트 주요 기능</h1>
<div align="center" >
  <img src="https://github.com/user-attachments/assets/03a46b98-f30e-46c4-b215-4d218fc05659">
</div>
<h1>3.ERD 설계도</h1>
<h3>>>erd 링크 바로가기 : https://www.erdcloud.com/d/ddkcTthy8NNnp86Fz</h3>
<img src="https://github.com/user-attachments/assets/6a97d072-f8fa-491d-9b5a-933348fbdcbe">
<h1>4.맡은 기능</h1>
<div align="center">
  <table>
  <tbody>
    <tr>
      <td align="center">기능</td>
      <td align="center">설명</td>
      <td align="center">비고</td>
    </tr>
    <tr>
      <td>내 정보 조회/수정</td>
      <td>회원 가입 시 입력했던 <br/>정보 조회 수정 가능</td>
      <td>
        -비밀번호 입력 시 수정 가능<br>
        -관리자 입장 시 프로필 사진/소개글 입력이 뜬다<br/>
        -탈퇴 가능
      </td>
    </tr>
    <tr>
      <td>내 게시글 조회</td>
      <td>본인 작성한 게시글 조회 가능</td>
      <td>
        -제목/내용으로 게시글 검색 가능<br/>
        -선택 후 게시글 삭제 가능, 미선택시 알림창 <br/>
        -게시글 선택시 상세 게시글 페이지로 이동
      </td>
    </tr>
    <tr>
      <td>내 댓글 관리</td>
      <td>본인이 작성한 댓글 조회 가능</td>
      <td>
        -선택 후 댓글 삭제 가능, 미선택시 알림창 <br/>
        -댓글 선택시 원본 게시글 페이지로 이동
      </td>
    </tr>
    <tr>
      <td>회원 관리</td>
      <td>관리자가 회원을 관리할 수 있다</td>
      <td>
        -이름/전화번호로 회원 검색 가능<br/>
        -회원의 비밀번호 초기화 가능<br/>
        -마스터 계정일시 회원의 등급 변경가능
      </td>
    </tr>   
  </tbody>
</table>  
</div>
<h1>5.기능별 코드 소개</h1>








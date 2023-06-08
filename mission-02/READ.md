# 2차 과제 제출

## 결과
![이미지](./image01/png)

## 마크업 코드, 설명

### html 

```
div.contatainer
    h1 /*제목*/
      form /*전체 폼*/
          fieldset
          div.idBOx /*아이디, 비밀번호 입력창*/
          label /*아이디*/
          input
          br
          label /*비밀번호*/
          input
          button /*로그인 버튼*/      
          ul.formList /*회원가입, 아이디 비밀번호 링크*/
             li
               a
             li
               a
```
### css
- .container fieldset의 margin 좌우 값 0;
- .idbox label은 display를 inline-block;으로 변경하여 사이즈 조정함
- .buttonFill은 display를 inline-block;으로 변경하여 사이즈 조정함
- position은 relative로 변경하여 left 170px, bottom 54px;줘서 위치 조정
- .formList, hr의 position은 relative로 변경하여 bottom 50px; 줘서 위치 조정
- ul li:first-child, nth-child(2) 가상 클래스 사용, first-child에 float: right으로 위치 조정

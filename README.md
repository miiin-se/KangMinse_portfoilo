# KangMinse_portfoilo
elcole project
------
프로젝트 계획이유
> 나만의 포트폴리오를 만들어 웹사이트에 올리기 위해 만들었습니다.
> 앞으로도 다양한 프로젝트를 하며 내용을 추가해 나갈 계획입니다.
------
My info
- 핵심 기능
  - 사진과 이름, 학적, 나이, 거주지를 나타내었다.

- 주요 코드
  - 사진의 사이즈를 조절하고 둥근 테두리 적용, 오른쪽 margin을 40px로 정하였다.
```css
#my_info img{
  width: 100px;
  height: auto;
  border-radius: 50px;
  margin-right: 40px;
  }
```
------
About
- 핵심 기능
  - 간단한 자기소개가 가능하도록 구현하였다.
------
Contact
- 핵심 기능
  - 전화번호와 이메일을 나타내었다.
  - 마우스를 올리면 색이 변하고 밑줄이 생긴다.
  - 클릭하면 해당 전화번호로 또는 이메일 주소로 연락할 수 있도록 링크로 연결되어 있다.
------
Skills
- 핵심 기능
  - 내가 가지고 있는 스킬을 해쉬태그 모양으로 구현하였다.
------
Projects
- 핵심 기능
  - 비디오를 넣어 내가 한 Project에 대해 쉽게 설명할 수 있게 하였다.
  - 사이트 바로가기를 넣어 클릭하면 만든 사이트로 연결될 수 있게 하였고, 마우스를 올리면 배경이 검정색으로 바뀌고 글씨가 옆으로 이동하는 애니메이션을 구현하였다.

- 주요 코드
  - hover를 통해 마우스를 위에 올리면 반응이 나타나게 하였다.
  - transition을 통해 padding속성을 0.2초 동안 서서히 변경하게 하였다.
```css
#projects a:hover{
    background-color: #2f2f2f;
    text-decoration: none ;
    padding: 2px 8px;
    transition: padding 0.2s;
}
```
https://miiin-se.github.io/KangMinse_portfoilo/

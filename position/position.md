## Position
position에는 4가지가 있음 (static, absolute, relative, )


.box {
    border:1px solid;
    position:absolute;
}

### absolute
absolute의 경우 화면이 기준이 된다 다른 부모 요소와는 상관없이 무조건 화면의 절대값을 따진다
다른 요소는 무시하게됨
position absolute의 상태에서 -갑승ㄹ 주게 되면 밖으로 나가게 되어 버린다 아래나 오른쪽의 경우에는 스크롤이 생기는듯 하지만

### relative
포지션을 잡기전의 원래 자리가 기준으로 잡는다

### fixed
fixed는 무조건 화면을 기준으로 정의

### absolute를 이용한 가운데 잡기
p {
    width: 500px;
    height: 200px;
    border: 2px solid red;
    position: absolute:
    left: 50%;
    top: 50%;
    margin-left: -250px;
    margin-top: -100px
}

margin-left;
margin-top; 이 두가지를 이용해서 원래 위치에서 땡겼다 밀었다 해보자
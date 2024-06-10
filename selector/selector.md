# 선택자
#### 태그 셀렉터
태그를 선택
```
h {
    width:100%
}
```

#### 전체 선택자
```
* {
     width:100%
}
```

```
div * {
    width:100%
}

div태그 이내의 자식선택자 전부
```

#### class 선택자
.class {
    width: 100%
}

#### id 선택자

#id {
    width: 100%
}

#### 자손 선택자
가능하면 id와 클래스명을 이용하지 않는것이 좋음
```
div h2 {
    width :100%
}
```

#### css before

```
 h1:before {
    content:'before;
    color:red;
 }
 
 <h1 id= "title"> css 기본 문법 </h1>
```
여기서 before 혹은 after는 드래그를 통해서 선택이 되지 않음 (html에서는 존재하지 않음)


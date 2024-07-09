## Flex

플랙서블 박스에서 부모박스는 가변적인 박스로 작동하기 위한 기본개념 (Wrap처럼 모든 요소를 감싸고 있는 존재)이 부모 박스에
플렉서블 박스에 특정 속성값을 적용하여 가변적인 박스로 작동하도록 설정

아래와 같이 부모요소에 display:flex를 설정하면 특별한 설정없이 자식요소들이 3등분으로 가로 배열이 된다

```
<style>
.parent {display :flex;}
.parent div{background-color: grey}
</style>
```

display: flex; 자식요소를 블록 수준의 플렉서블 박스로 작동하게 한다.

flexdirection:row(기본값) 기본값, 박스를 왼쪽에서 오른쪽으로 배치


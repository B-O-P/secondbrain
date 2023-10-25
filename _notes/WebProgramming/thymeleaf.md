### th:text = "${variable}"
+ PostMapping으로 variable에 데이터를 넘겨줘야한다.

```java
	mo.addAttribute("identity", id);
```

+ "identity"는 받는 html에서 사용할 이름이다.
+ id는 데이터를 줬던 html에서 가져온 이름이다.

### th:style = "|background-color : ${Color}"

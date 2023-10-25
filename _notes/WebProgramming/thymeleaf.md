### th:text = "${variable}"
+ PostMapping으로 variable에 데이터를 넘겨줘야한다.

```java
	mo.addAttribute("identity", id);
```

+ "identity"는 받는 html에서 사용할 이름이다.
+ id는 데이터를 줬던 html에서 가져온 이름이다.

### th:style

```html
th:style = "|background-color : ${Color}"
```

+ thymeleaf에서 ""안에 | |를 사용하면 | | 내용 전체를 전달할 수 있다.

### th:each

```html
<tr th:each = "item:${arr}">
	<td th:text = "${item}">
```

+ tr을 통해서 arr요소의 개수만큼 새로운 줄을 형성한다.
+ 새로운 줄을 형성하면서 item에 arr의 내용을 하나씩 추출한다.


```html
<style>
	a{
		margin-right : 40px;
		color : red; /* ""를 붙이면 안된다 */
	}
</style>
```

![image](https://github.com/B-O-P/secondbrain/assets/117426928/072d2acb-419a-4503-a345-3ed8402c8429)

+ tag_name이후 {}안에 css속성을 추가할 수 있다.
+ 값의 할당은 =이 아니라 :로 이루어진다.

### 각각의 태그 내부에서 style을 수정하기
```html
<body style = "background-color: lime;">
```

+ `<>`내부에서 `style`을 작성할 수 있다.
+ `=`로 할당하기 때문에 `""`내부에서 작성해야 한다.
+ `""`내부에서는 `:`을 통해서 값을 할당한다.

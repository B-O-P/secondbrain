```html
<script th:inline = "javascript">
    alert([[${msg}]]);/*th를 이용하여 js를 활용하는 법*/
    location.href = "/login";
</script>
```

```java
    @GetMapping("/popup")
    public String popup(String msg, Model mo){
        mo.addAttribute("msg", msg);
        return "popup";
    }
```


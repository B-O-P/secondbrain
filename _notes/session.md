```java
    @GetMapping("/logout")

    public String logout(HttpSession se, Model mo){

        mo.addAttribute("id", se.getAttribute("id"));

        se.invalidate();/*세션 무효화*/
00000000
        return "logout";
    }
```
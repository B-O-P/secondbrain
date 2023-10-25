```java
@PostMapping("/login/check")

    public String loginCheck(HttpSession se, String id, RedirectAttributes re){
        ArrayList<String> arr = new ArrayList<>();
        arr.add("고흐");
        if(arr.contains(id)){
            se.setAttribute("id", id);
            return "redirect:/menu";
        }
        else{
            re.addAttribute("msg", id + "는 미등록 아이디입니다.");
            return "redirect:/popup";
        }
    }
```

+ RedirectAttributes를 Parameter로 가져와야 한다.
+ RedirectAttributes를 사용하는 것은 redirect와 동시에 데이터를 전송하고 싶은 경우 불러오면 된다. 전송할 데이터가 없다면 굳이 불러오지 않아도 된다.
+ 
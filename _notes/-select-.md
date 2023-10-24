```html
<form method = "post" action = "/study/result">
    <p>
        아이디 : <input type="text" name = "id"><br>
        비밀번호 : <input type="password" name = "pass"><br>
        이름 : <input type="text" name = "name"><br>
        성별 : <input type = "radio" name = "gender" value = "man">맨 <input type = "radio" name = "gender" value = "women">우먼<br>
        직업 : <select name = "job">
            <option>아직고딩</option>
            <option>21세기대학생</option>
            <option>아티스트</option>
            <option>공유</option>
        </select>
    </p>
    <button type = "submit">등록</button>
    <button type = "reset">취소</button>
    </form>
```

![image](https://github.com/B-O-P/secondbrain/assets/117426928/38d65505-a660-4305-907c-957f2c120e58)

+ select는 name을 필요로 합니다.
+ select를 눌렀을 때 나오는 것들은 `<option>`이 필요합니다.
+ `<option>`은 솔로태그로 사용할 수 있습니다.


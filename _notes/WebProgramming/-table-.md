```html
    <table border = "1">
        <tr>
            <th>아이디 <th>비밀번호 <th>이름 <th>성별 <th>직업
        <tr>
            <td>sony<td>1111<td>손흥민<td>남<td>축구선수
        <tr>
            <td>sunflower<td>2222<td>고흐<td>남<td>화가
        <tr>
            <td>&nbsp<td>&nbsp<td>&nbsp<td>&nbsp<td>&nbsp
    </table>
```

![image](https://github.com/B-O-P/secondbrain/assets/117426928/51f9b45b-2d90-4256-b2db-3c3f9a0928ee)

+ border = "1"을 사용하면 줄이 보입니다.
+ border를 사용하지 않으면 줄이 없습니다. (border = "0")
+ th를 이용하면 진하게 가운데정렬
+ td를 이용하면 진하기가 보통이고 좌측 정렬입니다.

---
### Table심화
```html
<style>
    span{
        font-size : x-large;
        font-weight : bold;
        background-color: yellow;
    }
    #first{
        background-color: pink;
    }
    .second{
        background-color: cyan;
    }
</style>

<h3>rowspan</h3>
    <table border = "1">
        <tr>
            <td rowspan="3">여러행<br>셀<br>합치기 <td>1행 2열
        <tr>
            <td>2행 2열
        <tr>
            <td>3행 2열
    </table>
    <hr>
    <h3>colspan</h3>
    <table border = "1">
        <tr>
            <td colspan = "3">여러 열 합치기</td>
        <tr>
            <td>2행 1열 <td>2행 2열 <td>2행 3열
    </table>
    <hr>
    <span>시간표 만들기</span>
    <table border = "1">
        <tr id = "first">
            <th>교시 <th>월 <th>화 <th>수
        <tr>
            <th class = "second">1 <td>딥러닝 <td rowspan = "2">테니스 <td rowspan = "3">컴퓨터구조
        <tr>
            <th class = "second">2 <td>웹프로그래밍
        <tr>
            <th class = "second">3 <td>파일처리론 <td>이산수학
        <tr>
            <th class = "second">4 <th colspan = "3">점심 및 휴식시간입니다!
        <tr>
            <th class = "second">5 <td>영어 <td>롤 <td>AI
    </table>
```

![image](https://github.com/B-O-P/secondbrain/assets/117426928/4a06a675-28b2-4a72-85b7-41284b0c8f2a)

+ class를 사용하면 `.`으로 불러옵니다.
+ id를 사용하면 `#`으로 불러옵니다. 
+ `colspan`을 사용하면 가로로 n칸을 묶을 수 있습니다.
+ `rowspan`을 사용하면 세로로 n칸을 묶을 수 있습니다.
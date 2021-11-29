---
layout: simplepage
title: 컨셉이란 그저 이야깃거리
---

<script>
  function jsMove(){
    var baselink = "/secrets/keyis";
    var pc = document.getElementById('passcode').value;
    var temp = baselink.concat(pc);
    window.open(temp.toLowerCase());
  }
</script>

<div>
당신의 <span style="color:#65bed6"><b>선택</b></span>이 결과를 바꿀 것이다.<br>

<br>
Key: 지금까지 해왔던대로.
<br>
<form autocomplete='off' onsubmit = "jsMove();">
  <input id = 'passcode' type='text' required><br>
  <br>
  <input type = 'submit' value = '제출합니다.'>
</form>
</div>
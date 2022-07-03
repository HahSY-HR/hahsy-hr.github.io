---
layout: post
title: 이것은...?!
date: 2022-08-09
category: metafiction
---
<script>
  function jsMove(){
    var baselink = "https://hahsy-hr.github.io/2022";
    var tail = "bday/";
    var pc = document.getElementById('passcode').value;
    alert("접속을 시도합니다. 404에러가 났다면, 틀렸지롱!");
    var temp = baselink.concat(pc);
    window.open(temp.concat(tail));
  }
</script>
<p>
미안허다.<br>
님 동생 졸라 바빠서 아이디어가 부족햇다.<br>
이번에도 룰은 똑같다.<br>
먼말인지 몰르겟어? 뗴잉쯧 동생님에 대한 Jinjungsung이 부족하구만<br>
<br>
정모르겠으면 참조하라구 <a href="/metafiction/2021/08/09/surprise.html">링크</a><br>
<br>
형식: 네 자리 숫자<br>
  <form autocomplete='off' onsubmit = "jsMove();">
      <input id = 'passcode' type='text' required><br><br>
      <input type = 'submit' value = '제출합니다.'>
    </form>
</p>

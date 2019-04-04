//출처 : https://www.cosmosfarm.com/threads/document/2247

- 워드프레스 post 나 page 안에서 jQuery를 사용하는 방법

우선 소스보기로 jQuery가 추가 되어 있는지 확인
그리고 워드프레스에서 "$" 변수는 사용하실 수 없음.
"$" 변수 대신 "jQuery" 변수로 사용

예시) 
<script type="text/javascript">

jQuery(document).ready(function($) {

  $("h2").click(function() {

    $("h2").css({ "color" : "red" });

  });

});

</script>

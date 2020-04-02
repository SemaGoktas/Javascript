<!doctype html>
<html lang="tr-TR">
<head>
  <meta http-equiv="content-type" content="text/html; charset=utf-8">
  <title>Takip Eden Metin</title>
</head>

<body>
  <span id="hareketlialan" style="color:black;">Javascript </span>
  <script type="text/javascript" language="javascript">
  var alan = document.getElementById('hareketlialan');
  alan.style.position = "absolute";
  window.onmousemove = function(event)
  {
    alan.style.left = event.clientX + 15 + "px";
    alan.style.top  = event.clientY + "px";
  }
  </script>
</body>
</html>


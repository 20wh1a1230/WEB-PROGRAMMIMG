<html>
<head>
  <title>
getElementById.style.property example
</title>
</head>
<body>
  <h1 id="demo"> This text changes color by clicking on the following different buttons. </h1>
  <button onclick="change_Color('green');"> Green</button>
  <button onclick="change_Color('red');"> red</button>
<script type="text/javascript">

function change_Color(newColor) {
  var element = document.getElementById('demo').style.color = newColor;
}
</script>
</body>
  </html>

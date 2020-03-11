<html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/3/w3.css">
<body>
  <head>
  <link rel="stylesheet" href="style1.css">
</head>

<div class="h1">
  <h1>How to Bartend</h1>
  <p>Be the best Bartender ever ! :)</p>
</div>
<!-- Slide Show -->
<section>
  <img class="mySlides" src="	c700x420.jpg" style="width:100%">
  <img class="mySlides" src="c700x420-2.jpg" style="width:100%">
  <img class="mySlides" src="	Bobrow_Bartending.jpg" style="width:100%">
                                                               
</section>

<script>
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}
  x[myIndex-1].style.display = "block";
  setTimeout(carousel, 3000);
}
</script>

</body>
</html>

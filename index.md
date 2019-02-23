
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body { 
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

#header {
  background-color: #f1f1f1;
  padding: 50px 10px;
  color: black;
  text-align: center;
  font-size: 90px; 
  font-weight: bold;
  position: fixed;
  top: 0;
  width: 100%;
  transition: 0.2s;
}
</style>
<body>

<div id="header">Header</div>

<div style="margin-top:200px;padding:15px 15px 2500px;font-size:30px">
 <style>
* {
  box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  height: 3000px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h2>WE GOT THIS</h2>

<div class="row">
  <div class="column" style="background-color:yellow;">
    <h2>POSITIVE THOUGHTS</h2>
    <p>WE CAN DO THIS</p>
  </div>
  <div class="column" style="background-color:orange;">
    <h2>POSITIVE THOUGHTS</h2>
    <p>WE CAN DO THIS</p>
  </div>
  <div class="column" style="background-color:red;">
    <h2>POSITIVE THOUGHTS</h2>
    <p>WE CAN DO THIS</p>
  </div>
</div>


</div>

<script>
// When the user scrolls down 50px from the top of the document, resize the header's font size
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 50 || document.documentElement.scrollTop > 50) {
    document.getElementById("header").style.fontSize = "30px";
  } else {
    document.getElementById("header").style.fontSize = "90px";
  }
}
</script>

</body>
</html>

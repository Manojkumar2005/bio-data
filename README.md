<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.title {
  color: grey;
  font-size: 18px;
}

button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
}

button:hover, a:hover {
  opacity: 0.7;
}
</style>
</head>
<body>

<h2 style="text-align:center">User Profile Card</h2>

<div class="card">
  <img src="img/itachi.jpg" alt="John" style="width:100%">
  <h1>Manoj kumar</h1>
  <p class="title">Btech-Artificial intelligence and data science</p>
  <p>Ramco institute of technology</p>
  <div style="margin: 24px 0;">
    <a href="www.google.com"><i class="fa fa-dribbble"></i></a> 
    <a href="https://instagram.com/_manoj__005?igshid=ZGUzMzM3NWJiOQ=="><i class="fa fa-instagram"></i></a>  
    <a href="https://github.com/settings/profile"><i class="fa fa-github"></i></a>  
    <a href="https://www.facebook.com/profile.php?id=100016111021599&mibextid=ZbWKwL"><i class="fa fa-facebook"></i></a> 
  </div>
  <form action ="Manoj Resume.pdf" method=post>
  <p><button>Download cv</button></p></form>
</div>
</body>
</html>

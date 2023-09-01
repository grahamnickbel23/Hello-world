"# Hello-world" 
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lyrics</title>
    <link rel="stylesheet" href="styal3.css">
</head>
<body>
    <h1><a href="About.html" title="Home">Nationl Eligibility & Entrance Test (NEET)</a></h1>
    <hr>
    <nav class="navbar">
        <ul>
            <li><a href="About.html" title="Home">Home</a></li>
            <li><a href="lyrics.html" target="_blank" title="About">About</a></li>
            <li><a href="Product.html"target="_blank" title="Product">Products</a></li>
            <li><a href="Contacs.html" target="_blank" title="Product">Contacs</a></li>
        </ul>
    </nav><br>
    <hr>
   <main>
    <h2>Fill up this from with required information</h2><br>
    <from  action="index.php" method="post" enctype="multipart/form-data">
        <label for="username">username :</label>
        <input type="text" id="username" placeholder="Your name" minlength="5" maxlength="100" required><br><br>
        <label for="password">password :</label>
        <input type="password" id="password" placeholder="password" required maxlength="15" minlength="10"><br><br>
        <label for="Phone">Phone :</label>
        <input type="tel" is="phone" placeholder="123-456-7890" pattern="[0-9{3}[0-9]{3}[0-9]{4}" required><br><br>
        <label for="emial">E-mail :</label>
        <input type="email" id="emial" placeholder="adc@host.com" required>
    </from>
   </main><br>
   <hr>
    <footer>
        <nav class="navbar2">
          <ul>
            <li><a href="About.html" title="About">Home</a></li>
            <li><a href="lyrics.html"  target="_blank" title="About">About</a></li>
            <li><a href="Product.html"  target="_blank" title="About">Products</a></li>
            <li><a href="Contacs.html"  target="_blank" title="About">Contacs</a></li>
          </ul>
        </nav>
    </footer>
    
</body>
</html>

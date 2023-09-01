<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
</head>
<body>
    <h1><a title="Home">Nation Exam & Eligibility Test</a></h1>
    <hr>
    <nav>
        <ul>
            <li><a href="About.html">Home</a></li>
            <li><a href="lyrics.html">About</a></li>
            <li><a href="Product.html">Product</a></li>
            <li><a href="Contacs.html">Contacs</a></li>
        </ul>
    </nav>
    <hr>
    <main>
        <h2><a title="Fill the gaps with requred information">Fill the gaps with requred information</a></h2>
        <form action="index.php" method="post" enctype="multipart/form-data">
            <label for="Username">username :</label>
            <input type="text" id="Username" placeholder="Mukesh Achariya" required><br><br>
            <label for="password">password :</label>
            <input type="password" id="password" placeholder="abcs@123#" required minlength="5" maxlength="15"><br><br>
            <label for="Phone">Phone :</label>
            <input type="tel" id="Phone" placeholder="012-345-6789" pattern="[0-9]{3}[0-9]{3}[0-9]{4}" required maxlength="10" minlength="10"><br><br>
            <label for="E-mail">E-mail :</label>
            <input type="email" id="E-mail" placeholder="xxx@hotmail.com" required><br><br>
            </form>
    </main>
    <hr>
    <footer>
        <nav>
            <ul>
                <li><a href="About.html">Home</a></li>
                <li><a href="lyrics.html">About</a></li>
                <li><a href="Product.html">Product</a></li>
                <li><a href="Contacs.html">Contacs</a></li>
            </ul>
        </nav>
    </footer>
    <hr>
</body>
</html>

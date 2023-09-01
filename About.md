!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <link rel="stylsheet" href="styal3.css">
</head>
<body>
    <h1>Nation Stock Exchange</h1>
    <nav class="navbar">
        <ul>
            <li><a href="" title="Home">Home</a></li>
            <li><a href="" title="About" target="_blank">About</a></li>
            <li><a href="" title="Product" target="_blank">Product</a></li>
            <li><a href="" title="Contacs" target="_blank">Contacs</a></li>
        </ul>
    </nav><br>
    <hr>
    <main>
        <h2>Fill the form</h2>
        <from action="index.php" enctype="multipart" method="post">

            <label for="username">username :</label>
            <input type="text" id="username" placeholder="Your Name" maxlength="25" required><br><br>

            <label for="password">password :</label>
            <input type="password" id="password" placeholder="password" maxlength="25" required><br><br>

            <label for="email">email :</label>
            <input type="email" id="email" placeholder="abcd@hotmail.com" required><br><br>

            <label for="phone">phone :</label>
            <input type="tel" id="phone" placeholder="012-345-6789" maxlength="10" minlength="10" pattern="[0-9]{3}[0-9]{3}[0-9]{4}" required><br><br>

        </from>
    </main>
    <hr>
    <footer>
        <nav class="navbar2">
            <ul>
                <li><a href="" title="Home">Home</a></li>
                <li><a href="" title="About" target="_blank">About</a></li>
                <li><a href="" title="Product" target="_blank">Product</a></li>
                <li><a href="" title="Contacs" target="_blank">Contacs</a></li>
            </ul>
        </nav>
    </footer>
</body>
</html>

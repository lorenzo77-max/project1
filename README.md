# project1
this is test repo 
<h1>Made by lorenzo-max.<h2>

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>test tech</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            font-family: "Roboto", sans-serif;
        }

        .header {
            background-color: rgb(129, 85, 137);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
        }

        .header a {
            color: #ffffff;
            padding: 0 20px;
            text-decoration: none;
            border-radius: 10px;
        }

        .header a:hover {
            background-color: #de9fdc;
        }

        .header button {
            padding: 5px 15px;
            color: #fdf9f9;
            border: 0;
            background-color: rgb(129, 85, 137);
            border-radius: 10px;
            cursor: pointer;
        }

        .header button:hover {
            background-color: #de9fdc;
            border-radius: 20px;
        }

        .landing-page {
            text-align: center;
            padding: 20px;
            background-color: #de9fdc;
            color: white;
        }

        .landing-page h1,
        .landing-page h2,
        .landing-page p {
            margin: 10px 0;
        }

        .landing-page img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
        }

        .searchbar {
            display:flex;
            justify-content: center;
            padding: 10px;
            background-color: #f8f8f8;
          
        }

        .searchbar input {
            padding: 10px;
            margin-right: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .searchbar button {
            padding: 10px;
            border: none;
            background-color: rgb(129, 85, 137);
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }

        .searchbar button:hover {
            background-color: #de9fdc;
        }
        .landing-page-image img {
          border-radius: 20;
          width="100"
        }
    </style>
</head>
<body>
    <!--HEADER-->
    <div class="header">
        <img src="images/" width="50" alt="Logo"/>
        <div>
            <a href="test.html">home</a>
            <a href="#">our shop</a>
            <a href="#">contact</a>
            <button>Sign in</button>
        </div>
    </div>

    <!-- SEARCH BAR -->
    <div class="searchbar">
        <input type="text" placeholder="Search..."/>
        <button>Search</button>
       
    </div>

    <!--LANDING PAGE-->
    <div class="landing-page">
        <h1>Welcome to our store</h1>
        <h2>The best clothes for the best clients</h2>
        <p>Happy shopping with good prices for ALL</p>
        <div class = "landing-page-image">
        <img src="images2" />
    </div>
</body>
</html>



<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Rushikesh khillare </title>
</head>
<link href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
    /* CSS Reset */

    body {
        font-family: 'Baloo Bhai', cursive;
        color: rgb(0, 0, 0);
        margin: 0px;
        padding: 0px;
        background: url("https://th.bing.com/th/id/R.b0941ae049cfe1242b875ee0ea722236?rik=TmhTt6vbVP7Rsg&riu=http%3a%2f%2fwww.lionleaf.com%2fwp-content%2fuploads%2f2014%2f11%2f1415275_22821821.jpg&ehk=7bK0H1iqq%2fkS48m0bbON6BfPoegjSZFfXu%2bC3ztcrvI%3d&risl=&pid=ImgRaw&r=0");
    }

    .left {
        display: inline-block;
        /* border: 2px solid red; */
        position: absolute;
        left: 60px;
        top: 20px;
    }

    .left img {
        width: 136px;
        filter: invert(100%);
    }

    .left div {
        line-height: 19px;
        font-size: 26px;
        text-align: center;
    }

    .mid {
        display: block;
        width: 20%;
        margin: 20px auto;
        color: black
        /* border: 2px solid green; */
    }

    .right {
        position: absolute;
        right: 34px;
        top: 43px;
        display: inline-block;
        /* border: 2px solid yellow; */
    }

    .navbar {
        display: inline-block;
        display: flex;
    }

    .navbar li {
        display: inline-block;
        font-size: 25px;
    }

    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 34px 23px;
    }

    .navbar li a:hover,
    .navbar li a.active {
        justify-content: space-between;
        text-decoration: underline;
        color: rgb(12, 9, 9);
    }

    .btn {
        font-family: 'Baloo Bhai', cursive;
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border: 2px solid grey;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(196, 13, 13);
    }

    .container {
        border: 2px solid rgb(209, 9, 9);
        margin: 106px 80px;
        padding: 75px;
        width: 80%;
        text-align: center;
        border-radius: 28px;
    }

    .form-group input {
        font-family: 'Baloo Bhai', cursive;
        text-align: center;
        display: block;
        width: 508px;
        padding: 1px;
        border: 2px solid rgb(199, 24, 24);
        margin: 11px auto;
        font-size: 25px;
        border-radius: 8px;
    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 74%;
        margin: 20px auto;
    }

    .navbar.li {
        text-align: center;
    }
</style>

<body>
    <header class="header">
        <!-- Left box for logo -->
        <div class="left">
            <div>Rushikesh Khillare</div>
        </div>
        <!-- Mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About </a></li>
                <li><a href="#">Contact </a></li>
            </ul>
        </div>

        <!-- Right box for buttons -->
        <div class="right">
            <button class="btn">Call Us Now</button>
            <button class="btn">Email Us</button>
        </div>
    </header>
    <div class="container">
        <h1>Student basic information collection form</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Locality">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Email Id">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Phone Number">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>

</html>

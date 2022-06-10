!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>.bod{background-image: url("LOG.jpg");
        display: flex;
        background-position: center;
        background-size: cover;
        width:100%;
        height: 100vh;
        align-items: center;
        justify-content: center;
        font-family: cursive;
    }
    div.be{width: 980px;
        height: 560px;
        border-radius: 15px;
        box-shadow:0 0 30px blueviolet;
        background:radial-gradient(blueviolet);
        backdrop-filter: blur(3px);
    }
    div.st{display: flex;
        flex-direction: row;
        color: white;
        margin-left: 0px;
        width: 550px;
        height: 80px;
        border-radius: 15px 0 15px 0;
        background-color: blueviolet;
        border: 1px solid blueviolet;
    }
    .hom{
        margin-left: 60PX;
        margin-top: 30px;
        transition: ease-in-out 0.5s;
    }
    .hom:hover{
        color: rgba(0, 0, 0, 0.781);
    }
    .sea{border: none;
        background-color: transparent;
        position: relative;
        left: 700px;
        top: -30px;
        outline: none;
        height: 30px;
        width: 250px;
        border-bottom: 1px solid blueviolet;
        border-right: 1px solid transparent;
        border-left: 1px solid transparent;
        border-top: 1px solid transparent;
    }
    .sea:hover{border-bottom-color:white;
    }
    .sea::placeholder{
        color: white;
        font-size: larger;
    }
    .lo{display: flex;
        flex-direction: column;
        border: 3px solid blueviolet;
        width: 300px;
        margin-left: 20px;
        margin-top: 10px;
        height: 400px; 
        border-radius: 10px;
        transition: ease-in-out 0.3s;
    }
    .lo:hover{
        border-color: white;
    }
    .og{display: flex;
        color: blueviolet;
        justify-content: center;
        font-size: xx-large;
    }
    
    .ph{border: none;
        color: white;
        background-color: transparent;
        border-bottom: 2px solid blueviolet;
        margin-left: 7px;
        margin-right: 15px;
        outline: none;
    }
    .ph::placeholder{
        color: white;
        font: size 20px;;
    }
    .em{margin-left: 7px;
        color: white;
    }
    .ph:hover{
        border-color: white;
    }
    .ss{border: none;
        color: white;
        background-color: transparent;
        border-bottom: 2px solid blueviolet;
        margin-left: 7px;
        margin-right: 15px;
        outline: none;
    }
    .ss::placeholder{
        color: white;
        font: size 20px;;
    }
    .pa{margin-left: 7px;
        color: white;
    }
    .ss:hover{
        border-color: white;
    }
    .fo{color: red;
        margin-left: 7px;
        margin-top: 20px;
        width: 170px;
        transition: ease-in-out 0.3s;
    }
    .fo:hover{
        color: green;
    }
    .gi{width: 100px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 30px;
        height: 40px;
        border: none;
        border-radius: 7px;
        margin-left: 100px;
        font-family: cursive;
        font-size: large;
    }
    .gi:hover{color: white;
        background-color: blueviolet;
    }
    .wel{width: 450px;
        height: 400px;
        border: 3px solid blueviolet;
        border-radius: 12px;
        margin-top: -405px;
        margin-left: 350px;
    }
    .wel:hover{
        border-color: white;
    }
    .el{display: flex;
        color: blueviolet;
        justify-content: center;
        font-size: xx-large;
    }
    .br{word-spacing: 10px;
        font-size: large;
        color: white;
    }
    .spa{display: flex;
    justify-content: space-between;
    margin-left: 10px;
    margin-right: 10px;
    }
    .li{width: 120px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 55px;
        height: 35px;
        border: none;
        border-radius: 7px;
        font-family: cursive;
        font-size: large;
    }
    .lt{width: 140px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 55px;
        height: 35px;
        border: none;
        border-radius: 7px;
        font-family: cursive;
        font-size: large;
    }
    .ly{width: 130px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 55px;
        height: 35px;
        border: none;
        border-radius: 7px;
        font-family: cursive;
        font-size: large;
    }
    .li:hover{color: white;
        background-color: blueviolet;
    }
    .lt:hover{color: white;
        background-color: blueviolet;
    }
    .ly:hover{color: white;
        background-color: blueviolet;
    }
    
    
    
    div.ba{width: 750px;
        height: 560px;
        display: flex;
        justify-content: center;
        flex-direction: column;
        border-radius: 15px;
        box-shadow:0 0 30px blueviolet;
        background:radial-gradient(blueviolet);
        backdrop-filter: blur(3px);
    }
    div.ov{display: flex;
        width: 200px;
        flex-direction: column;
        justify-content: center;
        margin-left: 130px;
        color: blueviolet;
        margin-top: -50px;
    }
    .las{display: flex;
        justify-content: stretch;
        margin-top: -18px;
        width: 500px;
        height: 25px;
        background-color: transparent;
        border-bottom: 1px solid blueviolet;
        border-top: none;
        color: #fff;
        border-left: none;
        border-right: none;
        outline: none;
    }
    .las:hover{border-bottom-color: #fff;
    }
    .las::placeholder{color: white;
        font-size: 15px;
    }
        .tt{display: flex;
            justify-content: center;
            align-items: center;
            width: 700px;
            margin-left: 25px;
            margin-top: 30px;
            height: 40px;
            border: none;
            border-radius: 10px;
            font-size: x-large;
            font-weight: 500px;
            font-family: cursive;
        }
        .tt:hover{color: white;
            background-color: blueviolet;
        }
        .gh{display: flex;
            justify-content: center;
            position: relative;
            top: -30px;
            color: blueviolet;
            text-decoration: underline;
        }
        .gin{position: relative;
            top: -20px;
        }</style>
    <title>ABIMBOLA LOGIN PAGE</title>
</head>
<body class="bod">  
    <div class="be">
        <div class="st">
        <p class="hom">HOME</p>
        <p class="hom">ABOUT</p>
        <p class="hom">SERVICE</p>
        <p class="hom">CONTACT</p>
        </div> 
        <a href="https://www.google.com.ng/webhp?tab=rw"><input class="sea" type="search" placeholder="Click to search"></a>
        <div class="lo">
            <h3 class="og">LOGIN</h3>
            <p class="em"><b>Email or Phone Number:</b></p>
            <input class="ph" type="text" placeholder="Enter Email or Phone Number">
            <p class="pa"><b>Password:</b></p>
            <input class="ss" type="password" placeholder="Enter Password">
            <a class="fo" href="SIGN UP.html">I am a new member</a>
            <button class="gi">LOGIN</button>
        </div>
        <div class="wel">
            <h3 class="el">WELCOME EVERYONE</h3>
            <p class="br">The webpage is a single document on the web using a unique URL,
                while a website is a collection of multiple webpage in which information on a related
                topic or another subject is linked together under the same domain</p>
                <div class="spa">
                    <button class="li">LIKE PAGE</button>
                    <button class="lt">LEARN MORE</button>
                    <button class="ly">FOLLOW US</button>
                </div>
        </div>
    </div>
</body>
</html>

<html>

<head>
    <title>Login Hotel</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

<body>
    <div class="form-box">
        <h2>O Monot Hotel!</h2>
        <h1>Login Here</h1>
        <div class="input-box">
            <i class="fa fa-envelope-o"></i>
            <input type="email" placeholder="Email Id">
        </div>
        <div class="input-box">
            <i class="fa fa-key"></i>
            <input type="password" placeholder="Password" id="myInput">
            <span class="eye" onclick="myFunction()">
            <i id="hide1" class="fa fa-eye"></i>
            <i id="hide2" class="fa fa-eye-slash" aria-hidden="true"></i>
        </span>
        </div>
        <button type="button" class="login-btn">LOGIN</button>
    </div>
    <script>
        function myFunction(){
            var x = document.getElementById("myInput");
            var y = document.getElementById("hide1");
            var z = document.getElementById("hide2");

            if(x.type === 'password'){
                x.type = "text";
                y.style.display = "block";
                z.style.display = "none";
            }
            else{
                x.type = "password";
                y.style.display = "none";
                z.style.display = "block";
            }
        }
    </script>
</body>
</html>

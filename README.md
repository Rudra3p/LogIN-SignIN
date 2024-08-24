# LogIN-SignIN
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" 
          content="width=device-width, initial-scale=1.0">
    <title>LogIN_&_SignIN</title>
    <link rel="stylesheet" href="LogIN_&_SignIN.css">
</head>

<body><header>
        <h1 class="heading">VirtuaLearn</h1>
        </header>
    <!--main container-->
    <div class="container">
         <!--button and text container-->
        <div class="text_button_container">
        <div class="text">
        <h2>Heading</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatibus, nisi. Eum, nemo tempora. Recusandae corporis quas aspernatur porro, nostrum odio! Incidunt, fuga soluta numquam sit, sed unde reiciendis repudiandae commodi est architecto nobis excepturi ad?</p>
        </div>
        <div class="button_container">
        <div class="slider"></div>
        <div class="btn">
            <button class="signin">Sign-in</button>
            <button class="login">Log-in</button>
        </div>
        </div>
        </div>
   <!--form container-->
   <div class="form-container">
        <div class="form-section">
            <!-- login form -->
            <form action="" id="Log-in_form">
            <div class="login-box">
                <input type="email" class="email ele" placeholder="youremail@email.com">
                <input type="password"class="password ele" placeholder="password">
                <button class="clkbtn">Login</button>
            </div>
            </form>
            <!--  signin form -->
            <form action="" id="Sign-in_form">
            <div class="signin-box">
                <input type="text" class="name ele" placeholder="Enter your name">
                <input type="email" class="email ele" placeholder="youremail@email.com">
                <input type="password" class="password ele" placeholder="password">
                <input type="password" class="password ele" placeholder="Confirm password">
                <button class="clkbtn"> signin</button>
            </div>
            </form>  
        </div>
    </div>
    </div>
    <script>
        let  signin = document.querySelector(".signin");
let login = document.querySelector(".login");
let slider = document.querySelector(".slider");
let formSection = document.querySelector(".form-section");

signin.addEventListener("click", () => {
    slider.classList.remove("moveslider");
    formSection.classList.remove("form-section-move");
});

login.addEventListener("click", () => {
    slider.classList.add("moveslider");
    formSection.classList.add("form-section-move");
});
    </script>
</body>
</html>

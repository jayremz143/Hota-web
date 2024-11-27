# Hota-web
<!DOCTYPE html>

<html>

<head>

  <title>Skill Central - Login</title>

  <style>

    



  body {

      font-family: Arial, sans-serif;

      background-color: #0a313d;

      background-image: url(huta1.jpg);

      image-rendering: crisp-edges;

      background-repeat: initial;

      background-position: center;

      background-size: cover;

      display: flex;

      justify-content: center;

      align-items: center;

      height: 100vh;

    }

    

    .container {

      max-width: 400px;

      padding: 500px;

      background-color: transparent;

      background-position: center ;

      border-radius: 5px;

      box-shadow: 0px 10px 50px rgba(0, 0, 0, 0.1);

      margin-left:auto;

      

    }

    h2 {

      text-align: center;

      margin-bottom: 20px;

      color: white;

    }

    label {

      display: block;

      margin-bottom: 10px;

      color: #fff;

      width: 100%;

      height: fit-content;

    }

    input[type="text"],

    input[type="password"] {

      width: 100%;

      padding: 10px;

      border: 1px solid #ddd;

      border-radius: 3px;

      align-items: center;

    }

    .btn {

      display: block;

      width: 112%;

      padding: 10px;

      font-size: 16px;

      text-align: center;

      background-color:orange;

      color: #fff;

      border: none;

      border-radius: 5px;

      cursor: pointer;

    }

    .btn:hover {

      background-color: transparent;

    }

	</style>



</head>

<body>

  



  



    



  <div class="container">

    <h2>Login to HOTA</h2>

    <form id="loginForm">

      <label for="username">Username:</label>

      <input type="text" id="username" name="username">



      <label for="password">Password:</label>

      <input type="password" id="password" name="password">

      <br><br>



      <input type="submit" value="Login" class="btn">

      

    </form>

  </div>

<script>

const form = document.getElementById('loginForm');

    form.addEventListener('submit', (event) => {

      event.preventDefault();



      const username = document.getElementById('username').value;

      const password = document.getElementById('password').value;



      // Perform login validation

      // Replace with your own logic



      if (username === 'hota' && password === 'password') {

        alert('Login Successful');

        // Redirect to home page or perform any required action

        window.location.href = 'home.html';

      } else {

        alert('Invalid username or password');

      }

    });

  </script>

  

</body>

</html>

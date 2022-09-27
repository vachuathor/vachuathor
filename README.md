<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700;900&display=swap"
      rel="stylesheet"
    />
    <title>Homework</title>
  </head>
  <style>
    * {
      padding: 0;
      margin: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      width: 100%;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color:#db248f;
      overflow: hidden;
    }
    .signin_container {
      width: 900px;
      height: 800px;
      background-color: rgba(36, 99, 246, 0.686);
      box-shadow: rgb(3, 20, 28, 0, 0.9);
    }

    .nav {
      width: 100%;
      height: 80px;
      /* background-color: black; */
      color: rgb(36, 218, 23);
      padding: 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 2rem;
      font-weight: 900;
      color: #6c63ff;
      cursor: pointer;
    }

    .sign_in_up_btn .sign {
      padding: 8px 30px;
      border-radius: 5px;
      cursor: pointer;
    }

    .sign_up {
      margin-right: 2rem;
      background-color: transparent;
      border-color: #6c63ff;
      font-size: 1rem;
      font-weight: 900;
      transition: 0.3s ease-in-out;
    }
    .sign_up:hover {
      background-color: #6c63ff;
      color: #ffffff;
    }

    .sign_in {
      border: none;
      background-color: #6c63ff;
      color: #ffffff;
      font-weight: 900;
      font-size: 1rem;
    }

    .ctn_container {
      padding: 2rem;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .img_container {
      width: 496px;
      height: 690px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .img_container p {
      display: flex;
      font-size: 1.5rem;
      padding-bottom: 1rem;
      text-transform: capitalize;
    }

    .form_container {
      width: 496px;
      height: 690px;
      display: flex;
      flex-direction: column;
      padding-top: 8rem;
      padding-right: 1rem;
      padding-left: 1rem;
    }

    .form_container h1 {
      display: flex;
      justify-content: flex-start;
      margin-bottom: 1rem;
    }

    input {
      width: 100%;
      height: 50px;
      background-color: #e6e6e6;
      margin-bottom: 2rem;
      border-radius: 5px;
      border: none;
    }

    input[placeholder] {
      font-size: 1rem;
      padding-left: 1rem;
    }
    .input_check {
      margin: 0;
      display: flex;
      height: 20px;
      margin-bottom: 1rem;
    }

    .checkbox {
      width: 20px;
      display: flex;
      align-items: center;
      position: relative;
      top: -15px;
    }

    .input_check p {
      padding-left: 1rem;
    }

    .signIn_btn {
      padding: 10px;
      color: #fff;
      background-color: #6c63ff;
      border: none;
      border-radius: 5px;
      font-size: 2rem;
      font-weight: 900;
      transition: 0.3s ease-out;
    }

    .signIn_btn:hover {
      background-color: #766ffc;
    }

    .make_account_text {
      padding-top: 1rem;
    }

    .make_account_text a {
      text-decoration: none;
      font-size: 1.1rem;
    }

    img {
      background-size: cover;
      width: 422px;
      height: 447;
    }
  </style>
  <body>
    <div class="signin_container">
      <div class="nav">
        <span class="logo">V/S</span>
        <div class="sign_in_up_btn">
          <button class="sign sign_up">Sign Up</button>
          <button class="sign sign_in">Sign In</button>
        </div>
      </div>
      <div class="ctn_container">
        <div class="img_logo">
          <p>Sign in to access you account</p>
          <img src="./logo.png" alt="sign in" />
        </div>
        <form class="form_container">
          <h1>Sign In</h1>
          <div class="input_email">
            <input type="text" placeholder="Email" />
          </div>
          <div class="input_password">
            <input type="password" placeholder="password" />
          </div>
          <div class="input_check">
            <input type="checkbox" class="checkbox" />
            <p>Remember me</p>
          </div>
          <button class="signIn_btn">Sign In</button>
          <p class="make_account_text">
            Create an account <a href="#">sign up</a>
          </p>
        </form>
      </div>
    </div>
  </body>
</html>

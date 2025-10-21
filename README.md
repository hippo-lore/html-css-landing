<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FunTechs Landing</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      background-color: white;
    }

    /* HEADER */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 25px 80px;
    }

    .logo {
      font-weight: 700;
      color: #ff6b81;
      font-size: 18px;
    }

    nav {
      display: flex;
      align-items: center;
      gap: 25px;
    }

    nav a {
      text-decoration: none;
      color: black;
      font-weight: 500;
    }

    nav a.active {
      font-weight: 700;
    }

    .sign-in, .sign-up {
      border: none;
      cursor: pointer;
      padding: 8px 18px;
      border-radius: 6px;
      font-weight: 600;
    }

    .sign-in {
      color: #2f65f6;
      border: 1px solid #2f65f6;
      background: none;
    }

    .sign-up {
      background-color: #2f65f6;
      color: white;
    }

    /* MAIN SECTION */
    main {
      display: flex;
      flex: 1;
    }

    .left {
      flex: 1;
      background-color: #ff6b81;
      color: black;
      padding: 100px 80px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    .left h1 {
      font-size: 40px;
      font-weight: 700;
      margin-bottom: 20px;
    }

    .left p {
      font-size: 15px;
      line-height: 1.6;
      margin-bottom: 40px;
      max-width: 450px;
    }

    .buttons {
      display: flex;
      gap: 20px;
      margin-bottom: 60px;
    }

    .btn-primary {
      background-color: #2f65f6;
      color: white;
      border: none;
      padding: 14px 32px;
      border-radius: 6px;
      font-weight: 600;
      cursor: pointer;
    }

    .btn-outline {
      border: 1.5px solid #2f65f6;
      background-color: white;
      color: #2f65f6;
      padding: 14px 32px;
      border-radius: 6px;
      font-weight: 600;
      cursor: pointer;
    }

    .logos {
      display: flex;
      align-items: center;
      gap: 25px;
      flex-wrap: wrap;
    }

    .logo-circle {
      width: 45px;
      height: 45px;
      background-color: #f2f2f2;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      font-weight: bold;
    }

    /* RIGHT SIDE */
    .right {
      flex: 1;
      background-color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
    }

    .right img {
      width: 500px;
      height: auto;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">@Funtechs</div>
    <nav>
      <a href="#" class="active">HOME</a>
      <a href="#">CONTACT</a>
      <a href="#">TEAM</a>
      <button class="sign-in">SIGN IN</button>
      <button class="sign-up">SIGN UP</button>
    </nav>
  </header>

  <main>
    <div class="left">
      <h1>Design Confidentely.</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
        Tristique sapien praesent et vestibulum blandit faucibus. 
        Risus ut a, sodales magna sem velit quam.
      </p>
      <div class="buttons">
        <button class="btn-primary">GETTING STARTED</button>
        <button class="btn-outline">CALL US NOW</button>
      </div>
      <div class="logos">
        <div class="logo-circle">G</div>
        <div class="logo-circle">f</div>
        <div class="logo-circle">YT</div>
        <div class="logo-circle">in</div>
        <div class="logo-circle">M</div>
        <div>fiverr.</div>
        <div>NETFLIX</div>
      </div>
    </div>

    <div class="right">
      <img src="illustration.png" alt="Design Illustration" />
    </div>
  </main>
</body>
</html>

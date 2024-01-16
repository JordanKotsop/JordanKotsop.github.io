<html>
<head>
    <style>
        /* Define the colors */
        :root {
            --indigo: #4b0082;
            --purple: #800080;
            --light-purple: #e0b0ff;
            --yellow: #ffff00;
        }

        /* Set the font and background */
        body {
            font-family: Arial, sans-serif;
            background-color: var(--light-purple);
        }

        /* Style the header */
        h1 {
            color: var(--indigo);
            text-align: center;
        }

        /* Style the navigation bar */
        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color: var(--purple);
        }

        /* Style the links */
        a {
            color: var(--yellow);
            text-decoration: none;
            font-weight: bold;
        }

        /* Style the main content */
        main {
            margin: 20px;
        }

        /* Style the summary section */
        .summary {
            display: grid;
            grid-template-columns: 1fr 2fr;
            grid-gap: 10px;
        }

        /* Style the image */
        .summary img {
            width: 100%;
            height: auto;
            border-radius: 50%;
        }

        /* Style the text */
        .summary p {
            color: var(--indigo);
            font-size: 18px;
        }

        /* Style the footer */
        footer {
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: var(--purple);
            color: var(--yellow);
            padding: 10px;
        }
    </style>
</head>
<body>
    <h1>Jordan Kotsopoulos</h1>
   <nav class="nav">
      <!-- Create the nav links -->
      <a class="nav-link" href="#about">About Me</a>
      <a class="nav-link" href="#projects">My Projects</a>
      <a class="nav-link" href="#services">Services</a>
      <a class="nav-link" href="#contact">Contact Me</a>
    </nav>
    <main>
        <div class="summary">
            <img src="jordan.jpg" alt="Jordan Kotsopoulos">
            <p>
                Jordan Kotsopoulos is a strategic consultant and entrepreneur in the web3, AI and sports & entertainment industries. He has over 10 years of experience in helping clients achieve their goals and transform their businesses with cutting-edge technologies and innovative solutions. He is also the founder and CEO of Koto Labs, a web3 development studio that creates decentralized applications and platforms for various sectors and use cases. Jordan is passionate about the future of the internet and the potential of web3 to empower people and create a more open, fair and transparent world.
            </p>
        </div>
    </main>
    <footer>
        &copy; 2024 Jordan Kotsopoulos. All rights reserved.
    </footer>
</body>
</html>

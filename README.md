<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap"
      rel="stylesheet"
    />

    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>DevLinks</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div id="container">
      <div id="profile">
        <img
          src="./assets/avatar.png"
          alt="Foto de Lyvia Maria sorrindo, com tranças no cabelo, usando camiseta florida e fundo branco gelo"
        />
        <p>@olyviams</p>
      </div>

      <div id="switch" onclick="toggleMode
      ()">
        <button></button>
        <span></span>
      </div>

      <ul>
        <li>
          <a
            href="https://instagram.com/olyviams?igshid=YzAwZjE1ZTI0Zg%3D%3D&utm_source=qr"
            target="_blank"
            >Perfil Pessoal</a
          >
        </li>
        <li>
          <a href="#">Cursos e formação</a>
        </li>
        <li>
          <a
            href="https://www.canva.com/design/DAFwskx_mV8/ah_XDIdjfuUCGnILdndYWQ/edit"
            target="_blank"
            >Ver meu portfólio</a
          >
        </li>
        <li>
          <a href="https://www.youtube.com/watch?v=yKNxeF4KMsY" target="_blank"
            >Para se Inspirar</a
          >
        </li>
      </ul>
      <div id="social-links">
        <a
          href="https://api.whatsapp.com/send/?phone=5584994552418&text&type=phone_number&app_absent=0"
          target="_blank"
          ><ion-icon name="logo-whatsapp"></ion-icon>
        </a>

        <a
          href="https://github.com/olyviams?tab=repositories"
          target="_blank"
          ><ion-icon name="logo-github"></ion-icon>
        </a>

        <a
          href="https://www.youtube.com/channel/UCelw6Psn01qeInxrPbVcKnQ"
          target="_blank"
          ><ion-icon name="logo-youtube"></ion-icon>
        </a>

        <a
          href="https://www.linkedin.com/in/lyvia-maria-souza-silva-2a9a63260/"
          target="_blank"
          ><ion-icon name="logo-linkedin"></ion-icon>
        </a>
      </div>
      <footer>
        Feito com ♥ pela <a href="https://rocketseat.com.br">Rocketseat</a>
      </footer>
    </div>
    <script
      type="module"
      src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"
    ></script>
    <script
      nomodule
      src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"
    ></script>

    <script src="./script.js"></script>
  </body>

</html>

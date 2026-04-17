<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Нетцель Марина | Недвижимость</title>

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap"
    rel="stylesheet"
  />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      min-height: 100vh;
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(180deg, #8fd3cf 0%, #77c7c3 100%);
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 30px 15px;
      color: #ffffff;
    }

    .card {
      width: 100%;
      max-width: 430px;
      background:
        linear-gradient(180deg, rgba(255,255,255,0.08), rgba(255,255,255,0.03)),
        linear-gradient(180deg, #57b8b5 0%, #3f9e9d 100%);
      border-radius: 34px;
      padding: 34px 24px 28px;
      box-shadow: 0 20px 50px rgba(33, 88, 88, 0.22);
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    .card::before {
      content: "";
      position: absolute;
      width: 220px;
      height: 220px;
      background: rgba(255, 214, 230, 0.24);
      border-radius: 50%;
      top: -90px;
      right: -80px;
    }

    .card::after {
      content: "";
      position: absolute;
      width: 180px;
      height: 180px;
      background: rgba(255, 255, 255, 0.08);
      border-radius: 50%;
      bottom: -90px;
      left: -70px;
    }

    .content {
      position: relative;
      z-index: 2;
    }

    .avatar {
      width: 112px;
      height: 112px;
      border-radius: 50%;
      object-fit: cover;
      display: block;
      margin: 0 auto 16px;
      border: 6px solid rgba(255, 255, 255, 0.65);
      background: #ffffff;
    }

    .username {
      font-size: 18px;
      font-weight: 500;
      color: #eafcfc;
      margin-bottom: 18px;
    }

    .title {
      font-size: 34px;
      line-height: 1.15;
      font-weight: 500;
      margin-bottom: 18px;
      letter-spacing: 0.2px;
    }

    .description {
      font-size: 17px;
      line-height: 1.6;
      font-weight: 300;
      color: rgba(255, 255, 255, 0.95);
      margin-bottom: 28px;
    }

    .main-button {
      display: block;
      width: 100%;
      text-decoration: none;
      background: linear-gradient(180deg, #f7c7da 0%, #f0b8cf 100%);
      color: #ffffff;
      border-radius: 999px;
      padding: 18px 20px;
      margin-bottom: 28px;
      box-shadow: 0 10px 24px rgba(216, 129, 166, 0.22);
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }

    .main-button:hover {
      transform: scale(1.03);
      box-shadow: 0 14px 28px rgba(216, 129, 166, 0.28);
    }

    .main-button-top {
      display: block;
      font-size: 24px;
      line-height: 1.1;
      font-weight: 700;
      margin-bottom: 6px;
    }

    .main-button-bottom {
      display: block;
      font-size: 16px;
      line-height: 1.2;
      font-weight: 500;
      opacity: 0.98;
    }

    .social-block {
      background: rgba(255, 218, 232, 0.18);
      border-radius: 28px;
      padding: 28px 20px 24px;
      backdrop-filter: blur(3px);
    }

    .social-title {
      font-size: 28px;
      line-height: 1.2;
      font-weight: 500;
      margin-bottom: 18px;
    }

    .social-icons {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 18px;
      flex-wrap: wrap;
    }

    .social-link {
  width: 64px;
  height: 64px;
  border-radius: 50%;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}

    .social-link:hover {
      transform: scale(1.1);
      background: rgba(255, 255, 255, 0.26);
    }

    .social-icon {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
}

    @media (max-width: 480px) {
      .card {
        padding: 28px 18px 22px;
        border-radius: 28px;
      }

      .avatar {
        width: 96px;
        height: 96px;
      }

      .username {
        font-size: 16px;
      }

      .title {
        font-size: 28px;
      }

      .description {
        font-size: 15px;
      }

      .main-button-top {
        font-size: 21px;
      }

      .main-button-bottom {
        font-size: 14px;
      }

      .social-title {
        font-size: 24px;
      }

      .social-link {
        width: 64px;
        height: 64px;
        border-radius: 50%;
        overflow: hidden;
        display: flex;
        align-items: center;
        justify-content: center;
      }

      .social-icon {
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 50%;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="content">

      <!-- ВСТАВЬТЕ СЮДА ССЫЛКУ НА АВАТАРКУ -->
      <img class="avatar" src="https://sun9-34.userapi.com/s/v1/ig2/WlalYI_G2iiMS45vK7Z95ZU06zjAMfJpcs1hu451-LUxoSjglb9CdXui1cK3-u2N7GOGE9toYVLNkM_1DGtDAEbQ.jpg?quality=95&as=32x32,48x48,72x72,108x108,160x160,240x240,360x360,469x469&from=bu&u=4zJu-o-PUsfJ9d7mw9YZ05OcFAEipqFYdE6c-tRxNmo&cs=469x0" alt="Нетцель Марина" />

      <div class="username">@Marina_agent_spb</div>

      <h1 class="title">Нетцель Марина | Недвижимость</h1>

      <p class="description">
        Меня зовут Марина Нетцель – я агент по недвижимости Санкт-Петербурга.
        Опыт работы более 15 лет: от новостроек до старого фонда
      </p>

      <!-- ВСТАВЬТЕ СЮДА ССЫЛКУ НА ЛИЧНЫЕ СООБЩЕНИЯ -->
      <a class="main-button" href="https://t.me/Marina_agent_spb" target="_blank" rel="noopener noreferrer">
        <span class="main-button-top">Написать</span>
        <span class="main-button-bottom">в личные сообщения</span>
      </a>

      <div class="social-block">
        <div class="social-title">Мои социальные сети:</div>

        <div class="social-icons">
          <!-- ИКОНКА 1 -->
          <!-- ВСТАВЬТЕ СЮДА ССЫЛКУ НА СОЦСЕТЬ И ПУТЬ К ИКОНКЕ -->
          <a class="social-link" href="https://t.me/netsel_spb" target="_blank" rel="noopener noreferrer">
            <img class="social-icon" src="https://sun9-55.userapi.com/s/v1/ig2/2PWLO_heA_9RX2HLmM_CZa5NMImtZ85Cc0ZNLNuFBg34s2OF_WzBz6iWyExJAgTy_J2yYgc8mWOKDs8TAuN2rUi6.jpg?quality=95&as=32x32,48x48,72x72,108x108,160x160,240x240,360x360,480x480,540x540,640x640,720x720,1080x1080,1280x1280,1440x1440,2048x2048&from=bu&cs=2048x0" alt="Соцсеть 1" />
          </a>

          <!-- ИКОНКА 2 -->
          <a class="social-link" href="https://www.instagram.com/nettselmarina?igsh=MWVnaWhjZ2FoazN5cg==" target="_blank" rel="noopener noreferrer">
            <img class="social-icon" src="https://sun9-63.userapi.com/s/v1/ig2/YXF9jVAp-CHKXhDv0iDg3k6LxA5HNe2mI1ZCI7V4s2BazrMdXMcD0s7ERASnymRg6YGnNJ2mjqMGONcxkn75DGYT.jpg?quality=95&as=32x32,48x48,72x72,108x108,160x160,240x240,360x360,480x480,540x540,640x640,720x720,1080x1080,1280x1280,1440x1440,2048x2048&from=bu&cs=2048x0" alt="Соцсеть 2" />
          </a>

          <!-- ИКОНКА 3 -->
          <a class="social-link" href="https://vk.ru/netsel_spb" target="_blank" rel="noopener noreferrer">
            <img class="social-icon" src="https://sun9-58.userapi.com/s/v1/ig2/WaKqIEpyX8PrJlCVa5kzM0NHDaQIAdfgDXsJ8YQ69VFoxQWMeUusC34GoUFGbO3af1b702ZGAezVxMOKTKd-w8M_.jpg?quality=95&as=32x32,48x48,72x72,108x108,160x160,240x240,360x360,480x480,540x540,640x640,720x720,1080x1080,1280x1280,1440x1440,2048x2048&from=bu&u=KFO7XXOq408ev9HONGOq9vqfpWOeYiDEafQbxeTK5PM&cs=2048x0" alt="Соцсеть 3" />
          </a>

          <!-- ИКОНКА 4 -->
          <a class="social-link" href="https://max.ru/join/_2RKlyGJ-DWcVdIiRn9YN5HVI_V5Gy9VeKW-vB3fJ48" target="_blank" rel="noopener noreferrer">
            <img class="social-icon" src="https://sun9-22.userapi.com/s/v1/ig2/0aYWX49abL-fPwWe4Jw4NsRerNyEHDSnhzlIzZ20Z38fzDvtTxRfElkx-tcH2gfhncpsoimUgtCTtcp_UE4MZhvq.jpg?quality=95&as=32x32,48x48,72x72,108x108,160x160,240x240,360x360,480x480,540x540,640x640,720x720,1080x1080,1280x1280,1440x1440,2048x2048&from=bu&cs=2048x0" alt="Соцсеть 4" />
          </a>
        </div>
      </div>

    </div>
  </div>
</body>
</html>

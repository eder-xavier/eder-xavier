### Éder here.

- ☘️ Dev Full stack.
- 📜 Studing Assembly.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Custom GitHub Stats</title>
  <style>
    body {
      background-color: #f5f5dc; /* Bege */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    picture {
      border: 5px solid #ffffff; /* Branco */
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      animation: fadeIn 2s ease-in-out;
    }

    img {
      width: 100%;
      height: auto;
      display: block;
    }

    @keyframes fadeIn {
      0% {
        opacity: 0;
        transform: scale(0.9);
      }
      100% {
        opacity: 1;
        transform: scale(1);
      }
    }
  </style>
</head>
<body>
  <picture>
    <source
      srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=dark&bg_color=blue&text_color=white&icon_color=white"
      media="(prefers-color-scheme: dark)"
    />
    <source
      srcset="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=light&bg_color=white&text_color=blue&icon_color=blue"
      media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
    />
    <img src="https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&bg_color=white&text_color=blue&icon_color=blue" />
  </picture>
</body>
</html>





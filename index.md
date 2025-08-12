<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>PURKOT</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1, user-scalable=no">
  <style>
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      height: 100%;
      width: 100vw;
      margin: 0;
      padding: 0;
      background: #000;
      overflow: hidden;
      position: relative;
    }
    .video-container {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #000;
      z-index: 1;
    }
    video {
      width: 100vw;
      height: 100vh;
      object-fit: contain;
      background: #000;
      display: block;
      max-width: 100vw;
      max-height: 100vh;
    }
    @media screen and (max-width: 767px) {
      video {
        width: 100vw;
        height: 100vh;
        max-width: 100vw;
        max-height: 100vh;
      }
    }
    @media screen and (orientation: portrait) {
      video {
        width: 100vw;
        height: 100vh;
      }
    }
    @media screen and (orientation: landscape) {
      video {
        width: 100vw;
        height: 100vh;
      }
    }
  </style>
</head>
<body>
  <div class="video-container">
    <video src="Purkot_mov.MOV" controls autoplay loop muted playsinline>
      Your browser does not support the video tag.
    </video>
  </div>
</body>
</html>

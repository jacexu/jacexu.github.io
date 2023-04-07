<!DOCTYPE html>
<html>
  <head>
    <title>Jace.me</title>
    <meta charset="UTF-8">
    <style>
      body {
        background-color: #F0F0F0;
        font-family: Arial, sans-serif;
      }
      #qr-code {
        display: block;
        margin: 50px auto;
        width: 200px;
      }
      #qr-code img {
        width: 100%;
        height: auto;
      }
      #qr-text {
        text-align: center;
        font-size: 16px;
        margin-bottom: 50px;
      }
      #copyright {
        position: fixed;
        bottom: 0;
        left: 0;
        width: 100%;
        text-align: center;
        font-size: 12px;
        color: #777;
        padding: 10px;
        background-color: #F0F0F0;
      }
    </style>
  </head>
  <body>
    <div id="qr-code">
      <img src="path/to/qr-code.png" alt="QR Code">
    </div>
    <div id="qr-text">
      <p>欢迎扫码关注公众号</p>
    </div>
    <div id="copyright">
      <p>©2011-2023, Jace.me. All Rights Reserved.</p>
    </div>
  </body>
</html>

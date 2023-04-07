<html>
  <head>
    <title>Jace.me</title>
    <meta charset="UTF-8">
    <style>
      body {
        background-color: #FFFFFF;
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
        background-color: #FFFFFF;
      }
    </style>
    <script>
      // 更改此处开始
      var startYear = 2011; // 版权信息开始年份
      var endYear = new Date().getFullYear(); // 当前年份
      // 更改此处结束

      // 获取版权信息元素
      var copyright =
        document.getElementById("copyright");

      // 如果版权开始年份和当前年份不同，则显示年份范围
      if (startYear !== endYear) {
        var yearRange = startYear + "-" + endYear;
        var text =
          "©" + yearRange + ", <a href='https://jace.me'>Jace.me</a>. All Rights Reserved.";
        copyright.innerHTML = "<p>" + text + "</p>";
      } else {
        var text =
          "©" + endYear + ", <a href='https://jace.me'>Jace.me</a>. All Rights Reserved.";
        copyright.innerHTML = "<p>" + text + "</p>";
      }
    </script>
  </head>
  <body>
    <div id="qr-code">
      <img src="path/to/qr-code.png" alt="QR Code">
    </div>
    <div id="qr-text">
      <p style="font-size: 14px;">欢迎扫码关注公众号</p>
    </div>
    <div id="copyright">
      <!-- 版权信息会在 JavaScript 中动态更新 -->
    </div>
  </body>
</html>

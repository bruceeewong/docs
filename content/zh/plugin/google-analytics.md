---
title: Google Analytics
category: 插件
position: 301
badge: Pro
---

> Offical documentation: https://developers.google.com/analytics/devguides/collection/analyticsjs

To use google analytics directly from your domain name, just replace `https://www.google-analytics.com/analytics.js` to `https://${doamin}/__/google-analytics/analytics.js`

```diff
<!-- Google Analytics -->
<script>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
-    })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');
+    })(window,document,'script','https://${doamin}/__/google-analytics/analytics.js','ga');
ga('create', 'UA-XXXXX-Y', 'auto');
ga('send', 'pageview');
</script>
<!-- End Google Analytics -->
```

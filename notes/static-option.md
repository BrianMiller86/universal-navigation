## Option #2: Simple iFrame Universal Navigation & Footer

##### Using Internet Explorer? Be sure you are not running in "_Compatibility Mode_" when testing:
> Press the `F12 Key`, and click "Internet Explorer X Compatibilty Mode" and change to latest non-compatibility mode from the dropdown

___!!! Place this code at the very top of your site, outside of any container divs, and as close to the opening \<body\> tag as possible. The header should expand to 100% of the screen width, even if your current site has a fixed width. !!!___


```html
<iframe width="100%" height="86px" src="//static-assets.ny.gov/load_global_menu/ajax?iframe=true" frameborder="0" style="border:none; overflow:hidden; width:100%; height:86px;" scrolling="no">
            Your browser does not support iFrames
</iframe>    
<!-- Google Tag Manager -->
    <noscript><iframe src="//www.googletagmanager.com/ns.html?id=GTM-T4FP6H" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
    <script type="text/javascript">(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0];var j=d.createElement(s);var dl=l!='dataLayer'?'&l='+l:'';j.src='//www.googletagmanager.com/gtm.js?id='+i+dl;j.type='text/javascript';j.async=true;f.parentNode.insertBefore(j,f);})(window,document,'script','dataLayer','GTM-T4FP6H');</script>
<!-- End Google Tag Manager -->
```

### Footer Embed Code (pair with static banner)

 ___!!! Place this code at the very bottom of your site, outside of any container divs, as close to and before the closing \<body\> tag. The footer should expand to 100% of the screen, even if your current site has a fixed width. !!!___

```html
<iframe width="100%" height="86px" src="//static-assets.ny.gov/load_global_footer/ajax?iframe=true" frameborder="0" style="border:none; overflow:hidden; width:100%; height:86px;" scrolling="no">
            Your browser does not support iFrames
</iframe>

```

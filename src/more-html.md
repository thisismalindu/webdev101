# More HTML

අද අපි තව HTML ටිකක් බලමු. ඊළඟ පාඩමෙන් අපිට CSS පටන් ගන්න පුලුවන්. අද අපි ටිකක් වේගෙන් යනවා. මොකද ගොඩක් දේවල් එක වගේ දෙවල් තියෙන්නෙ. අද ලොකුවට අලුත් දේවල් නෑ. එත් HTML ලියද්දි දැනගෙන ඉන්න ඕනෙ දේවල් කීපයක් තමා අද කතා කරන්නේ. 

අද අපි සරල website එක්ක ආකෘතියක් හදාගන්න තමා ලෑස්ති වෙන්නේ. [මේ තියෙන්නෙ](https://thisismalindu.com/basicwebsite2.html) අද අපි හදන්න බලාපොරොත්තු වෙන website එක. මේක ඇත්තටම අපිට අද උගන්වන කිසි දෙයක් නැතිව දැනට දන්න දේවල් වලින් හදාගන්න පුලුවන්. ඒත් ඇත්තටම මේ වගේ දෙයක් හදද්දී හදන්න ඕනේ කොහොමද කියන දේ, ඒ දේවල් ඇයි එහෙම කරන්නෙ වගේ දේවල් තමා අද කතා කරන්නේ. ඒක නිසා ඇත්ත websites ලියද්දී ගොඩක් වැදගත් වෙන දේවල් තමා අද කතා කරන්නේ.

අද අපිට ඕනෙ වෙන images, codes එහෙම මන් දාලා තියෙනවා පල්ලහින්. ඔයාට මන් කරන එකත් එක්ක follow කරන් යන්න ඕනෙ නම් මෙතනින් ඒ දේවල් ටික ගන්න පුලුවන්. Images ඕනේ නම් මෙතනින් download කරගන්න, නැත්තන් ඔයාට ඕනේ නම් කෙලින්ම link එක copy කරලා use කරන්නත් පුලුවන්. Images download කරන්න නම් අදාල image එක උඩ right click කරලා "Save image as" වලින් save කරගන්න පුලුවන්.

ඒ වගේම full project file එක [මෙතනින් download කරගන්න](https://github.com/thisismalindu/basic-website-tutorial-webdev101/archive/refs/heads/html_only.zip) පුලුවන් zip එකක් විදිහට. ඒක ඔයාට extract කරගෙන ඕනේ නම් ඔයාගෙ code එකයි මගේ එකයි සසඳන්න පුලුවන්.

|||||
|---|---|---|---|
|![](https://thisismalindu.com/basicwebsite/images/website.png)|![](https://thisismalindu.com/basicwebsite/images/chess.png)|![](https://thisismalindu.com/basicwebsite/images/movies.png)|![](https://thisismalindu.com/basicwebsite/images/chat.png)|

<br>
<br>

`HTML Template`
```html
<html>
  <head>
    <title>About Me</title>
  </head>
  <body>
    <nav>
      <ul>
        <li><a href="./index.html">Home</a></li>
        <li><a href="./gallery.html">Gallery</a></li>
        <li><a href="./about.html">About</a></li>
        <li><a href="./contact.html">Contact</a></li>
      </ul>
    </nav>
    <br />
    <br />
    
    <br>
    <br>
    <footer>
        <ul>
            <li><a href="https://instagram.com/thisismalindu">Instagram</a></li>
            <li><a href="https://facebook.com/thisismalindu">Facebook</a></li>
            <li><a href="https://youtube.com/@thisismalindu">YouTube</a></li>
            <li><a href="https://tiktok.com/@thisismalindu">TikTok</a></li>
        </ul>

        <p> &copy; Copyright 2023 Malindu Bandara. All Rights Reserved. </p>
    </footer>
  </body>
</html>
```

<br>

[`imagegallery.html`](https://thisismalindu.com/imagegallery.html)
```html
<html>
    <head>
        <title>Image Gallery</title>
    </head>
    <body>
        <h1>Image Gallery</h1>
        <a href="https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_square.jpg"><img src="https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_square.jpg" alt="cat picture" height="250" width="250"></a>
        <a href="https://cdn.pixabay.com/photo/2014/11/30/14/11/cat-551554_640.jpg"><img src="https://cdn.pixabay.com/photo/2014/11/30/14/11/cat-551554_640.jpg" alt="cat picture" height="250" width="250"></a>
        <a href="https://images.saymedia-content.com/.image/ar_1:1%2Cc_fill%2Ccs_srgb%2Cfl_progressive%2Cq_auto:eco%2Cw_1200/MTk2NzY3MjA5ODc0MjY5ODI2/top-10-cutest-cat-photos-of-all-time.jpg"><img src="https://images.saymedia-content.com/.image/ar_1:1%2Cc_fill%2Ccs_srgb%2Cfl_progressive%2Cq_auto:eco%2Cw_1200/MTk2NzY3MjA5ODc0MjY5ODI2/top-10-cutest-cat-photos-of-all-time.jpg" alt="cat picture" height="250" width="250"></a><br>
        <a href="https://i.natgeofe.com/k/ad9b542e-c4a0-4d0b-9147-da17121b4c98/MOmeow1_square.png"><img src="https://i.natgeofe.com/k/ad9b542e-c4a0-4d0b-9147-da17121b4c98/MOmeow1_square.png" alt="cat picture" height="250" width="250"></a>
        <a href="https://headsupfortails.com/cdn/shop/articles/Cat_s_Mind_x630.jpg?v=1624444348"><img src="https://headsupfortails.com/cdn/shop/articles/Cat_s_Mind_x630.jpg?v=1624444348" alt="cat picture" height="250" width="250"></a>
        <a href="https://th-thumbnailer.cdn-si-edu.com/oVabaIyItVRvlSwByJk6a6_IFxs=/800x800/filters:focal(1850x1738:1851x1739)/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer_public/31/97/31979e81-313f-4d98-987c-fcce125a4d08/gettyimages-696166057.jpg"><img src="https://th-thumbnailer.cdn-si-edu.com/oVabaIyItVRvlSwByJk6a6_IFxs=/800x800/filters:focal(1850x1738:1851x1739)/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer_public/31/97/31979e81-313f-4d98-987c-fcce125a4d08/gettyimages-696166057.jpg" alt="cat picture" height="250" width="250"></a><br>
        <a href="https://catamazing.com/cdn/shop/files/catshark.jpg?v=1649869148"><img src="https://catamazing.com/cdn/shop/files/catshark.jpg?v=1649869148" alt="cat picture" height="250" width="250"></a>
        <a href="https://images.theconversation.com/files/443350/original/file-20220131-15-1ndq1m6.jpg?ixlib=rb-1.1.0&rect=0%2C0%2C3354%2C2464&q=45&auto=format&w=926&fit=clip"><img src="https://images.theconversation.com/files/443350/original/file-20220131-15-1ndq1m6.jpg?ixlib=rb-1.1.0&rect=0%2C0%2C3354%2C2464&q=45&auto=format&w=926&fit=clip" alt="cat picture" height="250" width="250"></a>
        <a href="https://hips.hearstapps.com/hmg-prod/images/black-cat-names-64ad9a37e2690.jpg?crop=0.667xw:1.00xh;0.171xw,0&resize=1200:*"><img src="https://hips.hearstapps.com/hmg-prod/images/black-cat-names-64ad9a37e2690.jpg?crop=0.667xw:1.00xh;0.171xw,0&resize=1200:*" alt="cat picture" height="250" width="250"></a>

    </body>
</html>
```
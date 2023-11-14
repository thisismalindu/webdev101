# HTML Basics

[Watch the Related Video 👇 ![HTML Basics](https://i3.ytimg.com/vi/z9U9lPacbIw/maxresdefault.jpg)](https://youtu.be/z9U9lPacbIw)

ඔන්න අද අපි HTML ඉගෙන ගන්න තමයි ලෑස්ති වෙන්නේ. මේ වෙනකොට කලින් පාඩම් ටික බලලා ඇති කියලා හිතනවා. එහෙම බැලුවෙ නැත්තන් අනිවාරෙන් ඒ ටික බලන්න. අඩුම තරමෙන් කලින් පාඩම බලන්න. මොකද ඔයාට අද කියන දේවල් හොදට තේරෙන්න නම් අනිවාරෙන් ඒ දැනුම අවශ්‍ය වෙනවා.

මං කලින් කියලා තියනවා website එකක් හැදෙන්නෙ HTML, CSS, JS තුන එකතු වුනාම කියලා. ඉතින් HTML වලින් අපේ website එකේ structure එක තමා හදලා දෙන්නේ. දැන් අපි බලන්න යන්නේ කොහොමද මේ structure එක හදල දෙන්නේ කියන එක.

මුලින්ම ඔයා VSCode open කරගන්න ඕනෙ. ඒකට startmenu එකට ගිහින් VSCode කියලා search කරන්න.

![Open VSCode](image-17.png)

නැත්තන් desktop shortcut එකෙනුත් පුලුවන්.

කෝම හරි VSCode open කරගන්න.

මේ Welcome page එක close කරගන්න.

![Close the welcome page](image-18.png)

දැන් Ctrl+N ඔබලා අලුත් file එකක් ගන්න.

![Create New File](image-19.png)

දැන් මේ file එකේ language එක HTML කියලා තෝරන්න.

![Choose HTML as language](image-20.png)

දැන් මේ file එකේ `Hello World` කියලා type කරන්න.

![Type Hello World](image-21.png)

දැන් Ctrl+S ඔබලා save කරන්න. File එකේ නම විදිහට `mywebsite.html` කියලා දෙන්න. දැනට අපි මේක desktop එකේ save කරමු. එහෙම නැත්තන් ඔයාට ලෙසියෙන් හොයාගන්න පුලුවන් තැනක save කරගන්න.

![Save File](image-22.png)

දැන් ඒ save කරපු file එක හොයාගෙන, Right Click කරලා Open With එකට ගිහින් ඔයාගේ Web Browser එක තෝරන්න. මන් recommend කරනවා Google Chrome use කරන්න කියලා. එතකොට මං කරන දේවල්ම ඔයාටත් බලාගෙන කරන්න පුලුවන්. ටිකක් experience ආවම ඔයාට ඕනම දෙයක් ඕනම browser එක්කින් කරන්න පුලුවන් වෙයි. නමුත් දැනට හොඳම දේ මං කරන විදිහට කරන එක.

![Open Saved file using google chrome browser](image-23.png)

දැන් ඔයාට web browser එකෙන් පේනවා ඇති `Hello World` කියලා. හරි ඔන්න තියනවා ඔයාගෙ website එක.

![Browser Output](image-24.png)

ඔව්. ඔහොමත් පුලුවන් website එක හදන්න. හරියට ඔයා නිකන් MS Word open කරගෙන ලියාගෙන ලියාගෙන යනවා වගේ මේකෙත් ලියාගෙන ලියාගෙන යන්න පුලුවන්. ඒත් කිසිම දෙයක් ඔයාට ඕනෙ විදිහට පාට කරන්න හැඩ වැඩ දාන්න නම් වෙන්නෙ නෑ. මොකද මෙහෙම හැදුවොත් අපිට ඒ වගෙ දේවල් browser එකට කියන්න විදිහක් නෑ. අපිට browser එක එක්ක හරියට communicate කරන්න අවශ්‍ය නම් browser එක කතා කරන්න කැමති විදිහට අපිත් කතා කරන්න ඕනේ.

ඔයාට මතකද දන්නේ නෑ අපි මුලම දවසකදී ලීවා මෙන්න මේ වගේ code එකක්. ඕනේ නම් [මෙතනින්](installing-a-code-editor.md#:~:text=%E0%B6%B8%E2%80%8C%E0%B7%99%E0%B6%B1%E0%B7%8A%E0%B6%B1%20%E0%B6%B8%E0%B7%9A%20code%20%E0%B6%91%E0%B6%9A%20copy%20%E0%B6%9A%E0%B6%BB%E0%B6%BD%E0%B7%8F%20paste%20%E0%B6%9A%E0%B6%BB%E0%B6%B1%E0%B7%8A%E0%B6%B1%20%F0%9F%91%87) බලන්න අපි කවද්ද ඒක ලීවෙ කියලා.

```html
<html>
    <head>
        <title>Test Website</title>
    </head>
    <body>
        <h1>
            Hello World
        </h1>
    </body>
</html>
```
එදා මන් කීවා මං මේක පස්සෙ දවසක විස්තර කරන්නම්, දැනට අපි මේක copy paste කරලා ඔක්කොම හරියට වැඩද බලමු කියලා. ඔන්න දැන් මන් මේක විස්තර කරන්නයි යන්නේ.

මේ code එක දිහා බැලුවම අපිට ඇත්තටම වචන ටික කියවලා idea එකක් ගන්න පුලුවන් මොනවද මේ කියන්නේ කියලා. පොඩ්ඩක් try එකක් දීල බලන්න. ඔන්න මන් කියන්නයි යන්නේ.

මේ code එකේ පැහැදිලිවම එක රටාවක් බලාගන්න පුලුවන්. ඒ තමයි අපිට පේනවා එකම වචනේ දෙපාරක් ලියල තියනවා තැන් දෙකකදී. ඒ වගේම තමා ඒ වචන දෙක එක කෙලින් align වෙලා තියනවා. මේ විදිහට එකම වචනෙ තියෙන හැම තැනකදිම අපිට පේනවා ඒවා align වෙලා තියනවා. පොඩි වෙනසකට තියෙන්නෙ ඒ වචනෙ ගාව තියන සංකේත පොඩ්ඩක් වෙනස් වෙලා තියනවා. මොකද්ද මන් මේ කියන්න හදන්නේ.

HTML වලදී අපි ලියන්නෙ browser එක කරන්න ඕනේ දේවල්. ඒ කියන්නෙ අපි browser එකට කියනවා "image" එකක් දාන්න, "heading" එකක් දාන්න කියලා. ඒවා browser එකට කියන්න HTML හදපු කට්ටිය අපිට හඳුන්වලා දුන්නා HTML tags. ඔන්න තියනවා HTML tag එකක්. අපි ඒක ආස්‍රයෙන් බලමු මොකද්ද HTML tag එකක් කියන්නෙ කියලා.

```html
<h1>Hello World</h1>
```
මේකෙන් අපි web browser එකට කියනවා, `Hello World` කියලා "heading" එකක් දන්න කියලා.

අපිට මුලින්ම බලාගන්න හම්බෙන්නෙ `<h1>` කියලා. මොකද්ද මේකේ තේරුම? මේකට කියන්නේ අපි opening tag කියලා. මේකෙන් තමා අපි HTML tag එක open කරන්නේ. මෙකෙන් අපි කියනවා browser එකට ඔන්න අපි content වගයක් දෙන්නයි යන්නේ. මෙන්න මේක තමා ඒ content එකේ වර්ගේ. බලපොරොත්තුවෙන් ඉන්න කියල. දැන් browser එක බලාගෙන ඉදී content එක ලැබෙනකන්. ඔයා අහයි මොනවද මේ `<` `>` කියන්නේ කියලා. ඒවා HTML හදපු කට්ටිය සාකච්ඡා කරලා තීරණය කරපු දෙයක්. අපි මෙන්න මෙහෙම ලියමු HTML tag එකක් ලියද්දි කියලා. ඒක HTML syntax එහෙම නැත්තන් ව්‍යාකරණ වල තියන දෙයක්. ඒක ඔයාට ප්‍රශ්න කරන්න අයිතියක් නෑ, ප්‍රශ්න කරලා තේරුමකුත් නෑ. අපි content ලියන්න ලෑස්ති වෙද්දි අපි මුලින්ම opening tag එක ලියන්න ඕනේ. ඒ opening tag එක content එකේ කොටසක් නෙමේ කියලා හදුනගන්න ඒක වෙනස් විදිහකට ලියන්න ඕනේ. ඒක නිසා තමා අපි ඒක මේ විදිහට ලියන්නෙ. මොකද්ද එතකොට `h1` කියන්නේ? `h1` කියන්නේ "First Level Heading" කියන එක. හිතන්න අපි මොකක් හරි පාඩමක් ඉගෙන ගන්නවා කියලා, හරියට ඔයා මේ WebDev101 පාඩම ඉගෙන ගන්නව වගේ. එතකොට ඔයාට මේ articles වල පේනවා ඇති headings තියනවා, subheadings තියනවා කියලා. එතකොට ඔන්න ඔහොම හරි හමන් structure එක්කට දේවල් display කරන්න තමා අපිට විවිධ headings වර්ග තියෙන්නේ. headings වල තියෙන ලොකුම heading එක තමා `h1` කියන්නේ. `h1` ඉදල `h6` වෙනකන් heading tags තියෙනවා. අපි ඉස්සරහට බලමුකෝ ඒවා මොන වගේද කියලා. දැනට මේ tag එකක් කියන්නෙ මොකද්ද කියලා තේරුන් ගන්න බලමු.

ඊළඟට අපිට හම්බෙන්නේ Hello World එක. මේක තමා අපේ tag එකේ content එක. මේක තම browser එක display කරන්නේ. මේක තමා අවසන් website එකේ බලගන්න ලැබෙන්නේ. මෙතනදි අපිට වචනයක්, දෙකක්, නැත්තන් මුලු ඡේදයක් ම වුනත් ලීවහකි. ඒ විතරක් නෙමේ ඔයා ඉස්සරහට දකී අපිට තව තව දේවල් දාන්න පුලුවන්. දැනට අපි text දාමු. අපි Hello World කියන text එක තෝරගත්තා අපේ tag එකේ content එක විදිහට. මෙතනට ඔයා කැමති එකක් type කරන්න. සාමන්‍යයෙන් programming වැඩ වලදි මුලින්ම ලියන program එකේදි ලියන දේ තමා Hello World කියන්නේ. ඒක මේ නිකන් මිනිස්සු හදාගත්තු පුරුද්දක් විතරයි. හරියට අපි සුබ වැඩක් කරද්දී කිරිබත් කන්නේ, අන්න ඒ වගෙ තමා. Programming සුබ වෙන්න නම් පලවෙනි වැඩේදී Hello World කියල ලියන්න ඕනෙ. 😂

Content එක ලීවායින් පස්සේ, අපි ලියන්නෙ closing tag එක. ඒක තමා ඔය `</h1>` කියලා තියෙන්නේ. අපි මුලින්ම browser එකට කීවා content වගයක් බලාපොරොත්තු වෙන්න, ඒකෙ වර්ගෙ "heading" කියන වර්ගෙ කියලා. ඊට පස්සෙ එයා සැරසුනාම, අපි content එක දුන්නා, `Hello World` කියලා. දැන් browser එක දන්නෙ නෑ අපි content දීලා ඉවරද කියලා. ඒක නිසා අපි එයාට කියනවා හරි දැන් content දීල ඉවරයි. දැන් අපි ඊලඟ වැඩේට යමු කියලා. ඔය අවසානය සනිටුහන් කරන්න තමා අපි closing tag එක use කරන්නේ. ඒකත් opening tag එක වගේම තමා, opening tag එකේ වර්ගෙම තියෙන්න ඕනෙ. ඒ කියන්නෙ මෙතනදි මේකත් `h1` වෙන්නම ඕනේ, නැත්තන් ඉතින් ඇත්තට ගැලපීමකුත් නෑනේ. හැබැයි එක වෙනස් කමක්. මේකේ `/` සංකේතයක් තියනවා. ඒක තියෙන්නේ මේක වෙනත් opening tag එකකින් වෙන් කරල හදුනාගන්න. නැත්තන් browser එක හිතුවොත් අපි content එක අස්සේ තවත් tag එකක් දාන්න යනවා කියලා. මොකද ඇත්තටම එහෙම කරන එකම තමා අපි HTML ලියද්දි තනිකර කරන්නේ. එක tag එකක් ඇතුලේ තව tag එකක් දාන්න පුලුවන්. ඉතින් අපි browser එකට පැහැදිලිව කියන්න ඕනේ, මේක තවත් opening tag එකක් නෙමේ, මේ අපි අන්තිමට open කරපු tag එකේ closing tag එක කියලා. එතකොට browser එක හා හරි එහෙනම් කියල ඒක පිලි අරගෙන ඊලඟ tag එක display කරන්න ලෑස්ති වෙනවා.

ඉතින් ඔන්න ඔහොම තමා HTML tag එකක් හැදෙන්නේ. ඔහොම tags ගොඩකින් තමා HTML document එකක් හැදෙන්නේ. heading tag (`h1`) වගේ තව tags ගොඩක් තියනවා.

දැන් අපි ආපහු අර ලොකු code එක දිහා බලමු.

```html
<html>
    <head>
        <title>Test Website</title>
    </head>
    <body>
        <h1>
            Hello World
        </h1>
    </body>
</html>
```

දැන් ඔයාට හොදට තේරෙනවා ඇති මොකද්ද මේ වෙන්නෙ කියලා. මෙතන පැහදිලිවම HTML tags ගොඩක් තියෙන්නේ. ඒ වගේම මන් කලින් කීවා වගේ HTML tags ඇතුලේ තව HTML tags. හැම tag එකක්ම open වෙනවා වගේම close වෙලා තියෙනවා. හොඳ පැහැදිලි structure එකක් අපේ website එකට ලැබිලා තියනවා. දැන් අපි මේ එකින් එක කියවලා බලමු මොනවද මේ තියෙන්නේ කියලා.

පළවෙනියට බලාගන්න පුලුවන්, `<html>` කියලා. මේ තියෙන්නේ "root" tag එක. මේකෙන් තමා අපි browser එකට කියන්නෙ ඔන්න අපේ website එකේ අන්තර්ගතය මන් කියන්නයි යන්නේ කියලා. ඒ වගේම තමා මේ tag එකෙන් අපිට තව ප්‍රයෝජන ගොඩක් ගන්න පුලුවන් වෙනවා ඉස්සරහට. දැනට හිතාගන්න මෙහෙම. ඔයාම හිතලා බලන්නකො අපි මේ website හදද්දි සෑහෙන්න පිලිවෙල ගැන කතා කරනවා නේ. ඉතින් අපි හැමදේම හොද පිලිවෙලකට නිතියකට කරාම අපිටත් ලේසි browser එකටත් ලේසි. ඉතින් ඒ පිලිවෙලේ කොටසක් විදිහට දැනට මේක දකින්න. හරියට අපි browser එකට කියනවා, ඔන්න මං මගේ HTML Code එක පටන් ගන්නයි යන්නේ වගේ.

හරි, ඊලඟට අපිට බලාගන්න පුලුවන් `<head>` tag එක. මේක තියෙන්නේ browser එකට අපේ website එක ගැන විශේෂ තොරතුරු ටිකක් දෙන්න. මේ දේවල් අපේ website එකේ display වෙන්නේ නෑ. මේවා නිකන් අපේ website එකේ නම, description එක වගේ දේවල් අන්තර්ගත කරන්න තියෙන කොටස. මෙතනදි සම්පූර්නෙන් අපි browser එකට සහ, search engine (Google වගේ) වලට දෙන විස්තර කීපයක් තියෙන්නේ. මේවා අපේ end user ට එච්චර වැඩක් නෑ. (end user කියන්නේ අපේ website එක බලන්න එන අයට).

එකම එක දෙයක් නම් පේනවා, ඒ තමා website එකේ නම. ඒක තමා අපිට ඊලඟට පේන්න තියෙන්නේ. `<title>` tag එක. මේකෙන් අපිට website එකේ title එක, එහෙම නැත්තන් website ඒකේ නම මොකද්ද කියලා කියන්න පුලුවන්. Google වගෙ search engine එක්කින් ඔයාගෙ website එක search කරාම results වල ඔයාගෙ website එක පෙන්නද්දි පෙන්නනන නම තමා මේ.

![html title in search results](image-25.png)

ඒ වගේම තමා ඔයා browser එකෙන් website එකක් open කරාම, ඒ website එකට අදාල tab එකේ බලාගන්න හම්බෙන නමත් මේක තමා.

![html title in tab title](image-26.png)

ඉතින් `<head>` tag එක close කරාට පස්සෙ අපිට බලාගන්න පුලුවන් `<body>` tag එක. මේකෙ තමා අපේ website එකේ end user ට පේන දේවල් ටික දාන්නේ. ඇත්තටම website එක ජීවත් වෙන්නෙ මේ කොටසේ. මේ `<body>` tag එක ඇතුලේ අපි එක එක tags දාලා අපේ website එක හදනවා. මෙතනදි අපි සරලම විදිහට `<h1>` tag එකක් දැම්මා. ඔයාට පුලුවන් `<h1>`,`<h2>`,`<h3>` tags ටිකක් දාල, content එක විදිහට ඔයා කැමති text ටිකක් type කරන්න. ඉතින් අපි ඉස්සරහට තව ගොඩක් tags ඉගෙන ගන්නවා, ඒවා ඔක්කොම මේ body tag එකේ තමා දාන්නෙ.

```html
<body>
    <h1>
        Hello World
    </h1>
    <h2>
        I am Malindu
    </h2>
    <h3>
        ඕනේ නම් සිංහලෙන් දාන්නත් පුලුවන්.
    </h3>
</body>
```
ඉතින් මේ විදිහට අපි අපේ HTML file එකේ codes ලියලා, ඒක save කරන්න ඕනේ. එහෙම save කරාට පස්සෙ ඔයා web browser එකේ ඔයා ඉස්සෙල්ල open කරපු site එක දිහා බැලුවට මුකුත් වෙනස් වෙලා කියලා පේන්නේ නැති වෙයි. ඒකට හේතුව එක සැරයක් website එක load කරාට පස්සේ ඒ load වෙච්ච version එකත් එක්ක තමා browser එක වැඩ කරන්නේ. අපිට අලුත්ම version එක ගන්න ඕනේ නම්, අපි page එක refresh කරානම් හරි. ඕක ඉතින් අපි ඕන තරම් කරන දෙයක් නේ. ඒක හින්ද මතක තියාගන්න. මොකක් හරි හේතුවකට ඔයාගේ website එක හරියට පේන්නෙ නැතිව ගියොත්, page එක refresh කරන්න. මේක ගොඩක් වෙලාවට කරන්න අමතක වෙන දෙයක්. පිස්සු හැදෙනවා, මොකද්ද අවුල කියලා හිතාගන්න බැරිව ඉද්දී. අවසානෙ බැලුවම අපේ අවුලක් නෑ, අපි page එක refresh කරලා නෑ.

![reload the page](image-27.png)
![h1,h2,h3 demo](image-28.png)

ඔයාට පේනවා ඇති `<h1>`,`<h2>`,`<h3>` විදිහට දාද්දී browser එකෙන් ඒ ටික size අඩු වෙන විදිහට display කරලා. ඔව් නේ. ඒක නේ අපිට ඕනේ. මේ තියෙන්නේ page එකේ තියෙන headings 3ක්, පලවෙනි එක ප්‍රධාන heading එක, ඊලඟ එක අරකේ subheading එකක්, ඊලඟ එක මේකෙ subheading එකක්. සරලයි.

ඔය ටික තමා දැනට කතා කරන්න ඕනේ උනේ. අපි ඉස්සරහට තව දේවල් බලමු. දැනට headings ටිකක් දාන්න ඉගෙන ගන්න. ඔයා අද ලියපු code එක මකල ආයෙ ලියන්න. හැබැයි මේ සැරේ මතකෙන් ලියන්න. මොකද එතකොට ඔයාටම තෙරෙයි අමතක වෙද්දි ඇයි ඒව අමතක වුනේ සහ ඇයි ඒවා එහෙම දාන්නෙ කියලා. ඒ වගේම ඔයාටම තෙරෙයි කොච්චර තාර්කිකද මේ කතාව කියලා. ඒක තමා මේ programming ලෝකෙ තියෙන ලස්සනම දේ. හැමදේම තාර්කිකයි. හැමදේකටම හේතුවක් තියනවා. පිලිවෙලයි.

## Homework 👨‍🏫
මේ ටික කරන්න කලින් browser එකයි VSCode එකයි close කරන්න. අපි fresh විදිහට කරමු, එතකොට හොදට හැමදේම ඔලුවට යනවා.

1. Desktop එකේ හරි ඔයා මේ වැඩ ටික තියාගන්න කැමති folder එක්කට යන්න. ඒකෙ අලුත් folder එකක් හදන්න, `WebDev101` කියලා. මේකේ තමා අපි ඉස්සරහට මේ කෝස් එකේ හැම දෙයක්ම දාන්න යන්නේ. ඒක නිසා ඔයා කැමති පහසු තැනක මේක හදාගන්න. දැන් ඒකෙ අලුත් folder එකක් හදන්න, `Lesson 1 - HTML Basics - Homework` කියලා.
   ![create folder for homework](image-29.png)
2. Startmenu එකෙන් search කරලා VSCode open කරන්න. (කැමති විදිහකට කෝම හරි open කරගන්නයි ඕනෙ)
3. දැන් අලුත් File එකක් හදාගන්න. මතක නැත්තන් ආයෙ පාඩම කියවලා හොයාගන්න.
4. ඒකෙ language එක තෝරගන්න HTML විදිහට. මේක අත්‍යවශ්‍ය නෑ. මේක කරාම අපිට type කරද්දි වචන පාට වෙන නිසා හරියට ලීවද කියල හොයාගත්තහැකි.
5. මුලින්ම Basic HTML Document එකේ structure එක දාගන්න. මතක නැත්තන් කමක් නෑ, උඩ තියනවානේ, එතනින් copy කරගන්න. මතකෙන් ගහන තරමට හොදයි.
6. දැන් ඒකේ website එකේ title එක වෙනස් කරන්න, මේ folder (`Lesson 1 - HTML Basics - Homework`) එකේ නමට.
7. Website එකේ මට බලාගන්න ඕනෙ, headings 6ක්, ජාති 6කින්. ඒවා ලොකුම heading එකේ ඉදලා පොඩිම heading එකට යනකන් තියෙන්න ඕනේ. ඒවගෙ content එක මෙන්න මේ විදිහට තියෙන්න ඕනේ 👇
   - This is the biggest heading of all! It's so big, it's almost as big as my head!
   - This heading is a little smaller than the h1 heading, but it's still pretty big. It's about the size of my ego.
   - This heading is getting smaller, but it's still pretty noticeable. It's about the size of my pet hamster.
   - This heading is getting smaller, but it's still readable. It's about the size of my phone screen.
   - This heading is getting pretty small, but it's still there. It's about the size of my hand.
   - This heading is the smallest of all, but it's still there. It's about the size of my pinky finger.
8. අවසන් output එක මෙන්න මේ වගේ තියෙන්න ඕනේ 👇
![Code output](image-30.png)
9. දැන් code එක අර අපි හදපු folder එකේ save කරන්න. `homework.html` වගේ නමක් දෙන්න.
10. දැන් ඒ folder එකට ගිහින් ඔයා save කරපු file එක web browser එකෙන් open කරලා බලන්න මගේ එක වගේ තියනවද කියලා. මගේ එකේ අකුරු ඔයාගෙ එකට වඩා ලොකු හරි පොඩි හරි වෙන්න පුලුවන්. ඒත් අවසානෙ මගේ වගේ ලොකු එකේ ඉදන් පොඩි වෙවී ගිහින් තියෙන්න ඕනේ.
11. වැඩේ හරි නම්, නැත්තන් වැරදි නම් ඒත් කමක් නෑ, අපේ [Telegram Group](https://t.me/thisismalindu_chat/1011) එකට screenshot එකක් දාන්න. Screenshot ගහන්න දන්නේ නැත්තන්, Google කරලා හොයාගන්න.

අපි ඊළඟ පාඩමේදී HTML ලියද්දි ඔයාට ආපු ප්‍රශ්න විසඳනවා. මෙතනදි මං කතා කරන්න ප්‍රශ්න කීපයක් ලෑස්ති කරන් ඉන්නේ. උදාහරණයක් විදිහට කෙනෙක්ට ප්‍රශ්නයක් එන්න පුලුවන් මේකෙ මං code එක විස්තර කරද්දි මෙහෙම ලීව, හැබැයි සම්පූර්ණ code එක පෙන්නද්දි මෙහෙම ලීවා. ඒ දෙකේ වෙනස මොකද්ද, මොකද්ද හරි එක වගේ. ඔයාටත් ප්‍රශ්න ආවා නම් අනිවාරෙන් දාන්න comments section එකේ හරි [Telegram Group](https://t.me/thisismalindu_chat/1011) එකේ හරි. ඊලඟ පාඩමේදී ඔයාගෙ ප්‍රශ්න වලට උත්තර හම්බෙයි. Homework කරලා ලෑස්ති වෙලා ඉන්න. මං දුන්න ඒවට අමතරව තව දේවල් කරන්න try එකක් දෙන්න, ගෙදර අයට එහෙම පෙන්නන්න.

අපි එහෙනම් ඊළඟ පාඩමෙන් හම්බෙමු.




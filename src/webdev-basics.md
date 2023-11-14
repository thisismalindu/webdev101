# Web Development Basics

[Watch the Related Video 👇 ![Web Development Basics](https://i3.ytimg.com/vi/pUCkqkZBFAU/maxresdefault.jpg)](https://youtu.be/pUCkqkZBFAU)

## What is HTML? 📄
HTML = **H**yper-**T**ext **M**arkup **L**anguage

## What is CSS? 🎨
CSS = **C**ascading-**S**tyle**s**heets

## What is JS? 🏃‍♂️
JS = **J**ava**s**cript

## හරි ඒනම් දැන් තේරුනා නේද? 😏
නෑ නෑ, එහෙම බෑ 🙃

ඔන්න අහගන්න.

**Website** එකක් ගොඩක් වෙලාවට කොටස් 3කට කඩන්න පුලුවන්.

1. Website එකේ ව්‍යුහය
2. Website එකේ පෙනුම
3. Website එකේ ක්‍රියාකාරීත්වය

ඔව්. ඔය 3 තමා website එක්ක තියෙන්නේ. ඔය තුන සපුරන්න තමා කලින් දවසෙ කියපු languages 3 තියෙන්නේ.

1. HTML = ව්‍යුහය (structure)
2. CSS = පෙනුම (appearance)
3. JS = ක්‍රියාකාරිත්වය (functionality)

ඒ තරම් සරලයි මේ කතාව.

## මොනවද මේ ව්‍යුහය, පෙනුම, ක්‍රියාකරීත්වය කියන්නෙ? 🦴
මුලින්ම ඔයාව හිතේ මවාගන්න. ඇස් පියාගන්න ඕනේ නම් එහෙම. දැන් ඔයාගෙ මස් එහෙම අයින් කරලා ඇට සැකිල්ල මවාගන්න. ඔන්න ඕක නේද ඔයාගෙ ව්‍යුහය කියන්නේ. ඔව් ව්‍යුහය කියන්නෙ සැකිල්ලට. අන්න හරි, ඕක තමා HTML කියන්නේ.

දැන් ආපහු අර මස් අරව මෙව්ව දාලා ලස්සන කරල ගන්නකො සැකිල්ල. අන්න හරි. ඕක තමා CSS වලින් කරන්නේ.

ඔයාට කරන්න පුලුවන් දේවල් මොනවද? දුවන්න, කන්න බොන්න, ඉගෙන ගන්න, ලියන්න. මේවා තමා ඔයාගේ functionalities එහෙමත් නැත්තන් ඔයාට කරන්න පුලුවන් ක්‍රියාකාරකම්. අන්න ඒ වගේ තමා JS.

HTML වලින් website එකේ සැකිල්ල හදලා දෙනවා. website එකේ අන්තර්ගත වෙන්න ඕනේ දත්ත හා තොරතුරු මොනවද කියන එක තමා මේකෙන් කියන්නේ. ඔයාට මොකක් හරි වචනයක්, රූපයක් website එකේ පෙන්නන්න ඕනේ නම් අන්න ඒක HTML වලින් තමා ලියලා පෙන්නන්නේ.

උදාහරණයක් විදිහට, අපිට website එකේ පින්තූරයක් පෙන්නන්න ඕනේ නම් අපි ඒක කරන්නෙ මෙහෙම 👇

```HTML
<img src="dog.jpg">
```
මේකේ img කියන්නෙ image එකක් දාන්න කියන එක. image එක කොහෙද තියෙන්නෙ කියන එක තමා src="dog.jpg" කියන එකෙන් කියන්නේ. පේනවනේ හරිම සරලයි. මේ අනික් සංකේත ටික දැනට අමතක කරල normal විදිහට කියවන්න උත්සහ කරන්න. එහෙම තමා programmers ලා codes කියවන්නෙත්.

මේ code එකෙ result එක ඔන්න තියනවා 👇

![Dog](image-16.png)

දැන් ඔය රූපේ මට ලොකු කරන්න, කළු සුදු කරන්න, වටේ outline එකක් දාන්න, රවුමක් කරන්න වගේ දේවල් කරනවා නම් ඒක කරන්නෙ CSS වලින්. මොකද මේ හැමදේම රූපේ පෙනුම සම්බන්ධ දේවල්.

ඔන්න මන් රූපේ පෙනුම වෙනස් කරල තියනවා එක එක දේවල් කරලා 👇

```css
width:300px; 
```
(Original පින්තූරෙ 128px)

<img src="./image-16.png" style="width:300px;">


```css
filter:grayscale(100%);
```
<img src="./image-16.png" style="filter:grayscale(100%);">

```css
border:solid 10px red;
```
<img src="./image-16.png" style="border:solid 10px red;">

```css
border-radius:50%;
```
<img src="./image-16.png" style="border-radius:50%;">


```css
filter:blur(5px);
```

<img src="./image-16.png" style="filter:blur(5px);">

දැන් පේනවා නේ CSS කොච්චර සුපිරි ද කියලා.

දැන් ඔය රූපේ click කරාම බුරන සද්දයක් දාන්න, නැත්තන් ගෙදරටම බල්ලෙක් deliver වෙන්න වගේ හදන්න ඕනේ නම් ඒ වගේ දේවල් කරන්නෙ JS වලින්. මොකද ඒවා website එකේ ක්‍රියාකාරකම්.

මේ බල්ලව click කරලා බලන්නකෝ බුරයිද කියලා 👇

<img src="./image-16.png" class="bark" onclick="playAudio()">
<script>
    function playAudio(){const audio = new Audio("bark.mp3");
        const image = document.querySelector(".bark");
        image.addEventListener("click", () => {
            audio.play();
        });
    }
</script>

ඔන්න තියනවා බුරන්න use කරපු code එක 👇

```js
const audio = new Audio("bark.mp3");

const image = document.querySelector(".bark");
image.addEventListener("click", () => {
  audio.play();
});
```

ආයෙත් කියනවා, මේ කෝඩ් එක අකුරෙන් අකුර තේරුන් ගන්න යන්න එපා, එහෙම කරන්න ඔයාට දැන්ම බෑ. මට කියන්න තියෙන්නේ **JUST FEEL IT **කියලා. අපි උඩින් පල්ලෙන් මේක තේරුන් ගත්තොත්, අපි `bark.mp3 `කියලා file එකක් code එකට ගෙනල්ලා ඒකට `audio` කියලා නම දෙනවා. ඊට පස්සෙ අපි `document` එකෙන් අර පින්තූරෙ හොයාගෙන ඒක උඩ `click` කරාම අර `audio` එක `play` කරන්න කියනවා. සරලයි. අනික් විකාර symbols අමතක කරලා දාන්න. මේ හැමදේම හොදට ගැඹුරට කියලා දෙන්නම් ඉස්සරහට.

ඉතින් දැන් ඔයාට තේරෙනවා ඇති මොකද්ද ව්‍යුහය, පෙනුම සහ ක්‍රියාකාරිත්වය කියන්නේ කියලා.

## HTML + CSS + JS = Website 🎉
ඉතින් ඔය කියපු ජාති 3 එකතු උනාම තමා website එකක් හැදෙන්නේ. ඇත්තම කීවොත් ඉතිම් website එක්කට JS අත්‍යවශ්‍ය නෑ. මොකද සමහර websites තියෙනවා නිකන්ම විස්තර ටිකක් පෙන්නන්න විතරක්ම හදපු. ඒ වගේ එකක් තමා [මේ තියෙන්නේ](https://thisismalindu.com/html-css-only.html) (මට හොඳ උදාහරණයක් හොයාගන්න බැරි උනා, ඒක නිසා මන් ටක්ගාල එකක් හදලා දැම්මා 😂). එක අතකින් බැලුවම මේක website එක්කට වඩා flyer එකක්, leaflet එකක් වගේ තමා.

කොහොම හරි දැන් නම් ඔයාට ලොකු අවබෝධයක් ඇති කොහොමද මේ websites හැදෙන්නේ කියලා. අපි ඊලඟ පාඩමෙන් HTML ඉගෙන ගන්න පටන්ගමු. දැනට මේ කියපු දේවල් හොඳට දෙතුන් වතාවක් කියවලා හරි තේරුන් ගන්න.

අදත් Homework නෑ. පොඩ්ඩක් computer එක use කරන්න, websites වලට ගියාම ඒවා දිහා වෙනස් කෝණයකින් බලන්න. Website එක හැදෙන්න ඇත්තේ කොහොමද කියලා තේරුන් ගන්න බලන්න. YouTube එකේ video එකක් බලනකොට ඔයාට දකින්න අත්විදින්න ලැබෙන දේවල් HTML, CSS, JS මොන ගණයටද අයත් වෙන්නේ කියලා කල්පනා කරලා බලන්න. ඔයාට මෙච්චර කල් නොපෙනුනු ලස්සන දේවල් පෙනෙයි.

ඊළඟ පාඩමෙන් හම්බෙමු.
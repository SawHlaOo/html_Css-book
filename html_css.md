# HTML နှင့် CSS အခြေခံလမ်းညွှန်စာအုပ်

Beginner to Intermediate • မြန်မာဘာသာဖြင့် • လက်တွေ့ကုဒ်နမူနာများနှင့် လေ့ကျင့်ခန်းများ

ဒီစာအုပ်ကို Programming ကို အခုမှ စတင်လေ့လာသူတွေအတွက် ရေးသားထားပါတယ်။ HTML နဲ့ CSS ကို အခြေခံကနေ စတင်ပြီး ကိုယ်ပိုင် Website တစ်ခု တည်ဆောက်နိုင်တဲ့အထိ အဆင့်ဆင့် လေ့လာသွားပါမယ်။

ကုဒ်ထဲက HTML tag၊ CSS property နဲ့ programming ဆိုင်ရာ ဝေါဟာရတွေကို မူရင်းအင်္ဂလိပ်အတိုင်း ထားရှိပြီး မြန်မာလို နားလည်လွယ်အောင် ရှင်းပြထားပါတယ်။

## မာတိကာ

1. Website နှင့် HTML/CSS မိတ်ဆက်
2. လိုအပ်သော Tools များနှင့် ပထမဆုံး HTML ဖိုင်
3. HTML Document ဖွဲ့စည်းပုံ
4. Headings၊ Paragraphs နှင့် Text Formatting
5. Links နှင့် Images
6. Lists နှင့် Tables
7. Forms နှင့် Input များ
8. Semantic HTML နှင့် Accessibility
9. CSS မိတ်ဆက်နှင့် CSS ချိတ်ဆက်နည်း
10. CSS Selectors၊ Colors နှင့် Typography
11. Box Model၊ Margin နှင့် Padding
12. Borders၊ Backgrounds နှင့် Shadows
13. Display နှင့် Flexbox
14. CSS Grid နှင့် Position
15. Responsive Design
16. Pseudo-classes နှင့် Transitions
17. ကိုယ်ရေးမိတ်ဆက် Website တည်ဆောက်ခြင်း
18. အမှားရှာဖွေခြင်းနှင့် ကုဒ်ရေးသားမှုဆိုင်ရာ အလေ့အကျင့်ကောင်းများ
19. လေ့ကျင့်ခန်းများ
20. နောက်ထပ်လေ့လာရန် လမ်းညွှန်

# အခန်း ၁ — Website နှင့် HTML/CSS မိတ်ဆက်

## ၁.၁ Website ဆိုတာဘာလဲ။

Website ဆိုတာ Internet ပေါ်တွင် Browser အသုံးပြုပြီး ဝင်ရောက်ကြည့်ရှုနိုင်တဲ့ Web Pages များကို စုစည်းထားခြင်း ဖြစ်ပါတယ်။

ဥပမာ -

- Online Shopping Website
- Education Website
- News Website
- Personal Portfolio Website
- Social Media Website

Website တစ်ခုကို တည်ဆောက်ရာမှာ နည်းပညာအမျိုးမျိုးကို အသုံးပြုနိုင်ပါတယ်။ စတင်လေ့လာသူတစ်ယောက်အတွက် အရေးကြီးဆုံး အခြေခံနည်းပညာနှစ်ခုကတော့ HTML နဲ့ CSS ဖြစ်ပါတယ်။

## ၁.၂ HTML ဆိုတာဘာလဲ။

HTML ရဲ့ အရှည်ကောက်က HyperText Markup Language ဖြစ်ပါတယ်။

HTML ကို Website ရဲ့ ဖွဲ့စည်းပုံနဲ့ အကြောင်းအရာတွေ သတ်မှတ်ဖို့ အသုံးပြုပါတယ်။

ဥပမာ -

- ခေါင်းစဉ်များ
- စာပိုဒ်များ
- ပုံများ
- လင့်ခ်များ
- စာရင်းများ
- Form များ

ပထမဆုံး HTML နမူနာကို ကြည့်ကြည့်ရအောင်။

```
<h1>မင်္ဂလာပါ</h1>

<p>HTML ကို စတင်လေ့လာနေပါတယ်။</p>
```

ဒီကုဒ်မှာ -

- `<h1>` က အဓိကခေါင်းစဉ်ကို ဖော်ပြပါတယ်။
- `<p>` က စာပိုဒ်တစ်ခုကို ဖော်ပြပါတယ်။

## ၁.၃ CSS ဆိုတာဘာလဲ။

CSS ရဲ့ အရှည်ကောက်က Cascading Style Sheets ဖြစ်ပါတယ်။

HTML က Website ရဲ့ ဖွဲ့စည်းပုံကို တည်ဆောက်ပေးပြီး CSS က အဲဒီအကြောင်းအရာတွေကို အလှဆင်ပေးပါတယ်။

ဥပမာ -

```
h1 {
    color: blue;
    font-size: 36px;
}

p {
    color: gray;
    font-size: 18px;
}
```

ဒီကုဒ်က ခေါင်းစဉ်ကို အပြာရောင်၊ စာလုံးအရွယ်အစား 36px သတ်မှတ်ပေးပြီး စာပိုဒ်ကို မီးခိုးရောင်၊ 18px သတ်မှတ်ပေးပါတယ်။

## ၁.၄ HTML၊ CSS နှင့် JavaScript ကွာခြားချက်

HTML — Structure

Website မှာ ဘာအကြောင်းအရာတွေ ပါဝင်မလဲဆိုတာ သတ်မှတ်ပေးပါတယ်။

CSS — Design

အရောင်၊ အရွယ်အစား၊ အကွာအဝေးနဲ့ Layout တွေကို သတ်မှတ်ပေးပါတယ်။

JavaScript — Interactivity

Button နှိပ်တဲ့အခါ လုပ်ဆောင်မှုတွေ ဖြစ်ပေါ်စေခြင်း၊ အချက်အလက်ပြောင်းလဲခြင်းတို့ကို လုပ်ဆောင်ပေးပါတယ်။

## ၁.၅ HTML နှင့် CSS ကို ဘာကြောင့် လေ့လာသင့်သလဲ။

- ကိုယ်ပိုင် Website များ ဖန်တီးနိုင်ပါတယ်။
- Frontend Development ကို ဆက်လက်လေ့လာနိုင်ပါတယ်။
- React၊ Next.js စတဲ့ Framework တွေကို နားလည်ဖို့ အခြေခံကောင်း ရရှိပါတယ်။
- Portfolio Website တည်ဆောက်ပြီး ကိုယ့်ရဲ့ Project တွေကို ပြသနိုင်ပါတယ်။
- Web Developer အဖြစ် အလုပ်အကိုင်အခွင့်အလမ်းတွေကို စတင်ပြင်ဆင်နိုင်ပါတယ်။

# အခန်း ၂ — လိုအပ်သော Tools များနှင့် ပထမဆုံး HTML ဖိုင်

## ၂.၁ ဘာတွေ လိုအပ်သလဲ။

HTML နဲ့ CSS ကို စတင်လေ့လာဖို့ အထူးစျေးကြီးတဲ့ Computer သို့မဟုတ် Software မလိုအပ်ပါဘူး။

လိုအပ်တာတွေကတော့ -

- Computer သို့မဟုတ် Laptop
- Web Browser — Chrome၊ Edge သို့မဟုတ် Firefox
- Code Editor — Visual Studio Code (VS Code)
- HTML နဲ့ CSS ရေးသားလေ့ကျင့်ဖို့ Folder တစ်ခု

## ၂.၂ Project Folder ဖန်တီးခြင်း

ပထမဆုံး `my-website` ဆိုတဲ့ Folder တစ်ခု ဖန်တီးပါ။

VS Code ကို ဖွင့်ပြီး အဲဒီ Folder ကို Open Folder နဲ့ ဖွင့်ပါ။

ပြီးရင် `index.html` ဆိုတဲ့ ဖိုင်အသစ်တစ်ခု ဖန်တီးပါ။

Project ဖိုင်တွေကို ဒီလို စီစဉ်ထားနိုင်ပါတယ်။

```
my-website/
├── index.html
├── style.css
└── images/
    └── profile.jpg
```

- `index.html` — Website ရဲ့ HTML ဖိုင်။
- `style.css` — Website ရဲ့ CSS ဖိုင်။
- `images/` — ပုံတွေ သိမ်းထားဖို့ Folder။

## ၂.၃ ပထမဆုံး HTML Code

`index.html` ထဲမှာ အောက်ပါကုဒ်ကို ရေးပါ။

```
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>ကျွန်ုပ်၏ Website</title>
</head>
<body>
    <h1>မင်္ဂလာပါ။</h1>

    <p>ဒါက ကျွန်ုပ်ရဲ့ ပထမဆုံး Website ဖြစ်ပါတယ်။</p>
</body>
</html>
```

### Code တစ်ကြောင်းချင်း ရှင်းပြချက်

`<!DOCTYPE html>` — HTML5 document ဖြစ်ကြောင်း Browser ကို ပြောပြပါတယ်။

`<html lang="my">` — HTML document တစ်ခုလုံးကို စတင်ဖော်ပြပြီး အဓိကဘာသာစကားကို မြန်မာဘာသာအဖြစ် သတ်မှတ်ပါတယ်။

`<head>` — Website အကြောင်း Metadata နဲ့ Browser Tab မှာ ပေါ်မယ့် Title တို့ကို ထည့်သွင်းတဲ့နေရာ ဖြစ်ပါတယ်။

`<meta charset="UTF-8">` — မြန်မာစာအပါအဝင် Unicode စာသားတွေကို မှန်ကန်စွာ ဖတ်ရှုနိုင်ဖို့ သတ်မှတ်ပေးပါတယ်။

`<meta name="viewport" ...>` — Mobile ဖုန်းတွေရဲ့ မျက်နှာပြင်အရွယ်အစားနဲ့ ကိုက်ညီအောင် ပြသနိုင်ဖို့ အရေးကြီးပါတယ်။

`<title>` — Browser Tab ပေါ်မှာ ပေါ်လာမယ့် အမည်ဖြစ်ပါတယ်။

`<body>` — အသုံးပြုသူ မြင်တွေ့ရမယ့် အဓိကအကြောင်းအရာတွေကို ထည့်သွင်းတဲ့နေရာ ဖြစ်ပါတယ်။

## ၂.၄ Browser မှာ ဖွင့်ကြည့်ခြင်း

1. `Ctrl + S` နှိပ်ပြီး ဖိုင်ကို သိမ်းပါ။
2. `index.html` ဖိုင်ကို ရှာပါ။
3. ဖိုင်ကို Double-click နှိပ်ပြီး Browser နဲ့ ဖွင့်ပါ။
4. ကုဒ်ပြင်ပြီးတိုင်း သိမ်းဆည်းကာ Browser ကို Refresh လုပ်ပါ။

မှတ်ချက်။ မြန်မာစာ မမှန်ကန်ပါက ဖိုင်ထဲမှာ UTF-8 သတ်မှတ်ထားခြင်း၊ Unicode စာသားအသုံးပြုထားခြင်းနဲ့ စက်ထဲရှိ မြန်မာဖောင့်တို့ကို စစ်ဆေးပါ။

### လေ့ကျင့်ခန်း

- Website Title ကို မိမိအမည်ဖြင့် ပြောင်းပါ။
- `h1` ခေါင်းစဉ်တစ်ခု ထည့်ပါ။
- ကိုယ့်အကြောင်း စာပိုဒ်နှစ်ပိုဒ် ရေးပါ။

# အခန်း ၃ — HTML Document ဖွဲ့စည်းပုံ

## ၃.၁ Tag ဆိုတာဘာလဲ။

HTML Tag ဆိုတာ Browser ကို အကြောင်းအရာတစ်ခုရဲ့ အမျိုးအစားနဲ့ ဖွဲ့စည်းပုံကို ဖော်ပြပေးတဲ့ သတ်မှတ်ချက် ဖြစ်ပါတယ်။

ဥပမာ -

```
<p>ဒါက စာပိုဒ်တစ်ခုပါ။</p>
```

ဒီမှာ -

- `<p>` — Opening Tag
- `ဒါက စာပိုဒ်တစ်ခုပါ။` — Content
- `</p>` — Closing Tag

ဒီလို Tag နဲ့ Content ပေါင်းစပ်ထားတဲ့ အစိတ်အပိုင်းကို HTML Element လို့ ခေါ်ပါတယ်။

## ၃.၂ Attributes ဆိုတာဘာလဲ။

Attribute ဆိုတာ HTML Element တစ်ခုအကြောင်း ထပ်ဆောင်းအချက်အလက် ပေးတဲ့အရာ ဖြစ်ပါတယ်။

```
<a href="https://developer.mozilla.org/">
    HTML လေ့လာရန်
</a>
```

ဒီဥပမာမှာ `href` က Attribute ဖြစ်ပြီး URL က သူ့ရဲ့ Value ဖြစ်ပါတယ်။

နောက်ထပ်ဥပမာ -

```
<img
    src="images/profile.jpg"
    alt="ကျွန်ုပ်၏ ကိုယ်ရေးပုံ"
>
```

- `src` — ပုံဖိုင်ရဲ့ လမ်းကြောင်း။
- `alt` — ပုံအကြောင်း ဖော်ပြတဲ့ စာသား။

## ၃.၃ HTML Element တွေကို မှန်ကန်စွာ အစီအစဉ်ချခြင်း

HTML Element တွေကို တစ်ခုအတွင်း တစ်ခု ထည့်သွင်းနိုင်ပါတယ်။ ဒီနည်းလမ်းကို Nesting လို့ ခေါ်ပါတယ်။

မှန်ကန်တဲ့ပုံစံ -

```
<div>
    <h2>HTML သင်ခန်းစာ</h2>

    <p>
        HTML ကို <strong>လက်တွေ့</strong> လေ့လာကြမယ်။
    </p>
</div>
```

မှားယွင်းတဲ့ပုံစံ -

```
<p>
    <strong>မင်္ဂလာပါ။
</p>
</strong>
```

အဖွင့်နဲ့ အပိတ် Tag တွေကို မှန်ကန်စွာ တွဲဖက်အသုံးပြုဖို့ လိုအပ်ပါတယ်။

## ၃.၄ အပိတ် Tag မလိုအပ်သော Element များ

HTML Element အားလုံးမှာ Closing Tag မလိုအပ်ပါဘူး။

ဥပမာ -

```
<img src="photo.jpg" alt="ဓာတ်ပုံ">

<br>

<hr>

<meta charset="UTF-8">
```

`img`၊ `br`၊ `hr` နဲ့ `meta` တို့ဟာ ပုံမှန်အားဖြင့် Closing Tag မလိုအပ်တဲ့ Element တွေ ဖြစ်ပါတယ်။

# အခန်း ၄ — Headings၊ Paragraphs နှင့် Text Formatting

## ၄.၁ Headings

HTML မှာ Heading အဆင့် ခြောက်ဆင့် ရှိပါတယ်။

```
<h1>အဓိကခေါင်းစဉ်</h1>

<h2>ခေါင်းစဉ်ခွဲ</h2>

<h3>ခေါင်းစဉ်ခွဲ၏ အောက်အဆင့်</h3>

<h4>Heading 4</h4>

<h5>Heading 5</h5>

<h6>Heading 6</h6>
```

`h1` ဟာ အဓိကခေါင်းစဉ်ဖြစ်ပြီး `h6` က အငယ်ဆုံး Heading အဆင့် ဖြစ်ပါတယ်။

Heading တွေကို စာလုံးအရွယ်အစားအတွက်သာ မသုံးဘဲ အကြောင်းအရာရဲ့ ဖွဲ့စည်းပုံနဲ့ ကိုက်ညီအောင် အသုံးပြုသင့်ပါတယ်။

## ၄.၂ Paragraph

စာပိုဒ်တစ်ခု ရေးချင်ရင် `<p>` ကို အသုံးပြုပါ။

```
<p>
    HTML သည် Website တည်ဆောက်ရာတွင်
    အခြေခံအကျဆုံး နည်းပညာတစ်ခု ဖြစ်သည်။
</p>

<p>
    CSS ကို အသုံးပြု၍ Website ကို
    လှပစွာ ဒီဇိုင်းဆွဲနိုင်သည်။
</p>
```

## ၄.၃ Text Formatting

| Tag        | အသုံးပြုပုံ                            |
| ---------- | -------------------------------------- |
| `<strong>` | အရေးကြီးသော စာသား                      |
| `<em>`     | အလေးပေးသော စာသား                       |
| `<mark>`   | အမှတ်အသားပြုထားသော စာသား               |
| `<small>`  | စာလုံးသေးသော စာသား                     |
| `<del>`    | ဖယ်ရှားထားသော စာသား                    |
| `<br>`     | စာကြောင်းအသစ်သို့ ဆင်းခြင်း            |
| `<hr>`     | အကြောင်းအရာအပိုင်းများကို ခွဲခြားခြင်း |

ဥပမာ -

```
<p>
    <strong>သတိပြုရန်။</strong>
    ကုဒ်ကို သိမ်းဆည်းဖို့ မမေ့ပါနှင့်။
</p>

<p>
    HTML သည် <em>အရေးကြီးသော</em> အခြေခံဖြစ်သည်။
</p>

<p>
    မူလဈေးနှုန်း:
    <del>50,000 ကျပ်</del>
</p>

<hr>
```

# အခန်း ၅ — Links နှင့် Images

## ၅.၁ Links ဖန်တီးခြင်း

Website တစ်ခုမှ အခြား Website တစ်ခုသို့ သွားရန် သို့မဟုတ် ကိုယ့် Website ရဲ့ အခြားစာမျက်နှာတစ်ခုသို့ သွားရန် `<a>` Element ကို အသုံးပြုပါတယ်။

```
<a href="https://www.google.com/">
    Google သို့ သွားရန်
</a>
```

### ကိုယ့် Website အတွင်းရှိ စာမျက်နှာများသို့ ချိတ်ဆက်ခြင်း

```
<a href="about.html">ကျွန်ုပ်အကြောင်း</a>

<a href="contact.html">ဆက်သွယ်ရန်</a>
```

### Link ကို Tab အသစ်မှာ ဖွင့်ခြင်း

```
<a
    href="https://developer.mozilla.org/"
    target="_blank"
    rel="noopener noreferrer"
>
    MDN ကို လေ့လာရန်
</a>
```

`target="_blank"` က Link ကို Tab အသစ်မှာ ဖွင့်ပေးပါတယ်။

## ၅.၂ Images ထည့်ခြင်း

```
<img
    src="images/profile.jpg"
    alt="အပြင်ဘက်တွင် ရိုက်ထားသော ကိုယ်ရေးပုံ"
    width="300"
>
```

ပုံအတွက် အရေးကြီးတဲ့ Attribute တွေက -

- `src` — ပုံဖိုင်ရဲ့ လမ်းကြောင်း။
- `alt` — ပုံကို အဓိပ္ပာယ်ဖော်ပြပေးတဲ့ စာသား။
- `width` — ပုံရဲ့ အကျယ်။
- `height` — ပုံရဲ့ အမြင့်။

CSS ဖြင့် ပုံအရွယ်အစားကို Responsive ဖြစ်အောင်လည်း ပြုလုပ်နိုင်ပါတယ်။

```
img {
    max-width: 100%;
    height: auto;
}
```

ဒီနည်းလမ်းက ပုံကို မိမိရဲ့ Container ထက် ကျော်လွန်မသွားစေဘဲ အချိုးအစားမပျက်အောင် ကူညီပေးပါတယ်။

# အခန်း ၆ — Lists နှင့် Tables

## ၆.၁ Unordered List

အစဉ်လိုက် နံပါတ်မလိုအပ်တဲ့ စာရင်းအတွက် `<ul>` ကို သုံးပါတယ်။

```
<h2>လေ့လာမည့် ဘာသာရပ်များ</h2>

<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

## ၆.၂ Ordered List

အစဉ်လိုက် နံပါတ်လိုအပ်တဲ့ စာရင်းအတွက် `<ol>` ကို သုံးပါတယ်။

```
<h2>Website တည်ဆောက်ရန် အဆင့်များ</h2>

<ol>
    <li>Project Folder ဖန်တီးပါ။</li>
    <li>HTML ရေးပါ။</li>
    <li>CSS ချိတ်ဆက်ပါ။</li>
    <li>Browser မှာ စမ်းသပ်ပါ။</li>
</ol>
```

## ၆.၃ HTML Table

ဇယားတစ်ခုကို အောက်ပါ Element တွေနဲ့ တည်ဆောက်နိုင်ပါတယ်။

- `<table>` — ဇယားတစ်ခုလုံး။
- `<tr>` — ဇယားတစ်တန်း။
- `<th>` — ခေါင်းစီးဆဲလ်။
- `<td>` — ပုံမှန်အချက်အလက်ဆဲလ်။
- `<thead>` — ခေါင်းစီးအပိုင်း။
- `<tbody>` — အဓိကအချက်အလက်အပိုင်း။
- `<caption>` — ဇယားခေါင်းစဉ်။

```
<table>
    <caption>သင်တန်းအချိန်ဇယား</caption>

    <thead>
        <tr>
            <th>နေ့</th>
            <th>ဘာသာရပ်</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>သောကြာ</td>
            <td>HTML</td>
        </tr>

        <tr>
            <td>စနေ</td>
            <td>CSS</td>
        </tr>
    </tbody>
</table>
```

Table ကို အချက်အလက်တွေ ဇယားပုံစံနဲ့ ဖော်ပြဖို့ အသုံးပြုပါ။ Website ရဲ့ Layout တည်ဆောက်ရာမှာတော့ Flexbox သို့မဟုတ် Grid ကို အသုံးပြုတာ ပိုသင့်တော်ပါတယ်။

# အခန်း ၇ — Forms နှင့် Input များ

## ၇.၁ Form ဆိုတာဘာလဲ။

Form ဆိုတာ အသုံးပြုသူထံမှ အချက်အလက်တွေ ရယူဖို့ အသုံးပြုတဲ့ HTML Element ဖြစ်ပါတယ်။

ဥပမာ -

- Login Form
- Registration Form
- Contact Form
- Search Form
- Feedback Form

## ၇.၂ Input Element

```
<form>
    <label for="username">အသုံးပြုသူအမည်</label>

    <input
        type="text"
        id="username"
        name="username"
        required
    >

    <button type="submit">ပေးပို့ရန်</button>
</form>
```

`input` မှာ အသုံးများတဲ့ Attribute တွေက -

- `type` — ထည့်သွင်းမယ့် အချက်အလက်အမျိုးအစား။
- `id` — Element ကို သီးခြားသတ်မှတ်ပေးခြင်း။
- `name` — Form က ပေးပို့မယ့် အချက်အလက်ရဲ့ အမည်။
- `required` — အချက်အလက် မဖြစ်မနေထည့်ရန် သတ်မှတ်ခြင်း။
- `placeholder` — Input အတွင်း အညွှန်းစာသား ပြသခြင်း။

## ၇.၃ Input အမျိုးအစားများ

```
<input type="text" placeholder="အမည်">

<input type="email" placeholder="အီးမေးလ်">

<input type="password" placeholder="စကားဝှက်">

<input type="number" placeholder="အသက်">

<input type="date">

<input type="checkbox">

<input type="radio">

<input type="file">
```

Input တစ်ခုချင်းစီမှာ သက်ဆိုင်ရာ လုပ်ဆောင်ချက်နဲ့ ရည်ရွယ်ချက် ရှိပါတယ်။

## ၇.၄ ပြည့်စုံသော Registration Form

```
<form action="/register" method="post">

    <label for="name">အမည်</label>
    <input
        type="text"
        id="name"
        name="name"
        required
    >

    <label for="email">အီးမေးလ်</label>
    <input
        type="email"
        id="email"
        name="email"
        required
    >

    <label for="password">စကားဝှက်</label>
    <input
        type="password"
        id="password"
        name="password"
        minlength="8"
        required
    >

    <button type="submit">စာရင်းသွင်းရန်</button>

</form>
```

ဒီ Form မှာ `action="/register"` က အချက်အလက်ပေးပို့မယ့် URL ကို သတ်မှတ်ထားပြီး `method="post"` က HTTP POST method ကို အသုံးပြုထားပါတယ်။

သို့သော် HTML Form တစ်ခုတည်းနဲ့ အသုံးပြုသူအချက်အလက်ကို Database ထဲ အလိုအလျောက် သိမ်းဆည်းပေးမှာ မဟုတ်ပါဘူး။ Server သို့မဟုတ် Backend လိုအပ်ပါတယ်။

## ၇.၅ CSS ဖြင့် Form ကို အလှဆင်ခြင်း

```
form {
    max-width: 420px;
    margin: 30px auto;
    padding: 24px;
    background-color: white;
    border-radius: 12px;
}

label {
    display: block;
    margin-bottom: 6px;
}

input {
    width: 100%;
    padding: 12px;
    margin-bottom: 16px;
    border: 1px solid #cccccc;
    border-radius: 6px;
}

button {
    padding: 12px 20px;
    background-color: #1769AA;
    color: white;
    border: none;
    border-radius: 6px;
    cursor: pointer;
}
```

သတိပြုရန်။ Browser ဘက်မှာ စစ်ဆေးခြင်းတစ်ခုတည်းကို မယုံကြည်ပါနှင့်။ အရေးကြီးတဲ့ အချက်အလက်တွေကို Backend မှာလည်း Validate လုပ်ဖို့ လိုအပ်ပါတယ်။

# အခန်း ၈ — Semantic HTML နှင့် Accessibility

## ၈.၁ Semantic HTML ဆိုတာဘာလဲ။

Semantic HTML ဆိုတာ Element တစ်ခုရဲ့ အဓိပ္ပာယ်နဲ့ ရည်ရွယ်ချက်ကို ရှင်းလင်းစွာ ဖော်ပြပေးတဲ့ HTML ဖြစ်ပါတယ်။

ဥပမာ `div` ကို နေရာတိုင်းမှာ အသုံးပြုမယ့်အစား သက်ဆိုင်ရာ အဓိပ္ပာယ်ရှိတဲ့ Element တွေကို ရွေးချယ်နိုင်ပါတယ်။

| Element   | ရည်ရွယ်ချက်                           |
| --------- | ------------------------------------- |
| `header`  | ခေါင်းစီးနှင့် မိတ်ဆက်အပိုင်း         |
| `nav`     | လမ်းညွှန်လင့်ခ်များ                   |
| `main`    | အဓိကအကြောင်းအရာ                       |
| `section` | အကြောင်းအရာအပိုင်းတစ်ခု               |
| `article` | ကိုယ်ပိုင်အဓိပ္ပာယ်ရှိသော အကြောင်းအရာ |
| `aside`   | ဆက်စပ်အကြောင်းအရာ                     |
| `footer`  | အောက်ခြေအချက်အလက်                     |

## ၈.၂ Semantic Website နမူနာ

```
<header>
    <h1>My Website</h1>

    <nav aria-label="အဓိက လမ်းညွှန်">
        <a href="/">ပင်မစာမျက်နှာ</a>
        <a href="/about.html">ကျွန်ုပ်အကြောင်း</a>
        <a href="/contact.html">ဆက်သွယ်ရန်</a>
    </nav>
</header>

<main>
    <section>
        <h2>ကျွန်ုပ်တို့အကြောင်း</h2>

        <p>ကျွန်ုပ်တို့သည် Web Development ကို လေ့လာနေပါသည်။</p>
    </section>

    <article>
        <h2>HTML အခြေခံ</h2>

        <p>HTML သည် Website တည်ဆောက်ရာတွင် အသုံးပြုသည်။</p>
    </article>
</main>

<footer>
    <p>© 2026 My Website</p>
</footer>
```

## ၈.၃ Accessibility ဆိုတာဘာလဲ။

Accessibility ဆိုတာ လူအမျိုးမျိုး၊ စွမ်းရည်အမျိုးမျိုးရှိတဲ့ အသုံးပြုသူတွေ Website ကို အသုံးပြုနိုင်အောင် ပြုလုပ်ပေးခြင်း ဖြစ်ပါတယ်။

အရေးကြီးတဲ့ အချက်တွေက -

- ပုံတွေမှာ သင့်လျော်တဲ့ `alt` စာသား ထည့်ပါ။
- Form တစ်ခုချင်းစီအတွက် Label ထည့်ပါ။
- Heading တွေကို အစီအစဉ်တကျ အသုံးပြုပါ။
- Keyboard နဲ့ Website ကို အသုံးပြုနိုင်စေပါ။
- စာသားနဲ့ နောက်ခံအရောင်ကြား ဖတ်ရှုရလွယ်ကူတဲ့ ကွာခြားမှုရှိပါစေ။
- Focus ဖြစ်နေတဲ့ Link နဲ့ Button တွေကို မြင်သာစေပါ။

# အခန်း ၉ — CSS မိတ်ဆက်နှင့် CSS ချိတ်ဆက်နည်း

## ၉.၁ CSS Rule ရဲ့ ဖွဲ့စည်းပုံ

```
p {
    color: blue;
    font-size: 18px;
}
```

ဒီကုဒ်မှာ -

- `p` — Selector
- `color` — Property
- `blue` — Value
- `font-size` — Property
- `18px` — Value

CSS Rule တစ်ခုကို ပုံမှန်အားဖြင့် ဒီပုံစံနဲ့ ရေးပါတယ်။

```
selector {
    property: value;
}
```

## ၉.၂ Inline CSS

HTML Element တစ်ခုရဲ့ `style` Attribute အတွင်း CSS ရေးသားခြင်း ဖြစ်ပါတယ်။

```
<h1 style="color: blue;">
    မင်္ဂလာပါ
</h1>
```

ဒီနည်းက Element တစ်ခုအတွက် အလျင်အမြန် စမ်းသပ်ရာမှာ အသုံးဝင်ပေမဲ့ Website ကြီးလာတဲ့အခါ ထိန်းသိမ်းရခက်နိုင်ပါတယ်။

## ၉.၃ Internal CSS

HTML ဖိုင်ထဲက `head` အပိုင်းမှာ `style` Element အသုံးပြုပြီး CSS ရေးခြင်း ဖြစ်ပါတယ်။

```
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">

    <title>Internal CSS</title>

    <style>
        h1 {
            color: darkblue;
        }

        p {
            font-size: 18px;
        }
    </style>
</head>

<body>
    <h1>မင်္ဂလာပါ</h1>

    <p>Internal CSS ကို လေ့လာနေပါတယ်။</p>
</body>
</html>
```

## ၉.၄ External CSS

External CSS ဆိုတာ CSS ကို သီးခြားဖိုင်တစ်ခုအဖြစ် ရေးသားခြင်း ဖြစ်ပါတယ်။

Project Folder -

```
my-website/
├── index.html
└── style.css
```

`index.html` -

```
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>My Website</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <h1>မင်္ဂလာပါ</h1>

    <p>External CSS ကို အသုံးပြုထားပါတယ်။</p>
</body>
</html>
```

`style.css` -

```
h1 {
    color: #1769AA;
    font-size: 36px;
}

p {
    color: #555555;
    font-size: 18px;
}
```

### ဘယ်နည်းလမ်းကို ရွေးချယ်သင့်သလဲ။

ပုံမှန် Website Project တွေအတွက် External CSS ကို ဦးစားပေးအသုံးပြုသင့်ပါတယ်။ HTML နဲ့ CSS ကို သီးခြားထားခြင်းက Code ကို ဖတ်ရှုရလွယ်ကူစေပြီး ပြုပြင်ထိန်းသိမ်းရာမှာလည်း အဆင်ပြေစေပါတယ်။

# အခန်း ၁၀ — CSS Selectors၊ Colors နှင့် Typography

## ၁၀.၁ Element Selector

HTML Element အမျိုးအစားကို တိုက်ရိုက် ရွေးချယ်ပါတယ်။

```
p {
    color: gray;
}

h1 {
    color: navy;
}
```

ဒီ CSS က `p` Element အားလုံးနဲ့ `h1` Element အားလုံးကို သက်ဆိုင်ရာ Style သတ်မှတ်ပေးပါတယ်။

## ၁၀.၂ Class Selector

Class Selector ကို `.` နဲ့ စတင်ရေးသားပါတယ်။

HTML -

```
<p class="description">
    HTML သင်ခန်းစာမှ ကြိုဆိုပါတယ်။
</p>

<p class="description">
    CSS သင်ခန်းစာကို ဆက်လက်လေ့လာပါ။
</p>
```

CSS -

```
.description {
    color: #526174;
    font-size: 18px;
}
```

Class တစ်ခုကို Element အများအပြားမှာ ပြန်လည်အသုံးပြုနိုင်ပါတယ်။

## ၁၀.၃ ID Selector

ID Selector ကို `#` နဲ့ စတင်ရေးသားပါတယ်။

HTML -

```
<h1 id="main-title">ကျွန်ုပ်၏ Website</h1>
```

CSS -

```
#main-title {
    color: darkblue;
    text-align: center;
}
```

ID ကို စာမျက်နှာတစ်ခုအတွင်း Element တစ်ခုကို သီးခြားသတ်မှတ်ဖို့ အသုံးပြုလေ့ရှိပါတယ်။ ပုံမှန် CSS Styling အများစုအတွက် Class ကို ဦးစားပေးသုံးနိုင်ပါတယ်။

## ၁၀.၄ Descendant Selector

Element တစ်ခုအတွင်းရှိ သက်ဆိုင်ရာ Element တွေကို ရွေးချယ်နိုင်ပါတယ်။

```
nav a {
    color: navy;
    text-decoration: none;
}
```

ဒီကုဒ်က `nav` အတွင်းရှိ `a` Element တွေကို ရွေးချယ်ပေးပါတယ်။

## ၁၀.၅ CSS Colors

CSS မှာ အရောင်သတ်မှတ်နိုင်တဲ့ နည်းလမ်းအမျိုးမျိုး ရှိပါတယ်။

```
h1 {
    color: blue;
}

p {
    color: #333333;
}

.card {
    background-color: rgb(240, 245, 250);
}
```

အသုံးများတဲ့ ပုံစံတွေက -

- Named Colors — `blue`, `white`, `black`
- HEX — `#1769AA`
- RGB — `rgb(23, 105, 170)`
- RGBA — `rgba(23, 105, 170, 0.5)`
- HSL — `hsl(205, 76%, 38%)`

Website ဒီဇိုင်းဆွဲရာမှာ အရောင်အနည်းငယ်ကို တသမတ်တည်း သုံးခြင်းက ပိုမိုသပ်ရပ်တဲ့ ပုံစံကို ရရှိစေပါတယ်။

## ၁၀.၆ Typography

Typography ဆိုတာ စာသားရဲ့ ပုံစံ၊ အရွယ်အစားနဲ့ ဖတ်ရှုရလွယ်ကူမှုတို့ကို စီမံသတ်မှတ်ခြင်း ဖြစ်ပါတယ်။

```
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    line-height: 1.7;
    color: #17202D;
}

h1 {
    font-size: 36px;
    font-weight: 700;
}

p {
    text-align: left;
}
```

အသုံးများတဲ့ CSS Properties -

| Property          | ရည်ရွယ်ချက်           |
| ----------------- | --------------------- |
| `font-family`     | ဖောင့်အမျိုးအစား      |
| `font-size`       | စာလုံးအရွယ်အစား       |
| `font-weight`     | စာလုံးအထူ             |
| `line-height`     | စာကြောင်းကြားအကွာအဝေး |
| `text-align`      | စာသားညှိပုံ           |
| `text-decoration` | စာသားအလှဆင်မှု        |
| `letter-spacing`  | စာလုံးကြားအကွာအဝေး    |

မြန်မာစာ Website တွေအတွက် မြန်မာစာကို ကောင်းမွန်စွာ ပြသနိုင်တဲ့ ဖောင့်ကို ရွေးချယ်ပါ။

```
body {
    font-family: "Noto Sans Myanmar", "Myanmar Text", sans-serif;
}
```

သတ်မှတ်ထားတဲ့ ဖောင့်မရှိတဲ့ စက်တွေမှာ Fallback Font ကို အသုံးပြုနိုင်ပါတယ်။

# အခန်း ၁၁ — CSS Box Model၊ Margin နှင့် Padding

## ၁၁.၁ Box Model ဆိုတာဘာလဲ။

HTML Element တစ်ခုစီကို Box တစ်ခုလို စဉ်းစားနိုင်ပါတယ်။

Margin — Element အပြင်ဘက်

Border — အနားသတ်

Padding — အတွင်းအကွာအဝေး

Content

Box Model မှာ အဓိကအပိုင်း လေးခု ပါဝင်ပါတယ်။

1. Content — စာသား၊ ပုံနဲ့ အခြားအကြောင်းအရာ။
2. Padding — Content နဲ့ Border ကြားက အကွာအဝေး။
3. Border — Element ရဲ့ အနားသတ်။
4. Margin — Element အပြင်ဘက်က အကွာအဝေး။

## ၁၁.၂ Padding

```
.card {
    padding: 20px;
}
```

`padding: 20px;` ဆိုရင် Element ရဲ့ အပေါ်၊ ညာ၊ အောက်၊ ဘယ် ဘက်လေးဘက်စလုံးမှာ 20px အတွင်းအကွာအဝေး ရှိလာပါတယ်။

## ၁၁.၃ Margin

```
.card {
    margin: 20px;
}
```

Margin က Element ရဲ့ အပြင်ဘက်အကွာအဝေး ဖြစ်ပါတယ်။

Element တစ်ခုကို အလျားလိုက် အလယ်မှာထားဖို့ -

```
.container {
    max-width: 1100px;
    margin: 0 auto;
}
```

ဒီကုဒ်မှာ `margin: 0 auto;` က အပေါ်နဲ့အောက် Margin ကို 0 သတ်မှတ်ပြီး ဘယ်နဲ့ညာ Margin ကို အလိုအလျောက် ညှိပေးပါတယ်။

## ၁၁.၄ Border

```
.card {
    border: 1px solid #DCE3EC;
}
```

ဒီမှာ -

- `1px` — Border အထူ။
- `solid` — Border ပုံစံ။
- `#DCE3EC` — Border အရောင်။

## ၁၁.၅ Box Sizing

CSS Layout ကို စီမံရာမှာ အောက်ပါ Rule ကို အသုံးပြုလေ့ရှိပါတယ်။

```
*,
*::before,
*::after {
    box-sizing: border-box;
}
```

ဒီနည်းက `width` နဲ့ `height` တွက်ချက်ရာမှာ Padding နဲ့ Border ကို သတ်မှတ်ထားတဲ့ အရွယ်အစားအတွင်း ထည့်တွက်စေပါတယ်။ ထို့ကြောင့် Layout ကို ခန့်မှန်းရ ပိုမိုလွယ်ကူစေပါတယ်။

# အခန်း ၁၂ — Borders၊ Backgrounds နှင့် Shadows

## ၁၂.၁ Border Radius

Element ရဲ့ ထောင့်တွေကို ဝိုင်းစေဖို့ `border-radius` ကို သုံးပါတယ်။

```
.card {
    border-radius: 12px;
}
```

## ၁၂.၂ Background Color

```
body {
    background-color: #F4F7FB;
}

.card {
    background-color: white;
}
```

## ၁၂.၃ Box Shadow

Box Shadow က Element တစ်ခုကို အရိပ်ထည့်ပေးပါတယ်။

```
.card {
    box-shadow: 0 8px 24px rgba(20, 35, 60, 0.08);
}
```

အရိပ်ကို အလွန်ပြင်းထန်စွာ မသုံးဘဲ ဒီဇိုင်းနဲ့ လိုက်ဖက်အောင် သုံးသင့်ပါတယ်။

## ၁၂.၄ Gradient

Gradient ဆိုတာ အရောင်တစ်ရောင်မှ နောက်တစ်ရောင်သို့ ချောမွေ့စွာ ပြောင်းလဲသွားတဲ့ နောက်ခံပုံစံ ဖြစ်ပါတယ်။

```
.hero {
    background: linear-gradient(
        135deg,
        #102A43,
        #1769AA
    );

    color: white;
    padding: 48px 24px;
    border-radius: 16px;
}
```

ဒီလို Gradient ကို Hero Section၊ Banner နဲ့ Card တွေမှာ အသုံးပြုနိုင်ပါတယ်။

## ၁၂.၅ ပြည့်စုံသော Card Design

```
<div class="card">
    <h2>HTML အခြေခံ</h2>

    <p>
        HTML ကို အသုံးပြုပြီး Website ရဲ့
        ဖွဲ့စည်းပုံကို တည်ဆောက်နိုင်ပါတယ်။
    </p>

    <a href="#">သင်ခန်းစာ ဖတ်ရန်</a>
</div>
```

```
.card {
    max-width: 350px;
    padding: 24px;

    background-color: white;
    border: 1px solid #DCE3EC;
    border-radius: 14px;

    box-shadow: 0 8px 24px rgba(20, 35, 60, 0.08);
}

.card h2 {
    color: #1769AA;
}

.card p {
    color: #526174;
    line-height: 1.8;
}

.card a {
    color: #1769AA;
    text-decoration: none;
    font-weight: 700;
}
```

ဒီဥပမာက HTML နဲ့ CSS ကို ပေါင်းစပ်ပြီး ရိုးရှင်းတဲ့ သင်ခန်းစာ Card တစ်ခု တည်ဆောက်ထားတာ ဖြစ်ပါတယ်။

# အခန်း ၁၃ — Display၊ Flexbox နှင့် Layout

## ၁၃.၁ Display Property

`display` က HTML Element တွေကို Browser မှာ ဘယ်လိုပြသရမလဲဆိုတာ သတ်မှတ်ပေးပါတယ်။

အသုံးများတဲ့ Value တွေက -

- `block`
- `inline`
- `inline-block`
- `flex`
- `grid`
- `none`

ဥပမာ -

```
div {
    display: block;
}

span {
    display: inline;
}
```

`block` Element တွေဟာ ပုံမှန်အားဖြင့် လိုအပ်သလောက် အကျယ်ကို ယူပြီး စာကြောင်းအသစ်မှ စတင်ပါတယ်။

`inline` Element တွေကတော့ စာသားနဲ့အတူ တစ်ကြောင်းတည်းမှာ ရှိနေနိုင်ပါတယ်။

## ၁၃.၂ Flexbox ဆိုတာဘာလဲ။

Flexbox က Element တွေကို အလျားလိုက် သို့မဟုတ် ဒေါင်လိုက် စီစဉ်ဖို့ အသုံးပြုတဲ့ CSS Layout နည်းလမ်းတစ်ခု ဖြစ်ပါတယ်။

ဥပမာ Navigation Bar တစ်ခု တည်ဆောက်ကြည့်ရအောင်။

HTML -

```
<header class="navbar">
    <h2 class="logo">My Website</h2>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
</header>
```

CSS -

```
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
    padding: 20px;
}

nav {
    display: flex;
    gap: 16px;
}

nav a {
    text-decoration: none;
}
```

## ၁၃.၃ Flexbox Properties

| Property          | အသုံးပြုပုံ                                        |
| ----------------- | -------------------------------------------------- |
| `display: flex`   | Flex Container ဖန်တီးခြင်း                         |
| `flex-direction`  | Element များ စီစဉ်မည့် ဦးတည်ချက်                   |
| `justify-content` | Main Axis တစ်လျှောက် ချိန်ညှိခြင်း                 |
| `align-items`     | Cross Axis တစ်လျှောက် ချိန်ညှိခြင်း                |
| `gap`             | Element များကြား အကွာအဝေး                          |
| `flex-wrap`       | နေရာမလုံလောက်လျှင် နောက်တစ်ကြောင်းသို့ ဆင်းစေခြင်း |

## ၁၃.၄ Element များကို အလယ်မှာထားခြင်း

```
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 300px;
}
```

ဒီကုဒ်က Flex Container အတွင်းရှိ Element တွေကို အလျားလိုက်နဲ့ ဒေါင်လိုက် အလယ်မှာ ချိန်ညှိပေးပါတယ်။

## ၁၃.၅ Card များကို Flexbox ဖြင့် စီစဉ်ခြင်း

```
<div class="cards">
    <div class="card">HTML</div>
    <div class="card">CSS</div>
    <div class="card">JavaScript</div>
</div>
```

```
.cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    flex: 1 1 220px;
    padding: 24px;
    background-color: white;
    border-radius: 12px;
}
```

`flex-wrap: wrap` ကြောင့် နေရာမလုံလောက်တဲ့အခါ Card တွေက နောက်တစ်ကြောင်းသို့ ဆင်းသွားနိုင်ပါတယ်။

# အခန်း ၁၄ — CSS Grid နှင့် Position

## ၁၄.၁ CSS Grid ဆိုတာဘာလဲ။

CSS Grid ဟာ Row နဲ့ Column နှစ်မျိုးလုံးကို စီမံနိုင်တဲ့ Layout System ဖြစ်ပါတယ်။

Card Grid၊ Product Grid နဲ့ Dashboard Layout တွေ တည်ဆောက်ရာမှာ အသုံးဝင်ပါတယ်။

```
<div class="product-grid">
    <div class="product">Product 1</div>
    <div class="product">Product 2</div>
    <div class="product">Product 3</div>
</div>
```

```
.product-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.product {
    padding: 24px;
    background-color: #EAF4FF;
    border-radius: 12px;
}
```

`grid-template-columns: repeat(3, 1fr);` ဆိုတာ Column သုံးခုကို တူညီတဲ့ အကျယ်နဲ့ ဖန်တီးပေးတာ ဖြစ်ပါတယ်။

## ၁၄.၂ Responsive Grid

Column အရေအတွက်ကို အလိုအလျောက် ချိန်ညှိချင်ရင် -

```
.product-grid {
    display: grid;

    grid-template-columns: repeat(
        auto-fit,
        minmax(220px, 1fr)
    );

    gap: 20px;
}
```

ဒီပုံစံမှာ Browser ရဲ့ ရရှိနိုင်တဲ့ အကျယ်ပေါ်မူတည်ပြီး Card တွေရဲ့ Column အရေအတွက် ပြောင်းလဲနိုင်ပါတယ်။

## ၁၄.၃ Position Property

CSS `position` က Element တွေရဲ့ နေရာချထားပုံကို သတ်မှတ်ပေးပါတယ်။

| Value      | ရှင်းလင်းချက်                                            |
| ---------- | -------------------------------------------------------- |
| `static`   | ပုံမှန် Document Flow                                    |
| `relative` | မူလနေရာကို အခြေခံပြီး နေရာချနိုင်ခြင်း                   |
| `absolute` | အနီးဆုံး Positioned Ancestor ကို အခြေခံခြင်း             |
| `fixed`    | Viewport နဲ့ ဆက်စပ်ပြီး နေရာတည်မြဲခြင်း                  |
| `sticky`   | Scroll လုပ်ရာတွင် သတ်မှတ်ထားသော အနေအထား၌ ကပ်နေနိုင်ခြင်း |

ဥပမာ -

```
<div class="product-card">
    <span class="badge">NEW</span>

    <h2>Product Name</h2>
</div>
```

```
.product-card {
    position: relative;
    padding: 30px;
    background-color: #F4F7FB;
}

.badge {
    position: absolute;
    top: 10px;
    right: 10px;

    background-color: #1769AA;
    color: white;
    padding: 4px 10px;
    border-radius: 6px;
}
```

ဒီဥပမာမှာ `badge` ကို `product-card` ရဲ့ ညာဘက်အပေါ်ထောင့်မှာ ထားပါတယ်။

# အခန်း ၁၅ — Responsive Design

## ၁၅.၁ Responsive Design ဆိုတာဘာလဲ။

Responsive Design ဆိုတာ Computer၊ Tablet နဲ့ Mobile ဖုန်းတွေလို မျက်နှာပြင်အရွယ်အစား မတူညီတဲ့ စက်တွေမှာ Website ကို မှန်ကန်စွာ ပြသနိုင်အောင် ဒီဇိုင်းတည်ဆောက်ခြင်း ဖြစ်ပါတယ်။

Website တစ်ခုကို Desktop မှာပဲ လှပနေအောင် ပြုလုပ်ထားလို့ မလုံလောက်ပါဘူး။ Mobile ဖုန်းမှာလည်း စာသားဖတ်ရှုရလွယ်ကူပြီး Button တွေကို နှိပ်ရလွယ်ကူဖို့ လိုအပ်ပါတယ်။

## ၁၅.၂ Viewport Meta Tag

HTML ရဲ့ `head` အပိုင်းမှာ ဒီကုဒ်ကို ထည့်ပါ။

```
<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
>
```

ဒီသတ်မှတ်ချက်က Mobile Browser တွေမှာ Website ရဲ့ Layout ကို မျက်နှာပြင်အကျယ်နဲ့ ကိုက်ညီစေဖို့ အရေးကြီးပါတယ်။

## ၁၅.၃ Flexible Images

```
img {
    max-width: 100%;
    height: auto;
}
```

ဒီကုဒ်က ပုံကို Container အကျယ်ထက် ကျော်လွန်မသွားစေဘဲ မူလအချိုးအစားကို ထိန်းထားပေးပါတယ်။

## ၁၅.၄ Media Queries

Media Query ကို မျက်နှာပြင်အကျယ် သို့မဟုတ် အခြားအခြေအနေတွေပေါ် မူတည်ပြီး CSS ပြောင်းလဲဖို့ အသုံးပြုပါတယ်။

```
.cards {
    display: grid;
    grid-template-columns: 1fr;
    gap: 16px;
}

@media (min-width: 700px) {
    .cards {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (min-width: 1000px) {
    .cards {
        grid-template-columns: repeat(3, 1fr);
    }
}
```

ဒီဥပမာမှာ -

- ပုံမှန်အားဖြင့် Column တစ်ခု။
- 700px နဲ့အထက်မှာ Column နှစ်ခု။
- 1000px နဲ့အထက်မှာ Column သုံးခု။

ဒါကြောင့် မျက်နှာပြင်အကျယ်အလိုက် Layout ပြောင်းလဲနိုင်ပါတယ်။

## ၁၅.၅ Mobile-First Design

Mobile-First ဆိုတာ Mobile မျက်နှာပြင်အတွက် အရင်ဆုံး CSS ရေးပြီး နောက်ပိုင်းမှာ မျက်နှာပြင်ကြီးတွေအတွက် Layout ကို တိုးချဲ့သတ်မှတ်တဲ့ နည်းလမ်း ဖြစ်ပါတယ်။

```
.container {
    width: min(100% - 32px, 1100px);
    margin-inline: auto;
}

.grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 16px;
}

@media (min-width: 768px) {
    .grid {
        grid-template-columns: repeat(2, 1fr);
    }
}
```

Responsive Design ကို စမ်းသပ်တဲ့အခါ Browser ရဲ့ Developer Tools ကို အသုံးပြုပြီး Mobile၊ Tablet နဲ့ Desktop အရွယ်အစားတွေကို စစ်ဆေးပါ။

# အခန်း ၁၆ — Pseudo-classes နှင့် Transitions

## ၁၆.၁ Hover Effect

အသုံးပြုသူက Mouse Pointer ကို Element ပေါ်တင်တဲ့အခါ ပုံစံပြောင်းစေဖို့ `:hover` ကို အသုံးပြုပါတယ်။

```
<button class="button">စတင်လေ့လာရန်</button>
```

```
.button {
    padding: 12px 20px;
    background-color: #1769AA;
    color: white;
    border: none;
    border-radius: 8px;
    cursor: pointer;
}

.button:hover {
    background-color: #105D9D;
}
```

## ၁၆.၂ Transition

Transition က CSS Property တစ်ခုရဲ့ တန်ဖိုးပြောင်းလဲမှုကို ချောမွေ့စွာ ပြသပေးပါတယ်။

```
.button {
    background-color: #1769AA;
    transition: background-color 0.2s ease;
}

.button:hover {
    background-color: #105D9D;
}
```

## ၁၆.၃ Focus State

Keyboard အသုံးပြုသူတွေ အတွက်လည်း Element တစ်ခုကို ရွေးချယ်ထားကြောင်း မြင်သာစေဖို့ `:focus-visible` ကို အသုံးပြုနိုင်ပါတယ်။

```
.button:focus-visible {
    outline: 3px solid orange;
    outline-offset: 3px;
}
```

Hover Effect တစ်ခုတည်းကိုသာ မမှီခိုပါနဲ့။ Touch Screen နဲ့ Keyboard အသုံးပြုသူတွေအတွက်လည်း Website ကို အသုံးပြုရလွယ်ကူစေဖို့ လိုအပ်ပါတယ်။

# အခန်း ၁၇ — လက်တွေ့ Project: ကိုယ်ရေးမိတ်ဆက် Website တည်ဆောက်ခြင်း

ဒီအခန်းမှာ အရင်သင်ခန်းစာတွေက HTML နဲ့ CSS အခြေခံတွေကို အသုံးပြုပြီး ကိုယ်ပိုင် Portfolio Website တစ်ခု တည်ဆောက်ပါမယ်။

## ၁၇.၁ Project Folder

```
my-portfolio/
├── index.html
└── style.css
```

## ၁၇.၂ HTML Code

`index.html` ဖိုင်ထဲမှာ အောက်ပါကုဒ်ကို ရေးပါ။

```
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>ကျွန်ုပ်၏ Portfolio</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="navbar">
        <a class="logo" href="#">My Portfolio</a>

        <nav aria-label="အဓိက လမ်းညွှန်">
            <a href="#about">မိတ်ဆက်</a>
            <a href="#skills">ကျွမ်းကျင်မှု</a>
            <a href="#contact">ဆက်သွယ်ရန်</a>
        </nav>
    </header>

    <main class="container">
        <section class="hero" id="about">
            <p class="eyebrow">မင်္ဂလာပါ။ ကျွန်ုပ်က</p>

            <h1>Web Developer တစ်ယောက် ဖြစ်လာဖို့ လေ့လာနေပါတယ်။</h1>

            <p>
                HTML နဲ့ CSS ကို အသုံးပြုပြီး
                လှပပြီး အသုံးဝင်တဲ့ Website တွေ
                တည်ဆောက်ဖို့ ကြိုးစားနေပါတယ်။
            </p>

            <a class="button" href="#contact">
                ဆက်သွယ်ရန်
            </a>
        </section>

        <section id="skills">
            <h2>ကျွန်ုပ်၏ ကျွမ်းကျင်မှုများ</h2>

            <div class="skill-grid">
                <article class="card">
                    <h3>HTML</h3>
                    <p>Website ရဲ့ ဖွဲ့စည်းပုံကို တည်ဆောက်ခြင်း။</p>
                </article>

                <article class="card">
                    <h3>CSS</h3>
                    <p>Website ရဲ့ ဒီဇိုင်းနဲ့ Layout ကို ဖန်တီးခြင်း။</p>
                </article>

                <article class="card">
                    <h3>Learning</h3>
                    <p>နေ့စဉ် လေ့လာပြီး Project များ တည်ဆောက်ခြင်း။</p>
                </article>
            </div>
        </section>

        <section class="contact" id="contact">
            <h2>ဆက်သွယ်ရန်</h2>

            <p>
                Email:
                <a href="mailto:hello@example.com">
                    hello@example.com
                </a>
            </p>
        </section>
    </main>

    <footer class="footer">
        <p>© 2026 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
```

## ၁၇.၃ CSS Code

`style.css` ဖိုင်ထဲမှာ အောက်ပါကုဒ်ကို ရေးပါ။

```
*,
*::before,
*::after {
    box-sizing: border-box;
}

:root {
    --primary: #1769AA;
    --dark: #17202D;
    --muted: #586779;
    --background: #F4F7FB;
    --white: #FFFFFF;
    --border: #DCE3EC;
}

body {
    margin: 0;
    font-family: "Noto Sans Myanmar", "Myanmar Text", sans-serif;
    color: var(--dark);
    background-color: var(--background);
    line-height: 1.8;
}

a {
    color: var(--primary);
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;

    padding: 18px max(20px, calc((100% - 1100px) / 2));

    background-color: var(--white);
    border-bottom: 1px solid var(--border);
}

.logo {
    font-weight: 700;
    text-decoration: none;
}

nav {
    display: flex;
    flex-wrap: wrap;
    gap: 16px;
}

nav a {
    text-decoration: none;
}

.container {
    width: min(100% - 32px, 1100px);
    margin: 0 auto;
}

.hero {
    margin: 32px 0;
    padding: clamp(28px, 6vw, 64px);

    color: white;
    background: linear-gradient(135deg, #102A43, #1769AA);
    border-radius: 20px;
}

.hero h1 {
    max-width: 760px;
    font-size: clamp(1.8rem, 4vw, 3.2rem);
    line-height: 1.5;
}

.hero p {
    max-width: 680px;
}

.eyebrow {
    color: #B9DFFF;
}

.button {
    display: inline-block;
    margin-top: 12px;
    padding: 10px 18px;

    color: #102A43;
    background-color: white;

    border-radius: 8px;
    text-decoration: none;
    font-weight: 700;
}

.skill-grid {
    display: grid;
    grid-template-columns: repeat(
        auto-fit,
        minmax(220px, 1fr)
    );
    gap: 18px;
}

.card,
.contact {
    padding: 22px;
    background-color: var(--white);
    border: 1px solid var(--border);
    border-radius: 14px;
}

.card p,
.contact p {
    color: var(--muted);
}

.footer {
    margin-top: 40px;
    padding: 24px 16px;

    text-align: center;
    color: var(--muted);
    background-color: var(--white);
    border-top: 1px solid var(--border);
}

a:focus-visible {
    outline: 3px solid orange;
    outline-offset: 3px;
}

@media (max-width: 650px) {
    .navbar {
        align-items: flex-start;
        flex-direction: column;
    }
}
```

## ၁၇.၄ Project မှာ ဘာတွေ သင်ယူခဲ့သလဲ။

ဒီ Project ထဲမှာ အောက်ပါအချက်တွေကို လက်တွေ့အသုံးပြုထားပါတယ်။

- Semantic HTML — `header`၊ `nav`၊ `main`၊ `section`၊ `article` နှင့် `footer`
- CSS Variables — အရောင်တွေကို ပြန်လည်အသုံးပြုခြင်း
- Flexbox — Navigation Bar တည်ဆောက်ခြင်း
- CSS Grid — Skill Card များ စီစဉ်ခြင်း
- Responsive Design — မျက်နှာပြင်အကျယ်အလိုက် Layout ပြောင်းလဲခြင်း
- Accessibility — Keyboard Focus ကို မြင်သာစေခြင်း

### ကိုယ်တိုင် ပြင်ဆင်ကြည့်ပါ

1. Website ရဲ့ အရောင်တွေကို ပြောင်းပါ။
2. ကိုယ့်ဓာတ်ပုံတစ်ပုံ ထည့်ပါ။
3. Project တွေအတွက် Card သုံးခု ထပ်ထည့်ပါ။
4. ကိုယ့်ရဲ့ အမှန်တကယ် ဆက်သွယ်ရန် အချက်အလက်ကို ထည့်ပါ။
5. Mobile ဖုန်းမှာ Website ကို စမ်းသပ်ပါ။

# အခန်း ၁၈ — အမှားရှာဖွေခြင်းနှင့် Best Practices

## ၁၈.၁ CSS မအလုပ်လုပ်တဲ့အခါ

အများဆုံးတွေ့ရတဲ့ အမှားတွေက -

၁။ CSS File လမ်းကြောင်းမှားခြင်း

```
<link rel="stylesheet" href="style.css">
```

HTML နဲ့ CSS ဖိုင်ဟာ Folder တစ်ခုတည်းမှာ ရှိတယ်ဆိုရင် ဒီလမ်းကြောင်းကို သုံးနိုင်ပါတယ်။

၂။ Class Selector ရေးပုံမှားခြင်း

HTML -

```
<p class="description">Hello World</p>
```

မှန်ကန်သော CSS -

```
.description {
    color: blue;
}
```

Class Selector ရဲ့ ရှေ့မှာ `.` ထည့်ဖို့ မမေ့ပါနဲ့။

၃။ CSS Property ရေးပုံမှားခြင်း

မှားယွင်းသော Code -

```
h1 {
    color blue
}
```

မှန်ကန်သော Code -

```
h1 {
    color: blue;
}
```

Property နဲ့ Value ကြားမှာ `:` ထည့်ပြီး Declaration အဆုံးမှာ `;` သုံးပါ။

## ၁၈.၂ ပုံ မပေါ်တဲ့အခါ

```
<img src="images/profile.jpg" alt="ကိုယ်ရေးပုံ">
```

စစ်ဆေးရန် -

- ပုံဖိုင် တကယ်ရှိသလား။
- Folder အမည် မှန်သလား။
- ဖိုင်အမည်နဲ့ Extension မှန်သလား။
- စာလုံးအကြီးအသေး ကိုက်ညီသလား။
- ပုံရဲ့ Path မှန်သလား။

## ၁၈.၃ Browser Developer Tools

Chrome သို့မဟုတ် Edge မှာ `F12` နှိပ်ပြီး Developer Tools ကို ဖွင့်နိုင်ပါတယ်။

အသုံးဝင်တဲ့ Tab တွေက -

- Elements — HTML ဖွဲ့စည်းပုံကို စစ်ဆေးခြင်း။
- Styles — CSS Rule တွေကို ကြည့်ရှုခြင်းနှင့် စမ်းသပ်ပြင်ဆင်ခြင်း။
- Console — Error Message များကို စစ်ဆေးခြင်း။
- Network — CSS၊ ပုံနဲ့ အခြားဖိုင်တွေ တင်သွင်းရာမှာ ပြဿနာရှိမရှိ စစ်ဆေးခြင်း။

## ၁၈.၄ Professional Code ရေးသားမှု

ကုဒ်ကို အလုပ်အကိုင်အဆင့်အထိ တိုးတက်စေဖို့ -

- အဓိပ္ပာယ်ရှိတဲ့ Class အမည်တွေ သုံးပါ။
- HTML နဲ့ CSS ကို သီးခြားထားပါ။
- ထပ်နေတဲ့ CSS Rule တွေကို လျှော့ချပါ။
- Spacing နဲ့ Color တွေကို တသမတ်တည်း သုံးပါ။
- Responsive Design ကို စမ်းသပ်ပါ။
- Accessibility ကို ဂရုစိုက်ပါ။
- Git နဲ့ GitHub ကို အသုံးပြုပြီး Code Version တွေ သိမ်းဆည်းပါ။

# အခန်း ၁၉ — လေ့ကျင့်ခန်းများ

## လေ့ကျင့်ခန်း ၁ — HTML အခြေခံ

အောက်ပါမေးခွန်းတွေကို ကိုယ်တိုင် ဖြေကြည့်ပါ။

1. HTML ရဲ့ အရှည်ကောက်က ဘာလဲ။
2. CSS ရဲ့ အဓိကတာဝန်က ဘာလဲ။
3. စာပိုဒ်တစ်ခု ဖန်တီးဖို့ ဘယ် Tag ကို သုံးသလဲ။
4. Heading အဆင့် ဘယ်နှစ်ဆင့် ရှိသလဲ။
5. ပုံထည့်ဖို့ ဘယ် Element ကို သုံးသလဲ။
6. Link ဖန်တီးဖို့ ဘယ် Element ကို သုံးသလဲ။
7. Ordered List နဲ့ Unordered List က ဘာကွာသလဲ။
8. Form ထဲမှာ `required` က ဘာလုပ်ပေးသလဲ။

## လေ့ကျင့်ခန်း ၂ — CSS အခြေခံ

1. CSS Rule တစ်ခုရဲ့ အဓိကအစိတ်အပိုင်းတွေက ဘာတွေလဲ။
2. Class Selector ကို ဘယ်သင်္ကေတနဲ့ စရေးသလဲ။
3. ID Selector ကို ဘယ်သင်္ကေတနဲ့ စရေးသလဲ။
4. Margin နဲ့ Padding ဘာကွာသလဲ။
5. Flexbox ကို ဘာအတွက် အသုံးပြုသလဲ။
6. Grid နဲ့ Flexbox ဘယ်လိုကွာသလဲ။
7. Media Query က ဘာလုပ်ပေးသလဲ။
8. Responsive Design ဆိုတာ ဘာလဲ။

## လေ့ကျင့်ခန်း ၃ — Mini Project

HTML နဲ့ CSS ကို အသုံးပြုပြီး ကိုယ်ပိုင် Profile Website တစ်ခု တည်ဆောက်ပါ။

ပါဝင်ရမယ့် အချက်တွေ -

- Navigation Bar
- ကိုယ်ရေးမိတ်ဆက်
- Profile Photo
- ကျွမ်းကျင်မှု အနည်းဆုံး သုံးခု
- Project Card အနည်းဆုံး နှစ်ခု
- Contact Section
- Footer
- Responsive Layout

## အဖြေညွှန်း

1. HTML — HyperText Markup Language။
2. CSS — Cascading Style Sheets။
3. စာပိုဒ်အတွက် `<p>`။
4. Heading အဆင့် ခြောက်ဆင့်၊ `<h1>` မှ `<h6>`။
5. ပုံအတွက် `<img>`။
6. Link အတွက် `<a>`။
7. `<ol>` က အစဉ်လိုက်စာရင်း၊ `<ul>` က ပုံမှန်စာရင်း။
8. `required` က Form Field ကို မဖြစ်မနေ ဖြည့်ရန် သတ်မှတ်ပေးသည်။
9. Class Selector — `.name`။
10. ID Selector — `#name`။
11. Margin — Element အပြင်ဘက်အကွာအဝေး။
12. Padding — Element အတွင်းဘက်အကွာအဝေး။
13. Flexbox — တစ်ဘက်တည်းအတိုင်း Layout စီစဉ်ရန် အထူးအသုံးဝင်သည်။
14. Grid — Row နဲ့ Column နှစ်ဘက်အတိုင်း Layout စီစဉ်ရန် အသုံးဝင်သည်။
15. Media Query — သတ်မှတ်ထားတဲ့ အခြေအနေအလိုက် CSS Rule တွေ အသုံးချစေသည်။

# အခန်း ၂၀ — နောက်ထပ်လေ့လာရန် လမ်းညွှန်

HTML နဲ့ CSS အခြေခံတွေကို နားလည်လာပြီဆိုရင် အောက်ပါအစီအစဉ်အတိုင်း ဆက်လက်လေ့လာနိုင်ပါတယ်။

အဆင့် ၁ — HTML

Tags၊ Attributes၊ Forms၊ Tables၊ Semantic HTML

စာမျက်နှာရဲ့ ဖွဲ့စည်းပုံကို ကိုယ်တိုင် ရေးသားနိုင်အောင် လေ့ကျင့်ပါ။

အဆင့် ၂ — CSS

Selectors၊ Box Model၊ Flexbox၊ Grid၊ Responsive Design

လှပပြီး မျက်နှာပြင်အရွယ်အစားအလိုက် လိုက်လျောညီထွေရှိတဲ့ Website တွေ ဖန်တီးပါ။

အဆင့် ၃ — Git နှင့် GitHub

Code Version တွေကို စနစ်တကျ သိမ်းဆည်းပြီး ကိုယ်ပိုင် Project တွေကို ပြသတတ်အောင် လေ့လာပါ။

အဆင့် ၄ — JavaScript

Website ကို Interactive ဖြစ်အောင် ပြုလုပ်ခြင်း၊ Form Validation နဲ့ Dynamic Content တို့ကို လေ့လာပါ။

အဆင့် ၅ — Frontend Frameworks

HTML၊ CSS နဲ့ JavaScript အခြေခံခိုင်မာလာတဲ့အခါ React သို့မဟုတ် အခြား Frontend Framework တွေကို ဆက်လက်လေ့လာပါ။

## အခမဲ့လေ့လာနိုင်သော အရင်းအမြစ်များ

- MDN Web Docs — [HTML, CSS နှင့် Web Development လမ်းညွှန်](https://developer.mozilla.org/en-US/docs/Learn_web_development?utm_source=chatgpt.com)
- W3C — [Web Accessibility လမ်းညွှန်](https://www.w3.org/WAI/?utm_source=chatgpt.com)
- WHATWG — [HTML Standard](https://html.spec.whatwg.org/?utm_source=chatgpt.com)

## နိဂုံးချုပ်

HTML နဲ့ CSS ကို သင်ယူတဲ့အခါ စာဖတ်ရုံနဲ့ မလုံလောက်ပါဘူး။ ကိုယ်တိုင် Code ရေးပါ၊ Browser မှာ စမ်းသပ်ပါ၊ အမှားတွေ့ရင် အကြောင်းရင်းကို ရှာဖွေပြီး ပြင်ဆင်ပါ။

ပထမဆုံး Website က ရိုးရှင်းနေနိုင်ပါတယ်။ ဒါပေမဲ့ Project တစ်ခုချင်းစီကို ကိုယ်တိုင် တည်ဆောက်သွားရင် ပိုမိုရှုပ်ထွေးတဲ့ Website တွေကိုလည်း တဖြည်းဖြည်း ဖန်တီးနိုင်လာပါလိမ့်မယ်။

မှတ်ထားရမယ့် အချက်တစ်ခုက — Code ကို အလွတ်ကျက်တာထက် ဘာကြောင့် ဒီလိုရေးရသလဲဆိုတာ နားလည်ဖို့ ပိုအရေးကြီးပါတယ်။# HTML နှင့် CSS အခြေခံလမ်းညွှန်စာအုပ်

Beginner to Intermediate • မြန်မာဘာသာဖြင့် • လက်တွေ့ကုဒ်နမူနာများနှင့် လေ့ကျင့်ခန်းများ

ဒီစာအုပ်ကို Programming ကို အခုမှ စတင်လေ့လာသူတွေအတွက် ရေးသားထားပါတယ်။ HTML နဲ့ CSS ကို အခြေခံကနေ စတင်ပြီး ကိုယ်ပိုင် Website တစ်ခု တည်ဆောက်နိုင်တဲ့အထိ အဆင့်ဆင့် လေ့လာသွားပါမယ်။

ကုဒ်ထဲက HTML tag၊ CSS property နဲ့ programming ဆိုင်ရာ ဝေါဟာရတွေကို မူရင်းအင်္ဂလိပ်အတိုင်း ထားရှိပြီး မြန်မာလို နားလည်လွယ်အောင် ရှင်းပြထားပါတယ်။

## မာတိကာ

1. Website နှင့် HTML/CSS မိတ်ဆက်
2. လိုအပ်သော Tools များနှင့် ပထမဆုံး HTML ဖိုင်
3. HTML Document ဖွဲ့စည်းပုံ
4. Headings၊ Paragraphs နှင့် Text Formatting
5. Links နှင့် Images
6. Lists နှင့် Tables
7. Forms နှင့် Input များ
8. Semantic HTML နှင့် Accessibility
9. CSS မိတ်ဆက်နှင့် CSS ချိတ်ဆက်နည်း
10. CSS Selectors၊ Colors နှင့် Typography
11. Box Model၊ Margin နှင့် Padding
12. Borders၊ Backgrounds နှင့် Shadows
13. Display နှင့် Flexbox
14. CSS Grid နှင့် Position
15. Responsive Design
16. Pseudo-classes နှင့် Transitions
17. ကိုယ်ရေးမိတ်ဆက် Website တည်ဆောက်ခြင်း
18. အမှားရှာဖွေခြင်းနှင့် ကုဒ်ရေးသားမှုဆိုင်ရာ အလေ့အကျင့်ကောင်းများ
19. လေ့ကျင့်ခန်းများ
20. နောက်ထပ်လေ့လာရန် လမ်းညွှန်

# အခန်း ၁ — Website နှင့် HTML/CSS မိတ်ဆက်

## ၁.၁ Website ဆိုတာဘာလဲ။

Website ဆိုတာ Internet ပေါ်တွင် Browser အသုံးပြုပြီး ဝင်ရောက်ကြည့်ရှုနိုင်တဲ့ Web Pages များကို စုစည်းထားခြင်း ဖြစ်ပါတယ်။

ဥပမာ -

- Online Shopping Website
- Education Website
- News Website
- Personal Portfolio Website
- Social Media Website

Website တစ်ခုကို တည်ဆောက်ရာမှာ နည်းပညာအမျိုးမျိုးကို အသုံးပြုနိုင်ပါတယ်။ စတင်လေ့လာသူတစ်ယောက်အတွက် အရေးကြီးဆုံး အခြေခံနည်းပညာနှစ်ခုကတော့ HTML နဲ့ CSS ဖြစ်ပါတယ်။

## ၁.၂ HTML ဆိုတာဘာလဲ။

HTML ရဲ့ အရှည်ကောက်က HyperText Markup Language ဖြစ်ပါတယ်။

HTML ကို Website ရဲ့ ဖွဲ့စည်းပုံနဲ့ အကြောင်းအရာတွေ သတ်မှတ်ဖို့ အသုံးပြုပါတယ်။

ဥပမာ -

- ခေါင်းစဉ်များ
- စာပိုဒ်များ
- ပုံများ
- လင့်ခ်များ
- စာရင်းများ
- Form များ

ပထမဆုံး HTML နမူနာကို ကြည့်ကြည့်ရအောင်။

```
<h1>မင်္ဂလာပါ</h1>

<p>HTML ကို စတင်လေ့လာနေပါတယ်။</p>
```

ဒီကုဒ်မှာ -

- `<h1>` က အဓိကခေါင်းစဉ်ကို ဖော်ပြပါတယ်။
- `<p>` က စာပိုဒ်တစ်ခုကို ဖော်ပြပါတယ်။

## ၁.၃ CSS ဆိုတာဘာလဲ။

CSS ရဲ့ အရှည်ကောက်က Cascading Style Sheets ဖြစ်ပါတယ်။

HTML က Website ရဲ့ ဖွဲ့စည်းပုံကို တည်ဆောက်ပေးပြီး CSS က အဲဒီအကြောင်းအရာတွေကို အလှဆင်ပေးပါတယ်။

ဥပမာ -

```
h1 {
    color: blue;
    font-size: 36px;
}

p {
    color: gray;
    font-size: 18px;
}
```

ဒီကုဒ်က ခေါင်းစဉ်ကို အပြာရောင်၊ စာလုံးအရွယ်အစား 36px သတ်မှတ်ပေးပြီး စာပိုဒ်ကို မီးခိုးရောင်၊ 18px သတ်မှတ်ပေးပါတယ်။

## ၁.၄ HTML၊ CSS နှင့် JavaScript ကွာခြားချက်

HTML — Structure

Website မှာ ဘာအကြောင်းအရာတွေ ပါဝင်မလဲဆိုတာ သတ်မှတ်ပေးပါတယ်။

CSS — Design

အရောင်၊ အရွယ်အစား၊ အကွာအဝေးနဲ့ Layout တွေကို သတ်မှတ်ပေးပါတယ်။

JavaScript — Interactivity

Button နှိပ်တဲ့အခါ လုပ်ဆောင်မှုတွေ ဖြစ်ပေါ်စေခြင်း၊ အချက်အလက်ပြောင်းလဲခြင်းတို့ကို လုပ်ဆောင်ပေးပါတယ်။

## ၁.၅ HTML နှင့် CSS ကို ဘာကြောင့် လေ့လာသင့်သလဲ။

- ကိုယ်ပိုင် Website များ ဖန်တီးနိုင်ပါတယ်။
- Frontend Development ကို ဆက်လက်လေ့လာနိုင်ပါတယ်။
- React၊ Next.js စတဲ့ Framework တွေကို နားလည်ဖို့ အခြေခံကောင်း ရရှိပါတယ်။
- Portfolio Website တည်ဆောက်ပြီး ကိုယ့်ရဲ့ Project တွေကို ပြသနိုင်ပါတယ်။
- Web Developer အဖြစ် အလုပ်အကိုင်အခွင့်အလမ်းတွေကို စတင်ပြင်ဆင်နိုင်ပါတယ်။

# အခန်း ၂ — လိုအပ်သော Tools များနှင့် ပထမဆုံး HTML ဖိုင်

## ၂.၁ ဘာတွေ လိုအပ်သလဲ။

HTML နဲ့ CSS ကို စတင်လေ့လာဖို့ အထူးစျေးကြီးတဲ့ Computer သို့မဟုတ် Software မလိုအပ်ပါဘူး။

လိုအပ်တာတွေကတော့ -

- Computer သို့မဟုတ် Laptop
- Web Browser — Chrome၊ Edge သို့မဟုတ် Firefox
- Code Editor — Visual Studio Code (VS Code)
- HTML နဲ့ CSS ရေးသားလေ့ကျင့်ဖို့ Folder တစ်ခု

## ၂.၂ Project Folder ဖန်တီးခြင်း

ပထမဆုံး `my-website` ဆိုတဲ့ Folder တစ်ခု ဖန်တီးပါ။

VS Code ကို ဖွင့်ပြီး အဲဒီ Folder ကို Open Folder နဲ့ ဖွင့်ပါ။

ပြီးရင် `index.html` ဆိုတဲ့ ဖိုင်အသစ်တစ်ခု ဖန်တီးပါ။

Project ဖိုင်တွေကို ဒီလို စီစဉ်ထားနိုင်ပါတယ်။

```
my-website/
├── index.html
├── style.css
└── images/
    └── profile.jpg
```

- `index.html` — Website ရဲ့ HTML ဖိုင်။
- `style.css` — Website ရဲ့ CSS ဖိုင်။
- `images/` — ပုံတွေ သိမ်းထားဖို့ Folder။

## ၂.၃ ပထမဆုံး HTML Code

`index.html` ထဲမှာ အောက်ပါကုဒ်ကို ရေးပါ။

```
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>ကျွန်ုပ်၏ Website</title>
</head>
<body>
    <h1>မင်္ဂလာပါ။</h1>

    <p>ဒါက ကျွန်ုပ်ရဲ့ ပထမဆုံး Website ဖြစ်ပါတယ်။</p>
</body>
</html>
```

### Code တစ်ကြောင်းချင်း ရှင်းပြချက်

`<!DOCTYPE html>` — HTML5 document ဖြစ်ကြောင်း Browser ကို ပြောပြပါတယ်။

`<html lang="my">` — HTML document တစ်ခုလုံးကို စတင်ဖော်ပြပြီး အဓိကဘာသာစကားကို မြန်မာဘာသာအဖြစ် သတ်မှတ်ပါတယ်။

`<head>` — Website အကြောင်း Metadata နဲ့ Browser Tab မှာ ပေါ်မယ့် Title တို့ကို ထည့်သွင်းတဲ့နေရာ ဖြစ်ပါတယ်။

`<meta charset="UTF-8">` — မြန်မာစာအပါအဝင် Unicode စာသားတွေကို မှန်ကန်စွာ ဖတ်ရှုနိုင်ဖို့ သတ်မှတ်ပေးပါတယ်။

`<meta name="viewport" ...>` — Mobile ဖုန်းတွေရဲ့ မျက်နှာပြင်အရွယ်အစားနဲ့ ကိုက်ညီအောင် ပြသနိုင်ဖို့ အရေးကြီးပါတယ်။

`<title>` — Browser Tab ပေါ်မှာ ပေါ်လာမယ့် အမည်ဖြစ်ပါတယ်။

`<body>` — အသုံးပြုသူ မြင်တွေ့ရမယ့် အဓိကအကြောင်းအရာတွေကို ထည့်သွင်းတဲ့နေရာ ဖြစ်ပါတယ်။

## ၂.၄ Browser မှာ ဖွင့်ကြည့်ခြင်း

1. `Ctrl + S` နှိပ်ပြီး ဖိုင်ကို သိမ်းပါ။
2. `index.html` ဖိုင်ကို ရှာပါ။
3. ဖိုင်ကို Double-click နှိပ်ပြီး Browser နဲ့ ဖွင့်ပါ။
4. ကုဒ်ပြင်ပြီးတိုင်း သိမ်းဆည်းကာ Browser ကို Refresh လုပ်ပါ။

မှတ်ချက်။ မြန်မာစာ မမှန်ကန်ပါက ဖိုင်ထဲမှာ UTF-8 သတ်မှတ်ထားခြင်း၊ Unicode စာသားအသုံးပြုထားခြင်းနဲ့ စက်ထဲရှိ မြန်မာဖောင့်တို့ကို စစ်ဆေးပါ။

### လေ့ကျင့်ခန်း

- Website Title ကို မိမိအမည်ဖြင့် ပြောင်းပါ။
- `h1` ခေါင်းစဉ်တစ်ခု ထည့်ပါ။
- ကိုယ့်အကြောင်း စာပိုဒ်နှစ်ပိုဒ် ရေးပါ။

# အခန်း ၃ — HTML Document ဖွဲ့စည်းပုံ

## ၃.၁ Tag ဆိုတာဘာလဲ။

HTML Tag ဆိုတာ Browser ကို အကြောင်းအရာတစ်ခုရဲ့ အမျိုးအစားနဲ့ ဖွဲ့စည်းပုံကို ဖော်ပြပေးတဲ့ သတ်မှတ်ချက် ဖြစ်ပါတယ်။

ဥပမာ -

```
<p>ဒါက စာပိုဒ်တစ်ခုပါ။</p>
```

ဒီမှာ -

- `<p>` — Opening Tag
- `ဒါက စာပိုဒ်တစ်ခုပါ။` — Content
- `</p>` — Closing Tag

ဒီလို Tag နဲ့ Content ပေါင်းစပ်ထားတဲ့ အစိတ်အပိုင်းကို HTML Element လို့ ခေါ်ပါတယ်။

## ၃.၂ Attributes ဆိုတာဘာလဲ။

Attribute ဆိုတာ HTML Element တစ်ခုအကြောင်း ထပ်ဆောင်းအချက်အလက် ပေးတဲ့အရာ ဖြစ်ပါတယ်။

```
<a href="https://developer.mozilla.org/">
    HTML လေ့လာရန်
</a>
```

ဒီဥပမာမှာ `href` က Attribute ဖြစ်ပြီး URL က သူ့ရဲ့ Value ဖြစ်ပါတယ်။

နောက်ထပ်ဥပမာ -

```
<img
    src="images/profile.jpg"
    alt="ကျွန်ုပ်၏ ကိုယ်ရေးပုံ"
>
```

- `src` — ပုံဖိုင်ရဲ့ လမ်းကြောင်း။
- `alt` — ပုံအကြောင်း ဖော်ပြတဲ့ စာသား။

## ၃.၃ HTML Element တွေကို မှန်ကန်စွာ အစီအစဉ်ချခြင်း

HTML Element တွေကို တစ်ခုအတွင်း တစ်ခု ထည့်သွင်းနိုင်ပါတယ်။ ဒီနည်းလမ်းကို Nesting လို့ ခေါ်ပါတယ်။

မှန်ကန်တဲ့ပုံစံ -

```
<div>
    <h2>HTML သင်ခန်းစာ</h2>

    <p>
        HTML ကို <strong>လက်တွေ့</strong> လေ့လာကြမယ်။
    </p>
</div>
```

မှားယွင်းတဲ့ပုံစံ -

```
<p>
    <strong>မင်္ဂလာပါ။
</p>
</strong>
```

အဖွင့်နဲ့ အပိတ် Tag တွေကို မှန်ကန်စွာ တွဲဖက်အသုံးပြုဖို့ လိုအပ်ပါတယ်။

## ၃.၄ အပိတ် Tag မလိုအပ်သော Element များ

HTML Element အားလုံးမှာ Closing Tag မလိုအပ်ပါဘူး။

ဥပမာ -

```
<img src="photo.jpg" alt="ဓာတ်ပုံ">

<br>

<hr>

<meta charset="UTF-8">
```

`img`၊ `br`၊ `hr` နဲ့ `meta` တို့ဟာ ပုံမှန်အားဖြင့် Closing Tag မလိုအပ်တဲ့ Element တွေ ဖြစ်ပါတယ်။

# အခန်း ၄ — Headings၊ Paragraphs နှင့် Text Formatting

## ၄.၁ Headings

HTML မှာ Heading အဆင့် ခြောက်ဆင့် ရှိပါတယ်။

```
<h1>အဓိကခေါင်းစဉ်</h1>

<h2>ခေါင်းစဉ်ခွဲ</h2>

<h3>ခေါင်းစဉ်ခွဲ၏ အောက်အဆင့်</h3>

<h4>Heading 4</h4>

<h5>Heading 5</h5>

<h6>Heading 6</h6>
```

`h1` ဟာ အဓိကခေါင်းစဉ်ဖြစ်ပြီး `h6` က အငယ်ဆုံး Heading အဆင့် ဖြစ်ပါတယ်။

Heading တွေကို စာလုံးအရွယ်အစားအတွက်သာ မသုံးဘဲ အကြောင်းအရာရဲ့ ဖွဲ့စည်းပုံနဲ့ ကိုက်ညီအောင် အသုံးပြုသင့်ပါတယ်။

## ၄.၂ Paragraph

စာပိုဒ်တစ်ခု ရေးချင်ရင် `<p>` ကို အသုံးပြုပါ။

```
<p>
    HTML သည် Website တည်ဆောက်ရာတွင်
    အခြေခံအကျဆုံး နည်းပညာတစ်ခု ဖြစ်သည်။
</p>

<p>
    CSS ကို အသုံးပြု၍ Website ကို
    လှပစွာ ဒီဇိုင်းဆွဲနိုင်သည်။
</p>
```

## ၄.၃ Text Formatting

| Tag        | အသုံးပြုပုံ                            |
| ---------- | -------------------------------------- |
| `<strong>` | အရေးကြီးသော စာသား                      |
| `<em>`     | အလေးပေးသော စာသား                       |
| `<mark>`   | အမှတ်အသားပြုထားသော စာသား               |
| `<small>`  | စာလုံးသေးသော စာသား                     |
| `<del>`    | ဖယ်ရှားထားသော စာသား                    |
| `<br>`     | စာကြောင်းအသစ်သို့ ဆင်းခြင်း            |
| `<hr>`     | အကြောင်းအရာအပိုင်းများကို ခွဲခြားခြင်း |

ဥပမာ -

```
<p>
    <strong>သတိပြုရန်။</strong>
    ကုဒ်ကို သိမ်းဆည်းဖို့ မမေ့ပါနှင့်။
</p>

<p>
    HTML သည် <em>အရေးကြီးသော</em> အခြေခံဖြစ်သည်။
</p>

<p>
    မူလဈေးနှုန်း:
    <del>50,000 ကျပ်</del>
</p>

<hr>
```

# အခန်း ၅ — Links နှင့် Images

## ၅.၁ Links ဖန်တီးခြင်း

Website တစ်ခုမှ အခြား Website တစ်ခုသို့ သွားရန် သို့မဟုတ် ကိုယ့် Website ရဲ့ အခြားစာမျက်နှာတစ်ခုသို့ သွားရန် `<a>` Element ကို အသုံးပြုပါတယ်။

```
<a href="https://www.google.com/">
    Google သို့ သွားရန်
</a>
```

### ကိုယ့် Website အတွင်းရှိ စာမျက်နှာများသို့ ချိတ်ဆက်ခြင်း

```
<a href="about.html">ကျွန်ုပ်အကြောင်း</a>

<a href="contact.html">ဆက်သွယ်ရန်</a>
```

### Link ကို Tab အသစ်မှာ ဖွင့်ခြင်း

```
<a
    href="https://developer.mozilla.org/"
    target="_blank"
    rel="noopener noreferrer"
>
    MDN ကို လေ့လာရန်
</a>
```

`target="_blank"` က Link ကို Tab အသစ်မှာ ဖွင့်ပေးပါတယ်။

## ၅.၂ Images ထည့်ခြင်း

```
<img
    src="images/profile.jpg"
    alt="အပြင်ဘက်တွင် ရိုက်ထားသော ကိုယ်ရေးပုံ"
    width="300"
>
```

ပုံအတွက် အရေးကြီးတဲ့ Attribute တွေက -

- `src` — ပုံဖိုင်ရဲ့ လမ်းကြောင်း။
- `alt` — ပုံကို အဓိပ္ပာယ်ဖော်ပြပေးတဲ့ စာသား။
- `width` — ပုံရဲ့ အကျယ်။
- `height` — ပုံရဲ့ အမြင့်။

CSS ဖြင့် ပုံအရွယ်အစားကို Responsive ဖြစ်အောင်လည်း ပြုလုပ်နိုင်ပါတယ်။

```
img {
    max-width: 100%;
    height: auto;
}
```

ဒီနည်းလမ်းက ပုံကို မိမိရဲ့ Container ထက် ကျော်လွန်မသွားစေဘဲ အချိုးအစားမပျက်အောင် ကူညီပေးပါတယ်။

# အခန်း ၆ — Lists နှင့် Tables

## ၆.၁ Unordered List

အစဉ်လိုက် နံပါတ်မလိုအပ်တဲ့ စာရင်းအတွက် `<ul>` ကို သုံးပါတယ်။

```
<h2>လေ့လာမည့် ဘာသာရပ်များ</h2>

<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

## ၆.၂ Ordered List

အစဉ်လိုက် နံပါတ်လိုအပ်တဲ့ စာရင်းအတွက် `<ol>` ကို သုံးပါတယ်။

```
<h2>Website တည်ဆောက်ရန် အဆင့်များ</h2>

<ol>
    <li>Project Folder ဖန်တီးပါ။</li>
    <li>HTML ရေးပါ။</li>
    <li>CSS ချိတ်ဆက်ပါ။</li>
    <li>Browser မှာ စမ်းသပ်ပါ။</li>
</ol>
```

## ၆.၃ HTML Table

ဇယားတစ်ခုကို အောက်ပါ Element တွေနဲ့ တည်ဆောက်နိုင်ပါတယ်။

- `<table>` — ဇယားတစ်ခုလုံး။
- `<tr>` — ဇယားတစ်တန်း။
- `<th>` — ခေါင်းစီးဆဲလ်။
- `<td>` — ပုံမှန်အချက်အလက်ဆဲလ်။
- `<thead>` — ခေါင်းစီးအပိုင်း။
- `<tbody>` — အဓိကအချက်အလက်အပိုင်း။
- `<caption>` — ဇယားခေါင်းစဉ်။

```
<table>
    <caption>သင်တန်းအချိန်ဇယား</caption>

    <thead>
        <tr>
            <th>နေ့</th>
            <th>ဘာသာရပ်</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>သောကြာ</td>
            <td>HTML</td>
        </tr>

        <tr>
            <td>စနေ</td>
            <td>CSS</td>
        </tr>
    </tbody>
</table>
```

Table ကို အချက်အလက်တွေ ဇယားပုံစံနဲ့ ဖော်ပြဖို့ အသုံးပြုပါ။ Website ရဲ့ Layout တည်ဆောက်ရာမှာတော့ Flexbox သို့မဟုတ် Grid ကို အသုံးပြုတာ ပိုသင့်တော်ပါတယ်။

# အခန်း ၇ — Forms နှင့် Input များ

## ၇.၁ Form ဆိုတာဘာလဲ။

Form ဆိုတာ အသုံးပြုသူထံမှ အချက်အလက်တွေ ရယူဖို့ အသုံးပြုတဲ့ HTML Element ဖြစ်ပါတယ်။

ဥပမာ -

- Login Form
- Registration Form
- Contact Form
- Search Form
- Feedback Form

## ၇.၂ Input Element

```
<form>
    <label for="username">အသုံးပြုသူအမည်</label>

    <input
        type="text"
        id="username"
        name="username"
        required
    >

    <button type="submit">ပေးပို့ရန်</button>
</form>
```

`input` မှာ အသုံးများတဲ့ Attribute တွေက -

- `type` — ထည့်သွင်းမယ့် အချက်အလက်အမျိုးအစား။
- `id` — Element ကို သီးခြားသတ်မှတ်ပေးခြင်း။
- `name` — Form က ပေးပို့မယ့် အချက်အလက်ရဲ့ အမည်။
- `required` — အချက်အလက် မဖြစ်မနေထည့်ရန် သတ်မှတ်ခြင်း။
- `placeholder` — Input အတွင်း အညွှန်းစာသား ပြသခြင်း။

## ၇.၃ Input အမျိုးအစားများ

```
<input type="text" placeholder="အမည်">

<input type="email" placeholder="အီးမေးလ်">

<input type="password" placeholder="စကားဝှက်">

<input type="number" placeholder="အသက်">

<input type="date">

<input type="checkbox">

<input type="radio">

<input type="file">
```

Input တစ်ခုချင်းစီမှာ သက်ဆိုင်ရာ လုပ်ဆောင်ချက်နဲ့ ရည်ရွယ်ချက် ရှိပါတယ်။

## ၇.၄ ပြည့်စုံသော Registration Form

```
<form action="/register" method="post">

    <label for="name">အမည်</label>
    <input
        type="text"
        id="name"
        name="name"
        required
    >

    <label for="email">အီးမေးလ်</label>
    <input
        type="email"
        id="email"
        name="email"
        required
    >

    <label for="password">စကားဝှက်</label>
    <input
        type="password"
        id="password"
        name="password"
        minlength="8"
        required
    >

    <button type="submit">စာရင်းသွင်းရန်</button>

</form>
```

ဒီ Form မှာ `action="/register"` က အချက်အလက်ပေးပို့မယ့် URL ကို သတ်မှတ်ထားပြီး `method="post"` က HTTP POST method ကို အသုံးပြုထားပါတယ်။

သို့သော် HTML Form တစ်ခုတည်းနဲ့ အသုံးပြုသူအချက်အလက်ကို Database ထဲ အလိုအလျောက် သိမ်းဆည်းပေးမှာ မဟုတ်ပါဘူး။ Server သို့မဟုတ် Backend လိုအပ်ပါတယ်။

## ၇.၅ CSS ဖြင့် Form ကို အလှဆင်ခြင်း

```
form {
    max-width: 420px;
    margin: 30px auto;
    padding: 24px;
    background-color: white;
    border-radius: 12px;
}

label {
    display: block;
    margin-bottom: 6px;
}

input {
    width: 100%;
    padding: 12px;
    margin-bottom: 16px;
    border: 1px solid #cccccc;
    border-radius: 6px;
}

button {
    padding: 12px 20px;
    background-color: #1769AA;
    color: white;
    border: none;
    border-radius: 6px;
    cursor: pointer;
}
```

သတိပြုရန်။ Browser ဘက်မှာ စစ်ဆေးခြင်းတစ်ခုတည်းကို မယုံကြည်ပါနှင့်။ အရေးကြီးတဲ့ အချက်အလက်တွေကို Backend မှာလည်း Validate လုပ်ဖို့ လိုအပ်ပါတယ်။

# အခန်း ၈ — Semantic HTML နှင့် Accessibility

## ၈.၁ Semantic HTML ဆိုတာဘာလဲ။

Semantic HTML ဆိုတာ Element တစ်ခုရဲ့ အဓိပ္ပာယ်နဲ့ ရည်ရွယ်ချက်ကို ရှင်းလင်းစွာ ဖော်ပြပေးတဲ့ HTML ဖြစ်ပါတယ်။

ဥပမာ `div` ကို နေရာတိုင်းမှာ အသုံးပြုမယ့်အစား သက်ဆိုင်ရာ အဓိပ္ပာယ်ရှိတဲ့ Element တွေကို ရွေးချယ်နိုင်ပါတယ်။

| Element   | ရည်ရွယ်ချက်                           |
| --------- | ------------------------------------- |
| `header`  | ခေါင်းစီးနှင့် မိတ်ဆက်အပိုင်း         |
| `nav`     | လမ်းညွှန်လင့်ခ်များ                   |
| `main`    | အဓိကအကြောင်းအရာ                       |
| `section` | အကြောင်းအရာအပိုင်းတစ်ခု               |
| `article` | ကိုယ်ပိုင်အဓိပ္ပာယ်ရှိသော အကြောင်းအရာ |
| `aside`   | ဆက်စပ်အကြောင်းအရာ                     |
| `footer`  | အောက်ခြေအချက်အလက်                     |

## ၈.၂ Semantic Website နမူနာ

```
<header>
    <h1>My Website</h1>

    <nav aria-label="အဓိက လမ်းညွှန်">
        <a href="/">ပင်မစာမျက်နှာ</a>
        <a href="/about.html">ကျွန်ုပ်အကြောင်း</a>
        <a href="/contact.html">ဆက်သွယ်ရန်</a>
    </nav>
</header>

<main>
    <section>
        <h2>ကျွန်ုပ်တို့အကြောင်း</h2>

        <p>ကျွန်ုပ်တို့သည် Web Development ကို လေ့လာနေပါသည်။</p>
    </section>

    <article>
        <h2>HTML အခြေခံ</h2>

        <p>HTML သည် Website တည်ဆောက်ရာတွင် အသုံးပြုသည်။</p>
    </article>
</main>

<footer>
    <p>© 2026 My Website</p>
</footer>
```

## ၈.၃ Accessibility ဆိုတာဘာလဲ။

Accessibility ဆိုတာ လူအမျိုးမျိုး၊ စွမ်းရည်အမျိုးမျိုးရှိတဲ့ အသုံးပြုသူတွေ Website ကို အသုံးပြုနိုင်အောင် ပြုလုပ်ပေးခြင်း ဖြစ်ပါတယ်။

အရေးကြီးတဲ့ အချက်တွေက -

- ပုံတွေမှာ သင့်လျော်တဲ့ `alt` စာသား ထည့်ပါ။
- Form တစ်ခုချင်းစီအတွက် Label ထည့်ပါ။
- Heading တွေကို အစီအစဉ်တကျ အသုံးပြုပါ။
- Keyboard နဲ့ Website ကို အသုံးပြုနိုင်စေပါ။
- စာသားနဲ့ နောက်ခံအရောင်ကြား ဖတ်ရှုရလွယ်ကူတဲ့ ကွာခြားမှုရှိပါစေ။
- Focus ဖြစ်နေတဲ့ Link နဲ့ Button တွေကို မြင်သာစေပါ။

# အခန်း ၉ — CSS မိတ်ဆက်နှင့် CSS ချိတ်ဆက်နည်း

## ၉.၁ CSS Rule ရဲ့ ဖွဲ့စည်းပုံ

```
p {
    color: blue;
    font-size: 18px;
}
```

ဒီကုဒ်မှာ -

- `p` — Selector
- `color` — Property
- `blue` — Value
- `font-size` — Property
- `18px` — Value

CSS Rule တစ်ခုကို ပုံမှန်အားဖြင့် ဒီပုံစံနဲ့ ရေးပါတယ်။

```
selector {
    property: value;
}
```

## ၉.၂ Inline CSS

HTML Element တစ်ခုရဲ့ `style` Attribute အတွင်း CSS ရေးသားခြင်း ဖြစ်ပါတယ်။

```
<h1 style="color: blue;">
    မင်္ဂလာပါ
</h1>
```

ဒီနည်းက Element တစ်ခုအတွက် အလျင်အမြန် စမ်းသပ်ရာမှာ အသုံးဝင်ပေမဲ့ Website ကြီးလာတဲ့အခါ ထိန်းသိမ်းရခက်နိုင်ပါတယ်။

## ၉.၃ Internal CSS

HTML ဖိုင်ထဲက `head` အပိုင်းမှာ `style` Element အသုံးပြုပြီး CSS ရေးခြင်း ဖြစ်ပါတယ်။

```
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">

    <title>Internal CSS</title>

    <style>
        h1 {
            color: darkblue;
        }

        p {
            font-size: 18px;
        }
    </style>
</head>

<body>
    <h1>မင်္ဂလာပါ</h1>

    <p>Internal CSS ကို လေ့လာနေပါတယ်။</p>
</body>
</html>
```

## ၉.၄ External CSS

External CSS ဆိုတာ CSS ကို သီးခြားဖိုင်တစ်ခုအဖြစ် ရေးသားခြင်း ဖြစ်ပါတယ်။

Project Folder -

```
my-website/
├── index.html
└── style.css
```

`index.html` -

```
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>My Website</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <h1>မင်္ဂလာပါ</h1>

    <p>External CSS ကို အသုံးပြုထားပါတယ်။</p>
</body>
</html>
```

`style.css` -

```
h1 {
    color: #1769AA;
    font-size: 36px;
}

p {
    color: #555555;
    font-size: 18px;
}
```

### ဘယ်နည်းလမ်းကို ရွေးချယ်သင့်သလဲ။

ပုံမှန် Website Project တွေအတွက် External CSS ကို ဦးစားပေးအသုံးပြုသင့်ပါတယ်။ HTML နဲ့ CSS ကို သီးခြားထားခြင်းက Code ကို ဖတ်ရှုရလွယ်ကူစေပြီး ပြုပြင်ထိန်းသိမ်းရာမှာလည်း အဆင်ပြေစေပါတယ်။

# အခန်း ၁၀ — CSS Selectors၊ Colors နှင့် Typography

## ၁၀.၁ Element Selector

HTML Element အမျိုးအစားကို တိုက်ရိုက် ရွေးချယ်ပါတယ်။

```
p {
    color: gray;
}

h1 {
    color: navy;
}
```

ဒီ CSS က `p` Element အားလုံးနဲ့ `h1` Element အားလုံးကို သက်ဆိုင်ရာ Style သတ်မှတ်ပေးပါတယ်။

## ၁၀.၂ Class Selector

Class Selector ကို `.` နဲ့ စတင်ရေးသားပါတယ်။

HTML -

```
<p class="description">
    HTML သင်ခန်းစာမှ ကြိုဆိုပါတယ်။
</p>

<p class="description">
    CSS သင်ခန်းစာကို ဆက်လက်လေ့လာပါ။
</p>
```

CSS -

```
.description {
    color: #526174;
    font-size: 18px;
}
```

Class တစ်ခုကို Element အများအပြားမှာ ပြန်လည်အသုံးပြုနိုင်ပါတယ်။

## ၁၀.၃ ID Selector

ID Selector ကို `#` နဲ့ စတင်ရေးသားပါတယ်။

HTML -

```
<h1 id="main-title">ကျွန်ုပ်၏ Website</h1>
```

CSS -

```
#main-title {
    color: darkblue;
    text-align: center;
}
```

ID ကို စာမျက်နှာတစ်ခုအတွင်း Element တစ်ခုကို သီးခြားသတ်မှတ်ဖို့ အသုံးပြုလေ့ရှိပါတယ်။ ပုံမှန် CSS Styling အများစုအတွက် Class ကို ဦးစားပေးသုံးနိုင်ပါတယ်။

## ၁၀.၄ Descendant Selector

Element တစ်ခုအတွင်းရှိ သက်ဆိုင်ရာ Element တွေကို ရွေးချယ်နိုင်ပါတယ်။

```
nav a {
    color: navy;
    text-decoration: none;
}
```

ဒီကုဒ်က `nav` အတွင်းရှိ `a` Element တွေကို ရွေးချယ်ပေးပါတယ်။

## ၁၀.၅ CSS Colors

CSS မှာ အရောင်သတ်မှတ်နိုင်တဲ့ နည်းလမ်းအမျိုးမျိုး ရှိပါတယ်။

```
h1 {
    color: blue;
}

p {
    color: #333333;
}

.card {
    background-color: rgb(240, 245, 250);
}
```

အသုံးများတဲ့ ပုံစံတွေက -

- Named Colors — `blue`, `white`, `black`
- HEX — `#1769AA`
- RGB — `rgb(23, 105, 170)`
- RGBA — `rgba(23, 105, 170, 0.5)`
- HSL — `hsl(205, 76%, 38%)`

Website ဒီဇိုင်းဆွဲရာမှာ အရောင်အနည်းငယ်ကို တသမတ်တည်း သုံးခြင်းက ပိုမိုသပ်ရပ်တဲ့ ပုံစံကို ရရှိစေပါတယ်။

## ၁၀.၆ Typography

Typography ဆိုတာ စာသားရဲ့ ပုံစံ၊ အရွယ်အစားနဲ့ ဖတ်ရှုရလွယ်ကူမှုတို့ကို စီမံသတ်မှတ်ခြင်း ဖြစ်ပါတယ်။

```
body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    line-height: 1.7;
    color: #17202D;
}

h1 {
    font-size: 36px;
    font-weight: 700;
}

p {
    text-align: left;
}
```

အသုံးများတဲ့ CSS Properties -

| Property          | ရည်ရွယ်ချက်           |
| ----------------- | --------------------- |
| `font-family`     | ဖောင့်အမျိုးအစား      |
| `font-size`       | စာလုံးအရွယ်အစား       |
| `font-weight`     | စာလုံးအထူ             |
| `line-height`     | စာကြောင်းကြားအကွာအဝေး |
| `text-align`      | စာသားညှိပုံ           |
| `text-decoration` | စာသားအလှဆင်မှု        |
| `letter-spacing`  | စာလုံးကြားအကွာအဝေး    |

မြန်မာစာ Website တွေအတွက် မြန်မာစာကို ကောင်းမွန်စွာ ပြသနိုင်တဲ့ ဖောင့်ကို ရွေးချယ်ပါ။

```
body {
    font-family: "Noto Sans Myanmar", "Myanmar Text", sans-serif;
}
```

သတ်မှတ်ထားတဲ့ ဖောင့်မရှိတဲ့ စက်တွေမှာ Fallback Font ကို အသုံးပြုနိုင်ပါတယ်။

# အခန်း ၁၁ — CSS Box Model၊ Margin နှင့် Padding

## ၁၁.၁ Box Model ဆိုတာဘာလဲ။

HTML Element တစ်ခုစီကို Box တစ်ခုလို စဉ်းစားနိုင်ပါတယ်။

Margin — Element အပြင်ဘက်

Border — အနားသတ်

Padding — အတွင်းအကွာအဝေး

Content

Box Model မှာ အဓိကအပိုင်း လေးခု ပါဝင်ပါတယ်။

1. Content — စာသား၊ ပုံနဲ့ အခြားအကြောင်းအရာ။
2. Padding — Content နဲ့ Border ကြားက အကွာအဝေး။
3. Border — Element ရဲ့ အနားသတ်။
4. Margin — Element အပြင်ဘက်က အကွာအဝေး။

## ၁၁.၂ Padding

```
.card {
    padding: 20px;
}
```

`padding: 20px;` ဆိုရင် Element ရဲ့ အပေါ်၊ ညာ၊ အောက်၊ ဘယ် ဘက်လေးဘက်စလုံးမှာ 20px အတွင်းအကွာအဝေး ရှိလာပါတယ်။

## ၁၁.၃ Margin

```
.card {
    margin: 20px;
}
```

Margin က Element ရဲ့ အပြင်ဘက်အကွာအဝေး ဖြစ်ပါတယ်။

Element တစ်ခုကို အလျားလိုက် အလယ်မှာထားဖို့ -

```
.container {
    max-width: 1100px;
    margin: 0 auto;
}
```

ဒီကုဒ်မှာ `margin: 0 auto;` က အပေါ်နဲ့အောက် Margin ကို 0 သတ်မှတ်ပြီး ဘယ်နဲ့ညာ Margin ကို အလိုအလျောက် ညှိပေးပါတယ်။

## ၁၁.၄ Border

```
.card {
    border: 1px solid #DCE3EC;
}
```

ဒီမှာ -

- `1px` — Border အထူ။
- `solid` — Border ပုံစံ။
- `#DCE3EC` — Border အရောင်။

## ၁၁.၅ Box Sizing

CSS Layout ကို စီမံရာမှာ အောက်ပါ Rule ကို အသုံးပြုလေ့ရှိပါတယ်။

```
*,
*::before,
*::after {
    box-sizing: border-box;
}
```

ဒီနည်းက `width` နဲ့ `height` တွက်ချက်ရာမှာ Padding နဲ့ Border ကို သတ်မှတ်ထားတဲ့ အရွယ်အစားအတွင်း ထည့်တွက်စေပါတယ်။ ထို့ကြောင့် Layout ကို ခန့်မှန်းရ ပိုမိုလွယ်ကူစေပါတယ်။

# အခန်း ၁၂ — Borders၊ Backgrounds နှင့် Shadows

## ၁၂.၁ Border Radius

Element ရဲ့ ထောင့်တွေကို ဝိုင်းစေဖို့ `border-radius` ကို သုံးပါတယ်။

```
.card {
    border-radius: 12px;
}
```

## ၁၂.၂ Background Color

```
body {
    background-color: #F4F7FB;
}

.card {
    background-color: white;
}
```

## ၁၂.၃ Box Shadow

Box Shadow က Element တစ်ခုကို အရိပ်ထည့်ပေးပါတယ်။

```
.card {
    box-shadow: 0 8px 24px rgba(20, 35, 60, 0.08);
}
```

အရိပ်ကို အလွန်ပြင်းထန်စွာ မသုံးဘဲ ဒီဇိုင်းနဲ့ လိုက်ဖက်အောင် သုံးသင့်ပါတယ်။

## ၁၂.၄ Gradient

Gradient ဆိုတာ အရောင်တစ်ရောင်မှ နောက်တစ်ရောင်သို့ ချောမွေ့စွာ ပြောင်းလဲသွားတဲ့ နောက်ခံပုံစံ ဖြစ်ပါတယ်။

```
.hero {
    background: linear-gradient(
        135deg,
        #102A43,
        #1769AA
    );

    color: white;
    padding: 48px 24px;
    border-radius: 16px;
}
```

ဒီလို Gradient ကို Hero Section၊ Banner နဲ့ Card တွေမှာ အသုံးပြုနိုင်ပါတယ်။

## ၁၂.၅ ပြည့်စုံသော Card Design

```
<div class="card">
    <h2>HTML အခြေခံ</h2>

    <p>
        HTML ကို အသုံးပြုပြီး Website ရဲ့
        ဖွဲ့စည်းပုံကို တည်ဆောက်နိုင်ပါတယ်။
    </p>

    <a href="#">သင်ခန်းစာ ဖတ်ရန်</a>
</div>
```

```
.card {
    max-width: 350px;
    padding: 24px;

    background-color: white;
    border: 1px solid #DCE3EC;
    border-radius: 14px;

    box-shadow: 0 8px 24px rgba(20, 35, 60, 0.08);
}

.card h2 {
    color: #1769AA;
}

.card p {
    color: #526174;
    line-height: 1.8;
}

.card a {
    color: #1769AA;
    text-decoration: none;
    font-weight: 700;
}
```

ဒီဥပမာက HTML နဲ့ CSS ကို ပေါင်းစပ်ပြီး ရိုးရှင်းတဲ့ သင်ခန်းစာ Card တစ်ခု တည်ဆောက်ထားတာ ဖြစ်ပါတယ်။

# အခန်း ၁၃ — Display၊ Flexbox နှင့် Layout

## ၁၃.၁ Display Property

`display` က HTML Element တွေကို Browser မှာ ဘယ်လိုပြသရမလဲဆိုတာ သတ်မှတ်ပေးပါတယ်။

အသုံးများတဲ့ Value တွေက -

- `block`
- `inline`
- `inline-block`
- `flex`
- `grid`
- `none`

ဥပမာ -

```
div {
    display: block;
}

span {
    display: inline;
}
```

`block` Element တွေဟာ ပုံမှန်အားဖြင့် လိုအပ်သလောက် အကျယ်ကို ယူပြီး စာကြောင်းအသစ်မှ စတင်ပါတယ်။

`inline` Element တွေကတော့ စာသားနဲ့အတူ တစ်ကြောင်းတည်းမှာ ရှိနေနိုင်ပါတယ်။

## ၁၃.၂ Flexbox ဆိုတာဘာလဲ။

Flexbox က Element တွေကို အလျားလိုက် သို့မဟုတ် ဒေါင်လိုက် စီစဉ်ဖို့ အသုံးပြုတဲ့ CSS Layout နည်းလမ်းတစ်ခု ဖြစ်ပါတယ်။

ဥပမာ Navigation Bar တစ်ခု တည်ဆောက်ကြည့်ရအောင်။

HTML -

```
<header class="navbar">
    <h2 class="logo">My Website</h2>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
</header>
```

CSS -

```
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
    padding: 20px;
}

nav {
    display: flex;
    gap: 16px;
}

nav a {
    text-decoration: none;
}
```

## ၁၃.၃ Flexbox Properties

| Property          | အသုံးပြုပုံ                                        |
| ----------------- | -------------------------------------------------- |
| `display: flex`   | Flex Container ဖန်တီးခြင်း                         |
| `flex-direction`  | Element များ စီစဉ်မည့် ဦးတည်ချက်                   |
| `justify-content` | Main Axis တစ်လျှောက် ချိန်ညှိခြင်း                 |
| `align-items`     | Cross Axis တစ်လျှောက် ချိန်ညှိခြင်း                |
| `gap`             | Element များကြား အကွာအဝေး                          |
| `flex-wrap`       | နေရာမလုံလောက်လျှင် နောက်တစ်ကြောင်းသို့ ဆင်းစေခြင်း |

## ၁၃.၄ Element များကို အလယ်မှာထားခြင်း

```
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 300px;
}
```

ဒီကုဒ်က Flex Container အတွင်းရှိ Element တွေကို အလျားလိုက်နဲ့ ဒေါင်လိုက် အလယ်မှာ ချိန်ညှိပေးပါတယ်။

## ၁၃.၅ Card များကို Flexbox ဖြင့် စီစဉ်ခြင်း

```
<div class="cards">
    <div class="card">HTML</div>
    <div class="card">CSS</div>
    <div class="card">JavaScript</div>
</div>
```

```
.cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    flex: 1 1 220px;
    padding: 24px;
    background-color: white;
    border-radius: 12px;
}
```

`flex-wrap: wrap` ကြောင့် နေရာမလုံလောက်တဲ့အခါ Card တွေက နောက်တစ်ကြောင်းသို့ ဆင်းသွားနိုင်ပါတယ်။

# အခန်း ၁၄ — CSS Grid နှင့် Position

## ၁၄.၁ CSS Grid ဆိုတာဘာလဲ။

CSS Grid ဟာ Row နဲ့ Column နှစ်မျိုးလုံးကို စီမံနိုင်တဲ့ Layout System ဖြစ်ပါတယ်။

Card Grid၊ Product Grid နဲ့ Dashboard Layout တွေ တည်ဆောက်ရာမှာ အသုံးဝင်ပါတယ်။

```
<div class="product-grid">
    <div class="product">Product 1</div>
    <div class="product">Product 2</div>
    <div class="product">Product 3</div>
</div>
```

```
.product-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.product {
    padding: 24px;
    background-color: #EAF4FF;
    border-radius: 12px;
}
```

`grid-template-columns: repeat(3, 1fr);` ဆိုတာ Column သုံးခုကို တူညီတဲ့ အကျယ်နဲ့ ဖန်တီးပေးတာ ဖြစ်ပါတယ်။

## ၁၄.၂ Responsive Grid

Column အရေအတွက်ကို အလိုအလျောက် ချိန်ညှိချင်ရင် -

```
.product-grid {
    display: grid;

    grid-template-columns: repeat(
        auto-fit,
        minmax(220px, 1fr)
    );

    gap: 20px;
}
```

ဒီပုံစံမှာ Browser ရဲ့ ရရှိနိုင်တဲ့ အကျယ်ပေါ်မူတည်ပြီး Card တွေရဲ့ Column အရေအတွက် ပြောင်းလဲနိုင်ပါတယ်။

## ၁၄.၃ Position Property

CSS `position` က Element တွေရဲ့ နေရာချထားပုံကို သတ်မှတ်ပေးပါတယ်။

| Value      | ရှင်းလင်းချက်                                            |
| ---------- | -------------------------------------------------------- |
| `static`   | ပုံမှန် Document Flow                                    |
| `relative` | မူလနေရာကို အခြေခံပြီး နေရာချနိုင်ခြင်း                   |
| `absolute` | အနီးဆုံး Positioned Ancestor ကို အခြေခံခြင်း             |
| `fixed`    | Viewport နဲ့ ဆက်စပ်ပြီး နေရာတည်မြဲခြင်း                  |
| `sticky`   | Scroll လုပ်ရာတွင် သတ်မှတ်ထားသော အနေအထား၌ ကပ်နေနိုင်ခြင်း |

ဥပမာ -

```
<div class="product-card">
    <span class="badge">NEW</span>

    <h2>Product Name</h2>
</div>
```

```
.product-card {
    position: relative;
    padding: 30px;
    background-color: #F4F7FB;
}

.badge {
    position: absolute;
    top: 10px;
    right: 10px;

    background-color: #1769AA;
    color: white;
    padding: 4px 10px;
    border-radius: 6px;
}
```

ဒီဥပမာမှာ `badge` ကို `product-card` ရဲ့ ညာဘက်အပေါ်ထောင့်မှာ ထားပါတယ်။

# အခန်း ၁၅ — Responsive Design

## ၁၅.၁ Responsive Design ဆိုတာဘာလဲ။

Responsive Design ဆိုတာ Computer၊ Tablet နဲ့ Mobile ဖုန်းတွေလို မျက်နှာပြင်အရွယ်အစား မတူညီတဲ့ စက်တွေမှာ Website ကို မှန်ကန်စွာ ပြသနိုင်အောင် ဒီဇိုင်းတည်ဆောက်ခြင်း ဖြစ်ပါတယ်။

Website တစ်ခုကို Desktop မှာပဲ လှပနေအောင် ပြုလုပ်ထားလို့ မလုံလောက်ပါဘူး။ Mobile ဖုန်းမှာလည်း စာသားဖတ်ရှုရလွယ်ကူပြီး Button တွေကို နှိပ်ရလွယ်ကူဖို့ လိုအပ်ပါတယ်။

## ၁၅.၂ Viewport Meta Tag

HTML ရဲ့ `head` အပိုင်းမှာ ဒီကုဒ်ကို ထည့်ပါ။

```
<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
>
```

ဒီသတ်မှတ်ချက်က Mobile Browser တွေမှာ Website ရဲ့ Layout ကို မျက်နှာပြင်အကျယ်နဲ့ ကိုက်ညီစေဖို့ အရေးကြီးပါတယ်။

## ၁၅.၃ Flexible Images

```
img {
    max-width: 100%;
    height: auto;
}
```

ဒီကုဒ်က ပုံကို Container အကျယ်ထက် ကျော်လွန်မသွားစေဘဲ မူလအချိုးအစားကို ထိန်းထားပေးပါတယ်။

## ၁၅.၄ Media Queries

Media Query ကို မျက်နှာပြင်အကျယ် သို့မဟုတ် အခြားအခြေအနေတွေပေါ် မူတည်ပြီး CSS ပြောင်းလဲဖို့ အသုံးပြုပါတယ်။

```
.cards {
    display: grid;
    grid-template-columns: 1fr;
    gap: 16px;
}

@media (min-width: 700px) {
    .cards {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (min-width: 1000px) {
    .cards {
        grid-template-columns: repeat(3, 1fr);
    }
}
```

ဒီဥပမာမှာ -

- ပုံမှန်အားဖြင့် Column တစ်ခု။
- 700px နဲ့အထက်မှာ Column နှစ်ခု။
- 1000px နဲ့အထက်မှာ Column သုံးခု။

ဒါကြောင့် မျက်နှာပြင်အကျယ်အလိုက် Layout ပြောင်းလဲနိုင်ပါတယ်။

## ၁၅.၅ Mobile-First Design

Mobile-First ဆိုတာ Mobile မျက်နှာပြင်အတွက် အရင်ဆုံး CSS ရေးပြီး နောက်ပိုင်းမှာ မျက်နှာပြင်ကြီးတွေအတွက် Layout ကို တိုးချဲ့သတ်မှတ်တဲ့ နည်းလမ်း ဖြစ်ပါတယ်။

```
.container {
    width: min(100% - 32px, 1100px);
    margin-inline: auto;
}

.grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 16px;
}

@media (min-width: 768px) {
    .grid {
        grid-template-columns: repeat(2, 1fr);
    }
}
```

Responsive Design ကို စမ်းသပ်တဲ့အခါ Browser ရဲ့ Developer Tools ကို အသုံးပြုပြီး Mobile၊ Tablet နဲ့ Desktop အရွယ်အစားတွေကို စစ်ဆေးပါ။

# အခန်း ၁၆ — Pseudo-classes နှင့် Transitions

## ၁၆.၁ Hover Effect

အသုံးပြုသူက Mouse Pointer ကို Element ပေါ်တင်တဲ့အခါ ပုံစံပြောင်းစေဖို့ `:hover` ကို အသုံးပြုပါတယ်။

```
<button class="button">စတင်လေ့လာရန်</button>
```

```
.button {
    padding: 12px 20px;
    background-color: #1769AA;
    color: white;
    border: none;
    border-radius: 8px;
    cursor: pointer;
}

.button:hover {
    background-color: #105D9D;
}
```

## ၁၆.၂ Transition

Transition က CSS Property တစ်ခုရဲ့ တန်ဖိုးပြောင်းလဲမှုကို ချောမွေ့စွာ ပြသပေးပါတယ်။

```
.button {
    background-color: #1769AA;
    transition: background-color 0.2s ease;
}

.button:hover {
    background-color: #105D9D;
}
```

## ၁၆.၃ Focus State

Keyboard အသုံးပြုသူတွေ အတွက်လည်း Element တစ်ခုကို ရွေးချယ်ထားကြောင်း မြင်သာစေဖို့ `:focus-visible` ကို အသုံးပြုနိုင်ပါတယ်။

```
.button:focus-visible {
    outline: 3px solid orange;
    outline-offset: 3px;
}
```

Hover Effect တစ်ခုတည်းကိုသာ မမှီခိုပါနဲ့။ Touch Screen နဲ့ Keyboard အသုံးပြုသူတွေအတွက်လည်း Website ကို အသုံးပြုရလွယ်ကူစေဖို့ လိုအပ်ပါတယ်။

# အခန်း ၁၇ — လက်တွေ့ Project: ကိုယ်ရေးမိတ်ဆက် Website တည်ဆောက်ခြင်း

ဒီအခန်းမှာ အရင်သင်ခန်းစာတွေက HTML နဲ့ CSS အခြေခံတွေကို အသုံးပြုပြီး ကိုယ်ပိုင် Portfolio Website တစ်ခု တည်ဆောက်ပါမယ်။

## ၁၇.၁ Project Folder

```
my-portfolio/
├── index.html
└── style.css
```

## ၁၇.၂ HTML Code

`index.html` ဖိုင်ထဲမှာ အောက်ပါကုဒ်ကို ရေးပါ။

```
<!DOCTYPE html>
<html lang="my">
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <title>ကျွန်ုပ်၏ Portfolio</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="navbar">
        <a class="logo" href="#">My Portfolio</a>

        <nav aria-label="အဓိက လမ်းညွှန်">
            <a href="#about">မိတ်ဆက်</a>
            <a href="#skills">ကျွမ်းကျင်မှု</a>
            <a href="#contact">ဆက်သွယ်ရန်</a>
        </nav>
    </header>

    <main class="container">
        <section class="hero" id="about">
            <p class="eyebrow">မင်္ဂလာပါ။ ကျွန်ုပ်က</p>

            <h1>Web Developer တစ်ယောက် ဖြစ်လာဖို့ လေ့လာနေပါတယ်။</h1>

            <p>
                HTML နဲ့ CSS ကို အသုံးပြုပြီး
                လှပပြီး အသုံးဝင်တဲ့ Website တွေ
                တည်ဆောက်ဖို့ ကြိုးစားနေပါတယ်။
            </p>

            <a class="button" href="#contact">
                ဆက်သွယ်ရန်
            </a>
        </section>

        <section id="skills">
            <h2>ကျွန်ုပ်၏ ကျွမ်းကျင်မှုများ</h2>

            <div class="skill-grid">
                <article class="card">
                    <h3>HTML</h3>
                    <p>Website ရဲ့ ဖွဲ့စည်းပုံကို တည်ဆောက်ခြင်း။</p>
                </article>

                <article class="card">
                    <h3>CSS</h3>
                    <p>Website ရဲ့ ဒီဇိုင်းနဲ့ Layout ကို ဖန်တီးခြင်း။</p>
                </article>

                <article class="card">
                    <h3>Learning</h3>
                    <p>နေ့စဉ် လေ့လာပြီး Project များ တည်ဆောက်ခြင်း။</p>
                </article>
            </div>
        </section>

        <section class="contact" id="contact">
            <h2>ဆက်သွယ်ရန်</h2>

            <p>
                Email:
                <a href="mailto:hello@example.com">
                    hello@example.com
                </a>
            </p>
        </section>
    </main>

    <footer class="footer">
        <p>© 2026 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
```

## ၁၇.၃ CSS Code

`style.css` ဖိုင်ထဲမှာ အောက်ပါကုဒ်ကို ရေးပါ။

```
*,
*::before,
*::after {
    box-sizing: border-box;
}

:root {
    --primary: #1769AA;
    --dark: #17202D;
    --muted: #586779;
    --background: #F4F7FB;
    --white: #FFFFFF;
    --border: #DCE3EC;
}

body {
    margin: 0;
    font-family: "Noto Sans Myanmar", "Myanmar Text", sans-serif;
    color: var(--dark);
    background-color: var(--background);
    line-height: 1.8;
}

a {
    color: var(--primary);
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;

    padding: 18px max(20px, calc((100% - 1100px) / 2));

    background-color: var(--white);
    border-bottom: 1px solid var(--border);
}

.logo {
    font-weight: 700;
    text-decoration: none;
}

nav {
    display: flex;
    flex-wrap: wrap;
    gap: 16px;
}

nav a {
    text-decoration: none;
}

.container {
    width: min(100% - 32px, 1100px);
    margin: 0 auto;
}

.hero {
    margin: 32px 0;
    padding: clamp(28px, 6vw, 64px);

    color: white;
    background: linear-gradient(135deg, #102A43, #1769AA);
    border-radius: 20px;
}

.hero h1 {
    max-width: 760px;
    font-size: clamp(1.8rem, 4vw, 3.2rem);
    line-height: 1.5;
}

.hero p {
    max-width: 680px;
}

.eyebrow {
    color: #B9DFFF;
}

.button {
    display: inline-block;
    margin-top: 12px;
    padding: 10px 18px;

    color: #102A43;
    background-color: white;

    border-radius: 8px;
    text-decoration: none;
    font-weight: 700;
}

.skill-grid {
    display: grid;
    grid-template-columns: repeat(
        auto-fit,
        minmax(220px, 1fr)
    );
    gap: 18px;
}

.card,
.contact {
    padding: 22px;
    background-color: var(--white);
    border: 1px solid var(--border);
    border-radius: 14px;
}

.card p,
.contact p {
    color: var(--muted);
}

.footer {
    margin-top: 40px;
    padding: 24px 16px;

    text-align: center;
    color: var(--muted);
    background-color: var(--white);
    border-top: 1px solid var(--border);
}

a:focus-visible {
    outline: 3px solid orange;
    outline-offset: 3px;
}

@media (max-width: 650px) {
    .navbar {
        align-items: flex-start;
        flex-direction: column;
    }
}
```

## ၁၇.၄ Project မှာ ဘာတွေ သင်ယူခဲ့သလဲ။

ဒီ Project ထဲမှာ အောက်ပါအချက်တွေကို လက်တွေ့အသုံးပြုထားပါတယ်။

- Semantic HTML — `header`၊ `nav`၊ `main`၊ `section`၊ `article` နှင့် `footer`
- CSS Variables — အရောင်တွေကို ပြန်လည်အသုံးပြုခြင်း
- Flexbox — Navigation Bar တည်ဆောက်ခြင်း
- CSS Grid — Skill Card များ စီစဉ်ခြင်း
- Responsive Design — မျက်နှာပြင်အကျယ်အလိုက် Layout ပြောင်းလဲခြင်း
- Accessibility — Keyboard Focus ကို မြင်သာစေခြင်း

### ကိုယ်တိုင် ပြင်ဆင်ကြည့်ပါ

1. Website ရဲ့ အရောင်တွေကို ပြောင်းပါ။
2. ကိုယ့်ဓာတ်ပုံတစ်ပုံ ထည့်ပါ။
3. Project တွေအတွက် Card သုံးခု ထပ်ထည့်ပါ။
4. ကိုယ့်ရဲ့ အမှန်တကယ် ဆက်သွယ်ရန် အချက်အလက်ကို ထည့်ပါ။
5. Mobile ဖုန်းမှာ Website ကို စမ်းသပ်ပါ။

# အခန်း ၁၈ — အမှားရှာဖွေခြင်းနှင့် Best Practices

## ၁၈.၁ CSS မအလုပ်လုပ်တဲ့အခါ

အများဆုံးတွေ့ရတဲ့ အမှားတွေက -

၁။ CSS File လမ်းကြောင်းမှားခြင်း

```
<link rel="stylesheet" href="style.css">
```

HTML နဲ့ CSS ဖိုင်ဟာ Folder တစ်ခုတည်းမှာ ရှိတယ်ဆိုရင် ဒီလမ်းကြောင်းကို သုံးနိုင်ပါတယ်။

၂။ Class Selector ရေးပုံမှားခြင်း

HTML -

```
<p class="description">Hello World</p>
```

မှန်ကန်သော CSS -

```
.description {
    color: blue;
}
```

Class Selector ရဲ့ ရှေ့မှာ `.` ထည့်ဖို့ မမေ့ပါနဲ့။

၃။ CSS Property ရေးပုံမှားခြင်း

မှားယွင်းသော Code -

```
h1 {
    color blue
}
```

မှန်ကန်သော Code -

```
h1 {
    color: blue;
}
```

Property နဲ့ Value ကြားမှာ `:` ထည့်ပြီး Declaration အဆုံးမှာ `;` သုံးပါ။

## ၁၈.၂ ပုံ မပေါ်တဲ့အခါ

```
<img src="images/profile.jpg" alt="ကိုယ်ရေးပုံ">
```

စစ်ဆေးရန် -

- ပုံဖိုင် တကယ်ရှိသလား။
- Folder အမည် မှန်သလား။
- ဖိုင်အမည်နဲ့ Extension မှန်သလား။
- စာလုံးအကြီးအသေး ကိုက်ညီသလား။
- ပုံရဲ့ Path မှန်သလား။

## ၁၈.၃ Browser Developer Tools

Chrome သို့မဟုတ် Edge မှာ `F12` နှိပ်ပြီး Developer Tools ကို ဖွင့်နိုင်ပါတယ်။

အသုံးဝင်တဲ့ Tab တွေက -

- Elements — HTML ဖွဲ့စည်းပုံကို စစ်ဆေးခြင်း။
- Styles — CSS Rule တွေကို ကြည့်ရှုခြင်းနှင့် စမ်းသပ်ပြင်ဆင်ခြင်း။
- Console — Error Message များကို စစ်ဆေးခြင်း။
- Network — CSS၊ ပုံနဲ့ အခြားဖိုင်တွေ တင်သွင်းရာမှာ ပြဿနာရှိမရှိ စစ်ဆေးခြင်း။

## ၁၈.၄ Professional Code ရေးသားမှု

ကုဒ်ကို အလုပ်အကိုင်အဆင့်အထိ တိုးတက်စေဖို့ -

- အဓိပ္ပာယ်ရှိတဲ့ Class အမည်တွေ သုံးပါ။
- HTML နဲ့ CSS ကို သီးခြားထားပါ။
- ထပ်နေတဲ့ CSS Rule တွေကို လျှော့ချပါ။
- Spacing နဲ့ Color တွေကို တသမတ်တည်း သုံးပါ။
- Responsive Design ကို စမ်းသပ်ပါ။
- Accessibility ကို ဂရုစိုက်ပါ။
- Git နဲ့ GitHub ကို အသုံးပြုပြီး Code Version တွေ သိမ်းဆည်းပါ။

# အခန်း ၁၉ — လေ့ကျင့်ခန်းများ

## လေ့ကျင့်ခန်း ၁ — HTML အခြေခံ

အောက်ပါမေးခွန်းတွေကို ကိုယ်တိုင် ဖြေကြည့်ပါ။

1. HTML ရဲ့ အရှည်ကောက်က ဘာလဲ။
2. CSS ရဲ့ အဓိကတာဝန်က ဘာလဲ။
3. စာပိုဒ်တစ်ခု ဖန်တီးဖို့ ဘယ် Tag ကို သုံးသလဲ။
4. Heading အဆင့် ဘယ်နှစ်ဆင့် ရှိသလဲ။
5. ပုံထည့်ဖို့ ဘယ် Element ကို သုံးသလဲ။
6. Link ဖန်တီးဖို့ ဘယ် Element ကို သုံးသလဲ။
7. Ordered List နဲ့ Unordered List က ဘာကွာသလဲ။
8. Form ထဲမှာ `required` က ဘာလုပ်ပေးသလဲ။

## လေ့ကျင့်ခန်း ၂ — CSS အခြေခံ

1. CSS Rule တစ်ခုရဲ့ အဓိကအစိတ်အပိုင်းတွေက ဘာတွေလဲ။
2. Class Selector ကို ဘယ်သင်္ကေတနဲ့ စရေးသလဲ။
3. ID Selector ကို ဘယ်သင်္ကေတနဲ့ စရေးသလဲ။
4. Margin နဲ့ Padding ဘာကွာသလဲ။
5. Flexbox ကို ဘာအတွက် အသုံးပြုသလဲ။
6. Grid နဲ့ Flexbox ဘယ်လိုကွာသလဲ။
7. Media Query က ဘာလုပ်ပေးသလဲ။
8. Responsive Design ဆိုတာ ဘာလဲ။

## လေ့ကျင့်ခန်း ၃ — Mini Project

HTML နဲ့ CSS ကို အသုံးပြုပြီး ကိုယ်ပိုင် Profile Website တစ်ခု တည်ဆောက်ပါ။

ပါဝင်ရမယ့် အချက်တွေ -

- Navigation Bar
- ကိုယ်ရေးမိတ်ဆက်
- Profile Photo
- ကျွမ်းကျင်မှု အနည်းဆုံး သုံးခု
- Project Card အနည်းဆုံး နှစ်ခု
- Contact Section
- Footer
- Responsive Layout

## အဖြေညွှန်း

1. HTML — HyperText Markup Language။
2. CSS — Cascading Style Sheets။
3. စာပိုဒ်အတွက် `<p>`။
4. Heading အဆင့် ခြောက်ဆင့်၊ `<h1>` မှ `<h6>`။
5. ပုံအတွက် `<img>`။
6. Link အတွက် `<a>`။
7. `<ol>` က အစဉ်လိုက်စာရင်း၊ `<ul>` က ပုံမှန်စာရင်း။
8. `required` က Form Field ကို မဖြစ်မနေ ဖြည့်ရန် သတ်မှတ်ပေးသည်။
9. Class Selector — `.name`။
10. ID Selector — `#name`။
11. Margin — Element အပြင်ဘက်အကွာအဝေး။
12. Padding — Element အတွင်းဘက်အကွာအဝေး။
13. Flexbox — တစ်ဘက်တည်းအတိုင်း Layout စီစဉ်ရန် အထူးအသုံးဝင်သည်။
14. Grid — Row နဲ့ Column နှစ်ဘက်အတိုင်း Layout စီစဉ်ရန် အသုံးဝင်သည်။
15. Media Query — သတ်မှတ်ထားတဲ့ အခြေအနေအလိုက် CSS Rule တွေ အသုံးချစေသည်။

# အခန်း ၂၀ — နောက်ထပ်လေ့လာရန် လမ်းညွှန်

HTML နဲ့ CSS အခြေခံတွေကို နားလည်လာပြီဆိုရင် အောက်ပါအစီအစဉ်အတိုင်း ဆက်လက်လေ့လာနိုင်ပါတယ်။

အဆင့် ၁ — HTML

Tags၊ Attributes၊ Forms၊ Tables၊ Semantic HTML

စာမျက်နှာရဲ့ ဖွဲ့စည်းပုံကို ကိုယ်တိုင် ရေးသားနိုင်အောင် လေ့ကျင့်ပါ။

အဆင့် ၂ — CSS

Selectors၊ Box Model၊ Flexbox၊ Grid၊ Responsive Design

လှပပြီး မျက်နှာပြင်အရွယ်အစားအလိုက် လိုက်လျောညီထွေရှိတဲ့ Website တွေ ဖန်တီးပါ။

အဆင့် ၃ — Git နှင့် GitHub

Code Version တွေကို စနစ်တကျ သိမ်းဆည်းပြီး ကိုယ်ပိုင် Project တွေကို ပြသတတ်အောင် လေ့လာပါ။

အဆင့် ၄ — JavaScript

Website ကို Interactive ဖြစ်အောင် ပြုလုပ်ခြင်း၊ Form Validation နဲ့ Dynamic Content တို့ကို လေ့လာပါ။

အဆင့် ၅ — Frontend Frameworks

HTML၊ CSS နဲ့ JavaScript အခြေခံခိုင်မာလာတဲ့အခါ React သို့မဟုတ် အခြား Frontend Framework တွေကို ဆက်လက်လေ့လာပါ။

## အခမဲ့လေ့လာနိုင်သော အရင်းအမြစ်များ

- MDN Web Docs — [HTML, CSS နှင့် Web Development လမ်းညွှန်](https://developer.mozilla.org/en-US/docs/Learn_web_development?utm_source=chatgpt.com)
- W3C — [Web Accessibility လမ်းညွှန်](https://www.w3.org/WAI/?utm_source=chatgpt.com)
- WHATWG — [HTML Standard](https://html.spec.whatwg.org/?utm_source=chatgpt.com)

## နိဂုံးချုပ်

HTML နဲ့ CSS ကို သင်ယူတဲ့အခါ စာဖတ်ရုံနဲ့ မလုံလောက်ပါဘူး။ ကိုယ်တိုင် Code ရေးပါ၊ Browser မှာ စမ်းသပ်ပါ၊ အမှားတွေ့ရင် အကြောင်းရင်းကို ရှာဖွေပြီး ပြင်ဆင်ပါ။

ပထမဆုံး Website က ရိုးရှင်းနေနိုင်ပါတယ်။ ဒါပေမဲ့ Project တစ်ခုချင်းစီကို ကိုယ်တိုင် တည်ဆောက်သွားရင် ပိုမိုရှုပ်ထွေးတဲ့ Website တွေကိုလည်း တဖြည်းဖြည်း ဖန်တီးနိုင်လာပါလိမ့်မယ်။

မှတ်ထားရမယ့် အချက်တစ်ခုက — Code ကို အလွတ်ကျက်တာထက် ဘာကြောင့် ဒီလိုရေးရသလဲဆိုတာ နားလည်ဖို့ ပိုအရေးကြီးပါတယ်။
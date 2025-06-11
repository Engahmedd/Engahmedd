<div align="center" width="50">

<img src="https://github.com/SP-XD/SP-XD/blob/main/images/hellocoders_rounded.gif?raw=true" alt="Hello Coders" width="60%"/> <br>
<img src="https://github.com/SP-XD/SP-XD/blob/main/images/dev-working_rounded.gif?raw=true" alt="Workspace"  width="40%"/><br> 

<details>
<p><strong><summary>🎧 Busy coding & Vibing to:</summary></strong></p>

[![Spotify](https://spotify-readme.sp-xd.vercel.app/api/spotify)](https://open.spotify.com) <br>

</details>

![Totals Hits](https://komarev.com/ghpvc/?username=Ahmed-Sameh&style=flat&color=orange&label=PROFILE+VIEWS)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FAhmed-Sameh&count_bg=%2379C83D&title_bg=%23555555&icon=mediafire.svg&icon_color=%23E7E7E7&title=HITS&edge_flat=false)

</div>

---

## 👨‍💻 عني

- 👋 اسمي **أحمد سامح**
- 💻 أنا مبرمج **مواقع ويب**
- 🌐 عندي خبرة في **HTML**, **CSS**, و **C++**
- 🚀 قريبًا هبدأ أتعلم **JavaScript**
- 🧠 بحب البرمجة والتطوير المستمر في المجال

---

## ⚒️ الأدوات والتقنيات

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=flat&logo=javascript&logoColor=F7DF1E)
![Git](https://img.shields.io/badge/GIT-E44C30?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=flat&logo=visual%20studio%20code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## 🚀 مثال برمجي بسيط

```cpp
## 🚀 مثال برمجي بسيط - HTML Form

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body>
    <form action="index.php" method="post" enctype="multipart/form-data">
      <label for="username">username</label>
      <input type="text" id="username" placeholder="enter your name" minlength="3" maxlength="20" required /><br />

      <label for="password">password</label>
      <input type="password" id="password" placeholder="enter your password" minlength="7" maxlength="20" required /><br />

      <label for="email">email</label>
      <input type="email" id="email" placeholder="bla bla bla @gmail.com" minlength="7" maxlength="35" required /><br />

      <label for="phone">phone</label>
      <input type="phone" id="phone" placeholder="12345678900" pattern="[0-9]{3}[0-9]{3}[0-9]{5}" required /><br />

      <label for="birthday">birthday</label>
      <input type="date" id="birthday" required /><br />

      <label for="quantity">quantity</label>
      <input type="number" id="quantity" min="0" max="99" required /><br />

      <label for="title">title:</label><br />
      <label for="Mr.">Mr.</label>
      <input type="radio" id="Mr." value="Mr." name="title" />
      <label for="Ms.">Ms.</label>
      <input type="radio" id="Ms." value="Ms." name="title" />
      <label for="Dr.">Dr.</label>
      <input type="radio" id="Dr." value="Dr." name="title" />
      <label for="Eng.">Eng.</label>
      <input type="radio" id="Eng." value="Eng." name="title" /><br />

      <label for="payment">payment</label><br />
      <select id="payment">
        <option value="visa">visa</option>
        <option value="mastercard">mastercard</option>
        <option value="giftcard">giftcard</option>
        <option value="Cash">Cash</option>
      </select><br />

      <label for="subscribe">subscribe:</label>
      <input type="checkbox" id="subscribe" /><br />

      <label for="comment">comment:</label><br />
      <textarea id="comment" rows="3" cols="150"></textarea><br />

      <label for="file">file:</label>
      <input type="file" id="file" accept="image/png, image/jpeg" /><br />

      <input type="reset" /><br />
      <input type="submit" /><br />
    </form>
  </body>
</html>

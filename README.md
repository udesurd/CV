# Rostislav Dmitriev
JavaScript developer based in Belarus.<br>

[Email](mailto:udesurd@gmail.com) / [GitHub](https://github.com/udesurd/) / [Codewars](https://www.codewars.com/users/udesu) / [Phone](tel:+375(29)6437427)

## 👨🏻‍💻 About Me

*Learning javascript is an indispensable part of web development and not only, it is used in various areas of IT. 
Being my favorite language, it's also an essential part of frontend development.
My goal is to study in depth both the language and the profession in order to create services that can make life easier for others.
My experience with this language started 1 year ago. I participated in freelance development and creating personal projects.*
<br><br>

## 🦤 Skills

**My skills include:**
- HTML 
- CSS (Bootstrap, Preprocessor SCSS, BEM methodology)
- JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+,DOM)
- C#

**Frameworks:**
- React / Redux.
- .Net 6

**Databases:**
- MsSQL
- MongoDB
<br><br>

## 🪬 Code Example:
[GitHub User Searcher](https://udesurd.github.io/github_user_searcher/)
```js
document.querySelector('.btn').onclick = function (e) {
    e.preventDefault();
    let login = document.querySelector('.input').value;
    let resulltVision = document.querySelector('.form__result')
    resulltVision.classList.add('active')
    fetch("https://api.github.com/users/"+ login)
    .then((result) => result.json())
    .then((data) => {
        document.querySelector('.form__result').innerHTML = `
        <div class="result__wrapper">
        <a href="${data.avatar_url} class="bg" "><img src="${data.avatar_url}" class="bg" alt="" class="img"/></a>
        <div class="result__info">
        <div class="info"
        <p class="bg"><a target="_blank" href="https://github.com/${data.login}" class="bg"> ${data.login}</a></p>
        <p class="bg">Followers: ${data.followers}</p>
        </div>
        <div class="bio"
        <div><p class="bg">Name: ${data.name}</p>
        <p class="bg">Bio: ${data.bio}</p>
        <p class="bg">${data.created_at}</p></div>
        <div class="location bg"
        <div><p class="bg">Company: ${data.company}</p>
        <p class="bg">${data.location}</p></div>
        </div>
        </div>
        </div>
        </div>
   `
    })
}
```
<br><br>

## 👨🏻‍🎓 Education

**Bachelor, Polatsk State University,Navapolatsk**<br>
3D Technology _(2017 - 2022)_ <br>

## 📚 Languages

-English [EPAM English test result](https://examinator.epam.com/Main/PersonalAssignments/438259): **A2+** <br>
-Russian

<br>
<br>

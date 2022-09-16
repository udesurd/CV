# Rostislav Dmitriev
JavaScript developer based in Belarus.<br>

[Email](mailto:udesurd@gmail.com) / [GitHub](https://github.com/udesurd/) / [Phone](+375296437427)

## 👨🏻‍💻 About Me

*Learning javascript is an indispensable part of web development and not only, it is used in various areas of IT. 
Being my favorite language, it's also an essential part of frontend development.
My goal is to study in depth both the language and the profession in order to create services that can make life easier for others.
My experience with this language started 1 year ago. I participated in freelance development and creating personal projects.
<br><br>

## 🦤 Skills

** My skills include:
- HTML 
- CSS (Bootstrap, Preprocessor SCSS, BEM methodology)
- JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+,DOM)
- C#

** Frameworks:
- React / Redux.
- .Net 6

** Databases:
- - MsSQL
- MongoDB
<br><br>

## Code Example:

```js
document.querySelector('.btn-repos').onclick = function (e) {
    e.preventDefault();
    let login = document.querySelector('.input').value;
    let resulltVision = document.querySelector('.form__result')
    resulltVision.classList.add('active')
    fetch("https://api.github.com/"+ login+"/udesurd/repos/507312871")
    .then((result) => result.json())
    .then((data) => {
        document.querySelector('.form__result-repos').innerHTML = `
        <div class="result__wrapper-repos bg">
            ${data.description}
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

-English [EPAM English test result]([https://examinator.epam.com/Main/PersonalAssignments](https://examinator.epam.com/Main/PersonalAssignments/438259)): **A2+**
-Russian

<br>
<br>




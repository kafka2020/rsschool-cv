# Andrey Shinkarev
### Junior Front End Developer

---

## Contact Info
- **Address:** Stavropolsky kray, Nevinnomyssk, Russia
- **Phone:** +7 906 4892303
- **E-mail:** shinkarev89@gmail.com
- **Discord:** Andrey Shinkarev (@kafka2020)
- **Telegram:** @kafka2021
- **GitHub:** [kafka2020](https://github.com/kafka2020)
- **LinkedIn:** [Anreay Shinkarev](https://www.linkedin.com/in/andrey-shinkarev-0b43b4166/)

## About Myself
As a child, when I was 10, I started programming in BASIC. It was fun. At school I really liked computer science and programming. After school, I went to university and graduated as an electrical engineer. But the childhood love of programming has not gone away.

Now I want to learn the necessary knowledge and become a front-end developer.

## Skills
- HTML (semantic)
- CSS (flexbox/grid layouts)
- JavaScript Basics
- Command line interface 
- Git, GitHub
- VS Code, Chrome DevTools, Figma

## Code example
```JavaScript
let commentForm = document.querySelector('.comment-form');
let commentList = document.querySelector('.comment-list');
let commentField = document.querySelector('.comment-field');

commentForm.onsubmit = function (evt) {
  evt.preventDefault();

  let newComment = document.createElement('li');
  newComment.classList.add('user-comment');
  newComment.textContent = commentField.value;
  commentField.value = '';
  commentList.append(newComment);
};
```

## Experience
- **WorldSkills Standard Specification:** [Skills Passport](https://sp.dp.worldskills.ru/679252e3-5671-4453-b872-c605afdfaf98)  
    - _Design and web-development course_  
    - Exam paper (HTML, CSS, JavaScript): [GitHub](https://kafka2020.github.io/Design.pro/)

## Education
- ***July 2011:***  
    - **North-Caucasus Federal University (NCFU) (formerly North-Caucasus State Technical University), Stavropol**  
    - Engineer at specialty Electric drive and automation of industrial plants and technological complexes

- ***August 2021:***  
    - **Stavropol State Agrarian University, Stavropol**  
    - Postgraduate diploma in Web Development

## Languages
- Russian \- Native
- English \- A2 (Elementary English)

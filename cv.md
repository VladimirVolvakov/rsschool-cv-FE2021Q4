<!-- 
+Имя и фамилия
+Контакты для связи
+Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении учиться и узнавать новое)
+Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
+Примеры кода
+Опыт работы. Junior Dev может перечислить учебные проекты с указанием использованных навыков и ссылками на исходный код.
+Образование (включая пройденные курсы и тренинги)
+Английский язык (уровень английского языка, если была языковая практика, расскажите о ней) -->

![My photo](/assets/img_1.jpg)
#Volodymyr Volvakov
###Frontend Developer

###Contact Information
**Location:** Donetsk, Ukraine
**Phone:** +38-071-901-77-55
**Viber, Telegram:** +38-050-901-77-55
**WhatsApp:** +38-071-901-77-55
**E-mail:** dr.volvakov@gmail.com
**LinkedIn:** [Volodymyr Volvakov](https://www.linkedin.com/in/vladimir-volvakov-7243411a3/)
**Twitter:** [@VladVolvakov](https://twitter.com/VladVolvakov) 
**GitHub:** [Volodymyr Volvakov](https://github.com/VladimirVolvakov)

###About me
Since 2006 I work as a practicing dentist (entrepreneurship). Since 2008 I have also been working as a lecturer at Donetsk National Medical University (DNMU). From 2014 to 2019 I held the position of deputy dean of the Faculty of Dentistry of DNMU. So my entire professional career to date has been associated with medical care, workflow management, team work and teaching other people in my specialty. This experience of work was a great school for building my soft skills.

First my touch with web-development was in 2008. Then it was a hobby for switching my brain after work. Then I mastered HTML3 and even made a primitive website for my dental practice. 

About 1,5 years ago during lockdown I remembered my youth hobby and felt interest to modern web development. Then I decided to pass a course in JavaScript & Full stack development. It was not so easy for me because I had a lot of unanswered questions then but I’ve become really passionate about it. During this course, I realized that the frontend is of most interest to me, but a good web developer should be able to use the full stack. So I decided to master frontend development first and backend then (after I will feel complete confidence about my frontend development skills).

That's why I began to learn it at my afterwork time: I read tutorials and official documentation, watch videos on different Youtube channels, passed a couple of courses and try to write code every day.

I’m very fond of web development because it makes feel my ability of creating something new. This is a profession that holds the future and it provides great possibilities for personal and professional growth.

I believe that my love and ability to learn and gain new skills, my life experience and soft skills will lead me through the path of becoming a successful web developereveloper.

###Skills
* HTML5
* CSS3
* JavaScript
* React
* Git
* VS Code

###Code examples
**Task 1:** 
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in. Additionally, if the number is negative, return 0 (for languages that do have them. Note: If the number is a multiple of both 3 and 5, only count it once.

_**Code:**_
```javascript
function solution(number){
  let numsArray = []
  
  for (i = 1; i < number; i++) {
    numsArray.push(i)
  }
  
  return numsArray
    .filter(item => ((item % 3 === 0) || (item % 5 === 0)))
    .reduce((acc, rec) => acc + rec, 0) 
}
```

**Task 2:**
Your goal in this kata is to implement a difference function, which subtracts one list from another and returns the result.
It should remove all values from list a, which are present in list b keeping their order.
`arrayDiff([1,2],[1]) == [2];`
If a value is present in b, all of its occurrences must be removed from the other:
`arrayDiff([1,2,2,2,3],[2]) == [1,3];`

_**Code:**_
```javascript
function arrayDiff(a, b) {
  return a.filter(item => !b.includes(item))
}
```

###My Experience
**Education**
2001-2006 - Donetsk State Medical University, Faculty of Dentistry
2006-2008 - International University of Finance (Donetsk, Ukraine)

**Courses**
* [Skillcrucial](http://skillcrucial.com) - Full Stack Developer Course
* [FreeCodeCamp](http://www.freecodecamp.org/) - "Basic HTML and HTML5", "Basic CSS", "Applied Visual Design", "React"
* [Code-Basics](http://ru.code-basics.com/) - "HTML for beginners", "CSS fo beginners"
* Harvard University - [CS50 lectures](http://www.youtube.com/channel/UCcabW7890RKJzL968QWEykA)
* Academind - ["React Crash Course for Beginners 2021"](http://www.youtube.com/watch?v=Dorf8i6lCuk&t=6310s)
* Brad Traversy - ["React Front To Back 2022"](http://www.udemy.com/course/react-front-to-back-2022/) _(in progress)_ + lectures from [Youtube channel](https://www.youtube.com/c/TraversyMedia)
* Vladilen Minin - ["ReactJS from Zero to Hero"](https://webformyself.com/reactjs/) + lectures from [Youtube channel](https://www.youtube.com/c/VladilenMinin/)
* IT-KAMASUTRA - ["ReactJS - Samurai Way 1.0"](https://www.youtube.com/watch?v=gb7gMluAeao&list=PLcvhF2Wqh7DNVy1OCUpG3i5lyxyBWhGZ8)

**Projects:**
* [**Gallery of cars** (HTML, CSS, JavaScript)](http://github.com/VladimirVolvakov/gallery-of-cards)
* [**Feedback App** (HTML, CSS, JavaScript, React)](http://github.com/VladimirVolvakov/feedbackUI)

###Languages:
* Russian - native speaker
* Ukrainian - native speaker
* English - B2 
* German - A2
Practiced in English and German while traveling abroad.
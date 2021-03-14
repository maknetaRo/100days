## 100DaysOfCode

#### Start: January 30, 2021

#### My Goals:

- code every day a bit
- build projects

---
### Day 34: March 14, 2021

**Plans for Today:**

**Today's Progress:**
1. returned to John Smilga tutorial on React, learned about short-circuit evalutation 
```
const ShortCircuit = () => {
  const [text, setText] = useState("");
  return (
    <div>
      <h1>{text || 'john doe'}</h1> 
  
      {text && <h1>hello world</h1>}
    </div>
  )
}
```
- This expression`{text || 'john doe'}` means that if the first value is true, the first value will be displayed but if it's falsy, the second value will be displayed. In our case (because text is an empty string) it displays: 'john doe'

- The expression `{text && <h1>hello world</h1>}` says that if the first value is true, the second value will be displayed, if the first value is false, nothing will be displayed. In that case, nothing will be displayed.

We can also use {!text}

2. Created learning project from the course, almost everything by myself, only the last part I had to follow the tutorial. 

3. Managed to create mysql database in Django project. Created maps app and added dependencies for geodjango. 

4. Watched Emma Bostian talk from ReactJs Girls Conference from 2019

**Thoughts:**
I want to focus more on React. Much more. I think that learning by building is the best way of learning new stuff. 

**Link to work:**

**Plans for tomorrow:**
1. continue React course - build at least review project 
2. start checking how geodjango works

**Resources:**
* https://www.youtube.com/watch?v=ropAuzI7MtA

---

### Day 33: March 13, 2021

**Plans for Today:**


**Today's Progress:**
* finished styled components tutorial on scrimba
* cloned Django project

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**

**Resources:**

---

### Day 32: March 12, 2021

**Plans for Today:**
* continue Scrimba course on Styled Components
* clone Django project

**Today's Progress:**
* watched a bit more than 20% of Styled Components tutorial and spent more than 2hrs creating the project

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**
* Finish the course
* clone Django project and spend time on that project

**Resources:**
https://scrimba.com/learn/styledcomponents/passing-props-in-real-life-examples-project-work-co3fa4f778f94ebf9ce27939e

---

### Day 31: March 11, 2021

**Plans for Today:**
* learn React
* refactor some code in Zeton project

**Today's Progress:**
* started a new tutorial on Scriba about styled components - managed to do 39%.
* refactored some parts of the CustomSelect module in Zeton. I moved parts of the elements to smaller styled-components
* made a more complicated conditional in styling button
```
  background-color: ${({ theme, outline, disabled }) => {
  if (outline === true) {return "transparent"} 
  else if (disabled === true) { return theme.grey} 
  else {return theme.primary}
}};
```

**Thoughts:**
I like styled components more and more. And I feel really excited whenever I manage to do sth new.

**Link to work:**

**Plans for tomorrow:**
* continue course on Scrimba (it lasts only 1 hr but is with a project)
* clone Django edu app repo v.3, write the plan for my module, check what I did last time

**Resources:**


---


### Day 28 - 30: March 8 - 10, 2021

**Plans for Today:**

**Today's Progress:**
I finished CSS project I was working for a few days. Now I'm waiting for code review. 
I'm happy because I managed to add dark and light mode using nuxtjs/color-mode. It wasn't so difficult but I couldn't add svg icons from that library. 

---

How to use vars in scss for root and dark mode. 
1. First declare variables in scss style:
`$background-primary-color: #fff;`
2. Next add them to vars
`--background-primary-color: #{$background-primary-color};`

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**
* Come back to React: 
-- follow React course
-- work a bit on Zeton (change button disabled color and maybe refactor my code to separate UI from logic)

**Resources:**
* https://nuxtjs.org/blog/going-dark-with-nuxtjs-color-mode/
* https://dev.to/kensixx/guide-on-how-to-apply-nuxt-color-mode-with-bulma-1ekc

---


### Day 26-27: March 6-7, 2021

**Plans for Today:**

**Today's Progress:**
* was only following a bit of React course
* did some CSS in another project
* created a small word-cloud project

**Thoughts:**
* Wasn't feeling good on Saturday, slept all evening
* working with python is so fun

**Link to work:**

**Plans for tomorrow:**
* continue CSS in another project
* try to change button color when disabled in Zeton React project
* follow React tutorial

**Resources:**
https://github.com/amueller/word_cloud/blob/master/examples/alice.png

---


### Day 25: March 5 , 2021

**Plans for Today:**
* react tutorial & google font clone project

**Today's Progress:**
* created simple card in React js (promps from tutorial but I wasn't checking the tutorial to do it)
* haven't planned it, but started watching a yt series about Python openCV library and watched 4 videos
* Fav-Fonts in React: divided card component into smaller parts and added some data

**Thoughts:**
* really liked this openCV library, I don't know why but I always thought that it is something to work on excel sheets and other "boring" things

**Link to work:**
- https://github.com/maknetaRo/fav-fonts-react

**Plans for tomorrow:**
* add google fonts api 
* continue learning opencv library
* change disabled button style (color) in zeton project and try to refactor the code to divide logic and ui into 2 components

**Resources:**
https://www.youtube.com/watch?v=qCR2Weh64h4&list=PLzMcBGfZo4-lUA8uGjeXhBUUzPYc6vZRn


---

### Day 22, 23, 24: March 2, 3, 4, 2021

**Plans for Today:**

**Today's Progress:**
* I'm doing another React course slowly and also adding some changes to zeton project. 

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**

**Resources:**
https://www.udemy.com/course/react-tutorial-and-projects-course/learn/lecture/22580598#overview

---

### Day 21: March 1, 2021

## I decided to focus only on React in March. 

**Plans for Today:**
* work on custom select in React

**Today's Progress:**
* started my custom select from the beginning, but I have a few problems:
- I want to change the "header" part from "Choose a prize" into the actual prize and points, but it is an object and I don't know how to do it with objects;
- I'm not sure how to add a separate button to it that will trigger some computation

**Thoughts:**
Styled components are pretty nice. I'm glad I started learning it.

**Link to work:**

**Plans for tomorrow:**
* I may start another course that teaches more about hooks and functional components because I need them. I have also React Tutorial and Projects Course from John Smilga

**Resources:**
* React Tutorial and Projects Course

---

### Day 20: February 28, 2021

**Plans for Today:**

**Today's Progress:**
* Actually spent more than 8 hrs learning and coding:
- watched and followed a few parts of React course
- tried to create custom select using styled-components in React
- read about accessibility in custom select and tried to create custom select once again but couldn't make it work properly

**Thoughts:**
It was my best day for a long time. I was in a flow and it's a fantastic feeling.

**Link to work:**

**Plans for tomorrow:**
* work on custom select

**Resources:**

---

### Day 19: February 25, 2021

**Plans for Today:**
* React course
* style select form

**Today's Progress:**
* watched 9 videos from the course
* started building react app using an old html/css/js project

**Thoughts:**
I couldn't focus on videos today. They were too theoretical. I think I will have to come back to some of them later. I want to do my own small project (at least part of it with adding api and searching through cards) before starting the final project from the course. 

**Link to work:**

**Plans for tomorrow:**
* watch some more videos
* work on select and some other CSS (nuxt)

**Resources:**

---

### Day 18: February 24, 2021

**Plans for Today:**
- learn React
- work on zeton

**Today's Progress:**
* worked a bit on select form in React but haven't finished it yet
* watched more than 20 episodes of Complete React Developer in 2021 and coded along

**Thoughts:**
* need to stick to the course even though video courses aren't my fav way of learning; need to implement what I've learned in google font app; I mean I have a simple js app with google fonts and I could move it into React to practise.

**Link to work:**

**Plans for tomorrow:**
- React course
- finish select form 

**Resources:**
* https://www.udemy.com/course/complete-react-developer-zero-to-mastery/learn/lecture/15103904#content
* https://www.freecodecamp.org/news/styled-components-essentials-in-three-steps/
* https://spectrum.chat/styled-components/help/how-to-make-dropdown-menu-with-styled-components~219502c6-b8e2-476e-a9fd-0780f1a3e8d6


---

### Day 17: February 23, 2021

**Plans for Today:**
- zeton project: react styled components

**Today's Progress:**
- wrote some code and then had a meeting and after the meeting I put all the code to the trash 

**Thoughts:**
- need to spend more time learning and understanding React

**Link to work:**

**Plans for tomorrow:**
- react

**Resources:**

---

### Day 16: February 22, 2021

**Plans for Today:**
* Żeton 

**Today's Progress:**
* revised a bit of Vue notes (created space repetition system on Notion)
* started working on Żeton using styled components, created ListElement and AddElementForm

**Thoughts:**
I know that I know nothing. 

**Link to work:**

**Plans for tomorrow:**
* more work on Żeton, try style components and handle the form submission

**Resources:**

---

### Day 15: February 20, 2021

**Plans for Today:**
* make notes about Vue features
* start working on zeton 

**Today's Progress:**
* Spend my time mostly making notes about VueJS

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**

**Resources:**

---

### Day 14: February 19, 2021

**Plans for Today:**
* continue Vue project

**Today's Progress:**
* not much progress: I came back to one component only because now I want to be able to sort columns and really don't know how to do it.

**Thoughts:**
Creating tables with data from api isn't as easy as I thought :-(. This conclusion made me a bit sad and made me start thinking again that I know nothing about programming thinking and how to change it.

**Link to work:**

**Plans for tomorrow:**
* need to work on Zeton
* check how sorting was working in another project I took part in 

**Resources:**

---

### Day 13: February 18, 2021

**Plans for Today:**
- more on Vue components

**Today's Progress:**
1. read more about vue components and starting project with cli
2. started a new vue app but managed only to create one component

**Thoughts:**
In theory, props are easy but now when I want to build my own project without using any tutorial I have some problems with deciding what components I should build and how to pass data from parent component into a child component. 

Since master was replaced with main on Github I've got some problems with doing it properly. Instruction how to change master into main 
```
# Step 1 
# create main branch locally, taking the history from master
git branch -m master main

# Step 2 
# push the new local main branch to the remote repo (GitHub) 
git push -u origin main

# Step 3
# switch the current HEAD to the main branch
git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main

# Step 4
# change the default branch on GitHub to main
# https://docs.github.com/en/github/administering-a-repository/setting-the-default-branch

# Step 5
# delete the master branch on the remote
git push origin --delete master
```

**Link to work:**
- https://github.com/maknetaRo/countries-vue-app

**Plans for tomorrow:**
- continue my project
- maybe watch Vue JS 2 Tutorial by net ninja 

**Resources:**
* Country API: https://restcountries.eu/
* Vue JS 2 tutorial by net ninja: https://www.youtube.com/watch?v=3ROjxrSa5pk&list=PL4cUxeGkcC9gQcYgjhBoeQH7wiAyZNrYa&index=2

---

### Day 12: February 17, 2021

**Plans for Today:**
* vue components

**Today's Progress:**
* read 3 chapters (3 days) about Vue components from 30 days of Vue course
* learned how props and custom events work (in general)
"Props are always used to pass data downwards (parent -> child -> grandchild, etc) while custom events can be used to send information upwards."

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**
* finish reading about components in Vue 

**Resources:**

---

### Day 11: February 15, 2021

**Plans for Today:**
* lifecycle hooks in Vue 

**Today's Progress:**
* revised previous days of the 30 days of Vue tutorial
* read about lifecycle hooks in Vue
* spent most of my time trying to make ssh github key work properly

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**
* Zeton project 

**Resources:**
* https://www.newline.co/30-days-of-vue/day-10-lifecycle-hooks

---

### Day 9-10: February 13-14, 2021

**Plans for Today:**

**Today's Progress:**
Read 30 days of vue till Lifecycle hooks

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**
* read/learn about Lifecycle hooks and more from 30 days of Vue

**Resources:**
https://www.newline.co/30-days-of-vue/

---

### Day 8: February 12, 2021

**Plans for Today:**
* Learn Vue

**Today's Progress:**
* read and coded along and took notes of 5 days from 30 days of Vue.
- Vue directives: 
1. `v-on` -- `@`
2. `v-bind` -- `:`
3. `v-if`
4. `v-show`
5. `v-for`


* watched a short video about getters and setters in JavaScript

**Thoughts:**
Like 30 days of Vue tut.


**Link to work:**

**Plans for tomorrow:**
* continue 30 days of Vue from day 6
* work a bit on Nuxt project

**Resources:**
* https://www.newline.co/30-days-of-vue

---

### Day 7: February 10, 2021

**Plans for Today:**
1. Continue Vue tutorial from Tania Rascia

**Today's Progress:**
Did a bit of the Vue tutorial. Started learning something quite new (Hkll) but decided that it's not right time to do it now. 

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**

**Resources:**

---

### Day 6: Ferbruary 8, 2021

**Today's Progress:**
Haven't done much. Only a very small bit of CSS in Nuxt.js project. It's difficult for me to figurate where some things come from (in CSS) even though there are not many CSS files. 

---

### Day 4, 5: February 3, 4, 2021

**Thoughts:**
I was having a problem with ESLint for 2 days. I couldn't make it work and didn't know what it was and why I couldn't do anything in a project. I figured it out (at least I hope so) and started redoing some CSS in the Nuxt.js project. 

---

### Day 3: February 2, 2021

**Plans for Today:**
1. Learn Vue
2. Start css-redo.

**Today's Progress:**
1. Added random cocktail recipe to nuxt app. But only title, image, category and description. I don't know how to filter array from api in Vue.
2. Tried to run another project but had problems with dependencies (ESlint error)

**Thoughts:**
1. I don't know how to filter array from api in vue and how to create a component that uses only part of data from api. I'm using cocktail api. In each cocktail there are different ingredients. I want to create Ingredients component. 

**Link to work:**
* https://github.com/maknetaRo/nuxt-js-coctail-app/commit/3dd8a68873ddcb7d0d411e2e569a13db4a4be324

**Plans for tomorrow:**
1. Resolve problem with Eslint and start working on that project - I need to change CSS in Nuxt.js project
2. Continue learning about components and passing data from one component into another

**Resources:**
* https://www.thecocktaildb.com/api.php

---

### Day 2: February 1, 2021

**Plans for Today:**
1. Learn some basic Vue: https://www.taniarascia.com/getting-started-with-vue/
2. Add "pagination" to Cocktail App.


**Today's Progress:**
1. Went only through half of basic Vue tutorial

**Thoughts:**
I love that vue uses similar directives to those used by Angular. I don't remember much from Angular but I remember that I liked this part. 

**Link to work:**

**Plans for tomorrow:**
1. Recreate the part I was learning today (but instead of building a table of employees, I'll do another todo app or contact list)
2. Continue Tania's tutorial https://www.taniarascia.com/getting-started-with-vue/

**Resources:**
* https://www.taniarascia.com/getting-started-with-vue/

---

### Day 1: January 30 , 2021

**Plans for Today:**
1. Nuxt.js course by Traversy Media
2. Start an app in Nuxt and Vue

**Today's Progress:**
1. Watched and code along Traversy Media crash course on yt.
2. Started the Cocktail Recipes app using TheCoctailDB API. Created one page with recipes started with the letter m. 

**Thoughts:**
I like Nuxt but I know I won't be able to do much not knowing Vue. I think I need to start learning Vue properly first ;-)

**Link to work:**
https://github.com/maknetaRo/nuxt-js-coctail-app/tree/main

**Plans for tomorrow:**
1. Learn some basic Vue: https://www.taniarascia.com/getting-started-with-vue/
2. Read about useEffect in React.
3. https://www.freecodecamp.org/news/react-movie-app-tutorial/

**Resources:**
* https://www.youtube.com/results?search_query=nuxt+js+application

---

#### Resources
* https://nuxtjs.org/
* https://automatetheboringstuff.com/2e/chapter12/
* https://automatetheboringstuff.com/2e/chapter18/



<!-- Template
### Day 0: March, 2021

**Plans for Today:**

**Today's Progress:**

**Thoughts:**

**Link to work:**

**Plans for tomorrow:**

**Resources:**

---

 -->

# project 2 : Basic Movie Seat Selector

## What's this?
- Basic movie seat selector made with HTML + CSS + Vanilla JS.
- It's a part of my effort to get familiar with the front-end web dev (2 of 20)
- visit here for demo : https://marczen.github.io/2-web-projects-movie-selector/

## What I learned in this project
### JS
- js script's basic structure
  1. dom selectors at the top
  2. function declaration in the middle
  3. event listeners at the bottom
  - but the real process is like
    1. think about what function (I mean product's function) customers need (YAGNI!)
    2. define what events you need to hook that up
    3. what input, output needed?
    4. don't code. paper & algorithm is your best friend
    5. code
        - inside coding process
            1. dom selection & variable declaration
            2. event listeners & function outlining
            3. function declaration
    6. refactor
- to convert str to int in JS, you can just use +
- e.target
- if e.target.classList.contains('className') {e.target.classList.toggle('selected')}
  - didn't know about classList
  - add, remove, toggle to manipulate classes
- you can use css pseud-selectors inside querySelectorAll('here!')

### CSS
- learned difference btw .seat.occupied vs .seat .occupied
- css pseudo-selectors are powerful
  - like : .seat:not(.occupied):hover { /* style */ }

### HTML
- be more conscious about how are you going to wrap things around with div boxes
- you can use lists to bind similar elements together
- html & css is closely related

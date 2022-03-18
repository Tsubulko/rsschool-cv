# Pavel Tsubulko
## Junior Front-end developer

***

### Contact information:

**Phone:** +375299418088

**E-mail:** pashatsubulko@gmail.com

**Telegram:** @Pavel_Tsubulko

***

### About myself:

***

### Skills and Proficiency:

* Git, GitHub
* HTML5, CSS3
* JavaScript Basics
* C++ Basics
* VS Code
* Figma

***

### Code exaple:
**"Handshake problem" KATA fron Codewars:** Johnny is a farmer and he annually holds a beet farmers convention "Drop the beet".

Every year he takes photos of farmers handshaking. Johnny knows that no two farmers handshake more than once. He also knows that some of the possible handshake combinations may not happen.

However, Johnny would like to know the minimal amount of people that participated this year just by counting all the handshakes.

Help Johnny by writing a function, that takes the amount of handshakes and returns the minimal amount of people needed to perform these handshakes (a pair of farmers handshake only once).

```js
function getParticipants(handshakes)
{
  let count = 1, hsh = 1;
  while (hsh <= handshakes) 
  {
    count += 1;
    hsh += ((count - 1));
  }
  return  count;
} 
```

***

### Courses:

* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
* [Code-Basics (HTML, CSS, JS)](https://ru.code-basics.com/)

***

### Project:

[CV](https://github.com/Tsubulko/rsschool-cv)

***

### Languages:

* Russian - Native 
* English - Intermediate (according to the online test at [EFSET](www.efset.org))
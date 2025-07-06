# Dastan Hairushev
# My contact info
* Telegram: @FierceSloth
* Email: hairushevdastan@gmail.com
* Discord: @fiercesloth_
# Summary
Having started learning programming in the summer of 2024, I am gradually getting more and more into the frontend. I can study for 5-7 hours a day, and I am interested in it. I like to solve complex problems with good music.
My main strengths are quickly understanding complex aspects and quickly solving problems. My main goal now is to become a professional frontend developer. I believe that patience and hard work will help me achieve this.
# Skills
* HTML
* CSS
* JavaScript Basic
* Git, GitHub
* AI Tools Proficiency
* WordPress, Tilda
# Code Example:
__KATA__ from __CODEWARS__: Write a class that, when given a string, will return an uppercase string with each letter shifted forward in the alphabet by however many spots the cipher was initialized to.
``` let CaesarCipher = function (shift) {
  const alphabet = ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'];
  
  this.encode = function(word)  {
    let arrWord = word.toUpperCase().split('')
    let shiftWord = arrWord.map(item => {

      const index = alphabet.findIndex(letter => letter === item); 
      if (index === -1) return item; 
      return alphabet[(index + shift + alphabet.length) % alphabet.length]; 

    });

    return shiftWord.join('')
  }
  
  this.decode = function(word) {
    let arrWord = word.toUpperCase().split('')
    let shiftWord = arrWord.map(item => {

      const index = alphabet.findIndex(letter => letter === item); 
      if (index === -1) return item;
      return alphabet[(index - shift + alphabet.length) % alphabet.length];

    });

    return shiftWord.join('')
  }
};
```
# Courses
 __Aroken Front-End Course__
- Practical HTML and CSS training: semantic layout, flexbox, responsive design, cross-browser compatibility.

__Hexlet JavaScript Basics__
- Introduction to JavaScript: variables, conditions, loops, functions, basic DOM manipulation.

__Learn.Javascript.ru (Self-Study)__
- In-depth JavaScript knowledge: closures, prototypes, object-oriented programming, modules, and modern ES6+ features.
# Languages:
Russian: Native
English: Pre-Intermediate
Kazakh: Basic

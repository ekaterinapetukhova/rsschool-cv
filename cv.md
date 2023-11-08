# Ekaterina Petukhova, _web developer_

<img src="https://github.com/ekaterinapetukhova/rsschool-cv/assets/109340451/e25758a6-b726-4cf3-a5c7-24f8df465095" height='400'>

## 👋🏻 summary

i am a student of computer science faculty and i am starting my journey in the it world. my interest to information technologies appeared in my chilldhood and hash't disappeared nowadays, so my main goal is to become a great web developer (and i am not going to stop after achieve this). i already have little expierince to work in the it company, where i was creating and developing interface of the recruitment website. i am full of enthusiasm and ambitiones, always want to discover and to learn something new for me. 

## 🔌 contacts

**mail:** katepthv12@gmail.com

**discord:** sadkote.1234 (ekaterinapetukhova)

**[linkedin](https://www.linkedin.com/in/ekaterina-petukhova/)**

**[instagram](https://www.instagram.com/sadkote/)**

## 🎓 education

### belarussian state university, minsk

faculty of chemistry 

*2018 — 2021 (incomplete)*

### academy of silesia, katowice

faculty of computer science

*2021 — now*

## 💼 career history

### front-end developer intern, agileo.it

*jun — sep 2022, katowice*

* created and developed interface of recruitment website, using html/haml, bootstarp and scss

## 📖 courses 

### «JavaScript/Front-end. Stage 0», The Rolling Scopes

*jun — oct 2023*

### «JavaScript/Front-end», The Rolling Scopes

*nov 2023 — now*

## 🚀 skills & tools

* html

* css

* scss

* javacsript

* git

* figma

* gulp

## ⌨️ code example

[Base Conversion](https://www.codewars.com/kata/526a569ca578d7e6e300034e): *In this kata you have to implement a base converter, which converts positive integers between arbitrary bases / alphabets. Here are some pre-defined alphabets:*
```
var Alphabet = {
  BINARY:        '01',
  OCTAL:         '01234567',
  DECIMAL:       '0123456789',
  HEXA_DECIMAL:  '0123456789abcdef',
  ALPHA_LOWER:   'abcdefghijklmnopqrstuvwxyz',
  ALPHA_UPPER:   'ABCDEFGHIJKLMNOPQRSTUVWXYZ',
  ALPHA:         'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ',
  ALPHA_NUMERIC: '0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'
};
```
*The function convert() should take an input (string), the source alphabet (string) and the target alphabet (string). You can assume that the input value always consists of characters from the source alphabet. You don't need to validate it.*

```javascript
function convert(input, source, target) {
  const arr = input.split('');
  let convToTarg = [];
  
  let convToDec = arr.reduce((acc, item, index) => {
    acc += source.indexOf(item) * Math.pow(source.length, arr.length - 1 - index);
    return acc;
  }, 0);
  
  if (convToDec === 0) {
    convToTarg.push(convToDec);
  } else {
    while (convToDec !== 0) {
    convToTarg.push(convToDec % target.length);
    convToDec = Math.floor(convToDec / target.length);
   }
  }
  
  return convToTarg.reverse().map((item) => target.charAt(item)).join('');
}
```

## 🖥️ works examples

[audio player on pure javascript](https://rolling-scopes-school.github.io/ekaterinapetukhova-JSFEPRESCHOOL2023Q2/js30-1-2-audio-player/)

[gallery with unplash api](https://rolling-scopes-school.github.io/ekaterinapetukhova-JSFEPRESCHOOL2023Q2/js30-2-2-image-galery/)

[takeaway&delivery landing](https://ekaterinapetukhova.github.io/takeaway-and-delivery-landing/)

## 🌍 languages

* russian - *native (c2)*

* english - *intermediate (b1)*

* polish - *intermediate (b1)*


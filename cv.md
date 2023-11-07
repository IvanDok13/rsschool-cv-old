# Ivan Klochkov
### Frontend Developer
---
### Contact information:
**Phone:** +7(952)-268-28-64<br>
**E-mail:** [klochkov.ivan.sergeevich@gmail.com](mailto:klochkov.ivan.sergeevich@gmail.com)<br>
**Telegram:** [Dokivan](https://t.me/Dokivan)<br>
**Discord:** [IvanDok13](https://discordapp.com/users/IvanDok13#5167/)<br>

---
### About Me:
I worked as a researcher in the field of laser technology for 6 years. Developed various research methods, conducted experiments and made calculations.

In addition to my main job, for 6 years I was involved in and managed a company organizing outdoor events.

I became very interested in front-end development after I saw the work of my friends from the 'InDriver' and  
other large companies.

I love making improvements to workflows, solving complex problems, optimizing anything. I am sure that these skills will allow me to become an excellent developer.

---
### Languages and tools
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title="js" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" title="html" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" title="css" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" title="git" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" title="vscode" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" title="npm" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" title="node" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/eslint/eslint-original.svg" title="eslint" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vim/vim-original.svg" title="VIM" width="40" height="40"/>&nbsp;

---
### Code examples:
<a href="https://www.codewars.com/users/rsschool_5bb3f79998ed1d87"><img src="https://www.codewars.com/users/rsschool_5bb3f79998ed1d87/badges/large"></a>

**[Is a number prime?](https://www.codewars.com/kata/5262119038c0985a5b00029f)**
*Define a function that takes an integer argument and returns a logical value true or false depending on if the integer is a prime.*

```javascript
const isPrime = num => {
    for(let i = 2, s = Math.sqrt(num); i <= s; i++) {
        if(num % i === 0) return false;
    }
    return num > 1;
}

console.log(isPrime(1)) //false
console.log(isPrime(2)) //true
console.log(isPrime(-1)) //false
```
**[RGB To Hex Conversion](https://www.codewars.com/kata/513e08acc600c94f01000001)**
*The rgb function is incomplete. Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value.*

```javascript
function rgb(r, g, b) {
  let str = '';
  if (r < 0) r = 0;
  if (g < 0) g = 0;
  if (b < 0) b = 0;
  if (r > 255) r = 255;
  if (g > 255) g = 255;
  if (b > 255) b = 255;
  str = `${('0' + r.toString(16)).slice(-2)}${('0' + g.toString(16)).slice(-2)}${('0' + b.toString(16)).slice(-2)}`
  return str.toUpperCase();
}

console.log(rgb(255, 255, 255)) //"FFFFFF"
console.log(rgb(255, 255, 300)) //"FFFFFF"
console.log(rgb(0, 0, 0)) //"000000"
console.log(rgb(148, 0, 211)) //"9400D3"
```
---
### Projects
1. [Traveling-site](https://ivandok13.github.io/traveling-site/)
2. [Image-gallery](https://rolling-scopes-school.github.io/ivandok13-JSFEPRESCHOOL2023Q2/image-galery/)
3. [Pictures-slider](https://ivandok13.github.io/pictures-slider/)
4. [cssMemeSlider](https://ivandok13.github.io/cssMemeSlider/cssMemeSlider/index.html)
5. [Car-Slider-Project](https://ivandok13.github.io/slide-project/)
6. [Morse-decoder](https://github.com/IvanDok13/morse-decoder)
7. [Video Player](https://rolling-scopes-school.github.io/ivandok13-JSFEPRESCHOOL2023Q2/custom-video/)
8. [Library](https://rolling-scopes-school.github.io/ivandok13-JSFEPRESCHOOL2023Q2/library/)
9. [Drag-and-drop](https://ivandok13.github.io/drag-and-drop/)

---
### Courses:
The Rolling Scopes School - JS/FE Pre-School 2023Q2<br>
Result School - HTML&CSS 2022<br>
PASV - JavaScript 2022<br>
Hexlet - Front-end Developer 2021<br>

---
### Languages:
- Russian \- Native
- English \- Upper-intermediate


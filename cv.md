# Alexander Bazhenov (@alexbazhen)
Hello, I'm Alex! And this is my CV. Welcome!

## Contacts
* GitHub - [@alexbazhen](https://github.com/alexbazhen)
* Telegram - [@Alexbazhen](https://t.me/Alexbazhen)
* E-Mail - [alexbazhen@yandex.ru](mailto:alexbazhen@yandex.ru)
* Discord - `alexbazhen#5328`

## About Me
> I like working with web technologies. I have been developing websites for several years. In a couple of years, I would like to become a confident Middle Front-End developer. At the moment I am actively learning JS in RS School and I like it.

## My Skills

### WebDev
1. `HTML, CSS (SCSS, LESS)`
2. `JS`*(Studying now)*
3. `GIT`
4. `CMS: October CMS, WordPress`
5. `VS:Code`

### Design
1. `Figma`
2. `Adobe Photoshop/Illustrator`
3. `Adobe After Effects/Premier`

## Code Examples
[Isograms](https://www.codewars.com/kata/54ba84be607a92aa900000f1/javascript)
``` 
function isIsogram(str){
  const low = str.toLowerCase();
  const mas = [...low];
  const repeat = mas.filter((element, i, mas) => mas.indexOf(element) !== i).map(element => [element, element]);
  if (repeat.length > 0) {
    return false;
  } else {
    return true;
  }
} 
```
----
[Duplicate Encoder](https://www.codewars.com/kata/54b42f9314d9229fd6000d9c)
```
function duplicateEncode(word){
  return word
    .toLowerCase()
    .split("")
    .map(function (a, i, mas) {
      return mas.indexOf(a) == mas.lastIndexOf(a) ? "(" : ")";
    })
    .join("");
}
```

## My Experience
Website for IT business company - [Link](https://itb365.ru)

Website for motorsport club - [Link](https://inside-racing.ru)

## My Courses
1. Udemy - WebDev (HTML/CSS/JS)
2. Udemy - JS (From 0 to Pro)
3. *RS School (Now)*

## English lvl
`Pre-intermediate - A2`

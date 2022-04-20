# Kuvonchbek Khalilov
## Contact info:

[Email](mailto:kukhalilov@gmail.com)
[Telegram](https://t.me/Kuvonchbek_Khalilov)
[Github](https://github.com/kukhalilov/)

## About me:

Currently a student at university majoring in Business Information Systems. Taking additional courses outside of university to improve skills. Driven by the desire to learn new things and benefit others. Looking for an opportunity to get an Internship or a Junior position in Web Development.

## Skills:

- HTML
- CSS
- JavaScript
- Nodejs
- Pug
- Git / GitHub
- Python
- C#
- SQLite

## Code examples

*Playing with digits*

```sh
function digPow(n, p) {
  digits = [...(n + "")].map((c) => +c);
  sum = 0;
  for (let digit of digits) {
    sum += Math.pow(digit, p);
    p++;
  }
  k = sum / n;
  if (Number.isInteger(k)) {
    return k;
  } else {
    return -1;
  }
}
```

*Persistent Bugger*

```sh
function persistence(num) {
  let times = 0;
  function recursivePersistence(num) {
    let product = 1;
    digits = [...(num + "")].map((c) => +c);
    for (let digit of digits) {
      product *= digit;
    }
    while (digits.length > 0) {
      if (digits.length == 1) {
        return times;
      }
      times++;
      recursivePersistence(product);
    }
  }
  return recursivePersistence(num);
}
```
## Project

*Link to source:*
[GitHub](https://github.com/00012256/WT-CW2)

*Link to hosted web app:*
[Glitch](https://achieved-kaput-wedge.glitch.me/)

Developed a web app with CRUD functionality using HTML, CSS, JavaScript, Nodejs, Pug, and MongoDB

## Education

**Westminster International University in Tashkent** <br /> Business Information Systems <br />(*2020-2024*)

## Languages

- **Uzbek** <br />Level: Native
- **English** <br />Level: C1 (IELTS 7.5)

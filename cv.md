# Marat Mizitov

## Contacts
**Location:** Krasnodar, Russia \
**Email:** marat10008@gmail.com \
**GitHub:** [marat1000](https://github.com/marat1000) \
**Telegram:** [@Marat10008](https://t.me/Marat10008) \
**Discord:** Marat#2357 (Marat(@marat1000))

## About Me
Fast learner, hard worker and team player who is proficient at a basic level in an array of scripting languages and Web tools. I am reliable and dependable and often seek new responsibilities within a wide range of employment areas.

## Skills
* HTML5, CSS3
* SASS
* JavaScript (Basic)
* PHP (Basic)
* Oberon (Basic)
* Git
* Gulp
* Adobe Photoshop, Figma

## Code Example
```
/* Given a non-negative integer n,
write a function decimalToBase
which returns that number in a base format. */

function decimalToBase(n: number, base: number): number {
  /* precondition Q: n >= 0 AND 2 >= base AND base <= 10; */
  if (!Number.isInteger(n) || n < 0) {
    throw new Error(`n must be an integer and a non-negative number`);
  }
  if (!Number.isInteger(base) || base < 2 || base > 10) {
    throw new Error(`base must be an integer in the range from 2 to 10 inclusive`);
  }
  /* { Q === true }; */
  let remainder = n;
  let result = ``;
  /* invariant P: n === (remainder + Number(Number(result).toString(10))); */
  /* bound: Math.ceil(log base(remainder)) + 1; */
  /* { P === true }; */
  while (remainder !== 0) {
    const digit = remainder % base;
    result = `${digit}${result}`;
    remainder = Math.floor(remainder / base);
  }
  /* { (P AND remainder === 0) === true }; */
  /* { R === true }; */
  /* postcondition R: Number(result) === the base representation of n; */
  return Number(result);
}
```

## Education
University: North Caucasus Federal University

## Courses:
[HTML Academy](https://htmlacademy.ru/profile/id606021)

## English
C1 (Advanced)
[EF SET](https://www.efset.org/cert/2XKKJ5)

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
* Adobe Photoshop, Figma

## Code Example
```
/* Given a non-negative integer n,
write a function to_binary/ToBinary
which returns that number in a binary format. */

function toBinary(n) {
  let rest = n;
  let binary = 0;
  let power = 0;
  while (n > (2 ** power)) {
    power++;
  }
  while (power !== -1) {
    if (rest - (2 ** power) > -1) {
      binary = binary * 10 + 1;
      rest = rest - (2 ** power);
    } else {
      binary = binary * 10;
    }
    power--;
  }
  return binary;
}
```

## Education
University: North Caucasus Federal University

## Courses:
[HTML Academy](https://htmlacademy.ru/profile/id606021)

## English
C1 (Advanced)
[EF SET](https://www.efset.org/cert/2XKKJ5)

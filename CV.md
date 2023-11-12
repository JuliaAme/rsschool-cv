# CV

---

![Photo](.testrs/../IMG_4874.jpg)

## Julia Ameltchenko

## 35 years old

## About me

- study programming
- always try to learn new things
- diligent student
- main goal - become Software developer

## Skills

- HTML
- CSS
- JavaScript
- GIT

## Code examples

```javascript
function findNeedle(haystack) {
  return `found the needle at position ${haystack.indexOf("needle")}`;
}
console.log(
  findNeedle(["hay", "junk", "hay", "hay", "moreJunk", "needle", "randomJunk"])
);
```

```javascript
function areYouPlayingBanjo(name) {
  if (name[0] === "R" || name[0] === "r") {
    return name + " plays banjo";
  } else {
    return name + " does not play banjo";
  }
}
console.log(areYouPlayingBanjo("rolf"));
```

```javascript
function noSpace(x) {
  x = x.split(" ").join("");
  return x;
}
console.log(noSpace("8aaaaa dddd r     "));

//4.Find the smallest integer in the array
function findSmallestInt(args) {
  let min = args[0];
  for (let i = 0; i < args.length; i += 1) {
    if (args[i] < min) {
      min = args[i];
    }
  }
  return min;
}
console.log(findSmallestInt([78, 56, 232, 12, 8]));
```

## Projects

- [Noemi travel blog](https://github.com/JuliaAme/mq-diploma-last)
- [CV]()

## Education

- RS school tasks
- Netology (HTML, CSS modules)
- Elbrus Bootcamp (JavaScript prep course)

## English language

_Intermediate_ level

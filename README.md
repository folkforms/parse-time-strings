# parse-time-strings

Parse time strings into raw minutes e.g. '1h30m' -> '90'

## Usage

```
const parseTimeStrings = require('parse-time-strings');
console.log(parseTimeStrings("1h10m"); // 70
console.log(parseTimeStrings("1 h 20 m"); // 80
console.log(parseTimeStrings("1.25hrs"); // 75
console.log(parseTimeStrings("2 hrs 30 minutes"); // 150
console.log(parseTimeStrings("2 hours 30 minutes"); // 150
```

(Plus a few other combinations. Let me know if I've missed anything obvious.)

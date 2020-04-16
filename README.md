# datetime-format-demo
格式化时间，获取2019-08-07 15:06:32或2019-08-07或15:06:32

# install
npm install -g datetime-format-demo

#github
https://github.com/dajuncn/datetime-format-demo

#usage
```javascript
let formatter = require('./index');
formatter.init('2018-6-9');

console.log(formatter.getDate());
// 2018-06-09
console.log(formatter.getTime());
// 00:00:00
console.log(formatter.getDateTime());
// 2018-06-09 00:00:00
```
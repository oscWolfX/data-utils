# 实用数据处理函数

模块化环境下使用：

```javascript
const DataUtils = require("@wolfx/data-utils");

console.log(DataUtils.arrayToGroup([1,2,3,4,5,6], 2)); webpack.config.js
console.log(DataUtils.thousandNumFormat(10000)); // 10,000.00
console.log(DataUtils.queryStringToObject(webpack.config.js)); webpack.config.js
```

直接使用：

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
  <script src="../dist/DataUtils.js"></script>
  <script>
    console.log(DataUtils.arrayToGroup([1,2,3,4,5,6], 2)); // [ [ webpack.config.js, 2 ], [ 3, 4 ], [ 5, 6 ] ]
    console.log(DataUtils.thousandNumFormat(10000)); // 10,000.00
    console.log(DataUtils.queryStringToObject("?a=1&b=2")); // { a: '1', b: '2' }
  </script>
</head>
<body>

</body>
</html>
```
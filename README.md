# cookies.js

Proves simple CRUD operations for cookies in browsers

## Installation

`$ yarn add https://github.com/IBM/cookies.git`

## How to use

```javascript
import Cookies from "cookies";

Cookies.set("mykey", "myvalue", 1); // Set for 1 day
const res = Cookies.get("mykey"); // Read cookie
console.log(res); // Prints "myvalue"
Cookies.erase("mykey"); // Delete cookie
```

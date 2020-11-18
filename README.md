# cookies.js

Proves simple CRUD operations for cookies in browsers

## Installation

Replace `[YOUR_GIT_TOKEN]` with your token:

`$ npm install git+https://[YOUR_GIT_TOKEN]:x-oauth-basic@github.ibm.com/CyberRangers/cookies.git`

## How to use

```javascript
import Cookies from "cookies";

Cookies.set("mykey", "myvalue", 1); // Set for 1 day
const res = Cookies.get("mykey"); // Read cookie
console.log(res); // Prints "myvalue"
Cookies.erase("mykey"); // Delete cookie
```

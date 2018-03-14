``` js
const cv = require("@jx/config-vars");

cv((getenv /* getenv */) => ({
    port: getenv("PORT")
}));

const port = cv.env.port;
```
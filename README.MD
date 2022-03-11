# UTM Aska

## 📃 Description
Library to get UTM params from url and cookies

## 📦 Installation

### NPM

`npm install --save @norvikit/utm-aska`

### Yarn

`yarn add @norvikit/utm-aska`

## 🚀 Usage

### Using a `<script>` tag:
```
<html>
  <head>
    <script src="scripts/utm-aska.min.js"></script>
  </head>
  <body>
    <div id="app" />
    <script>
      const utmParams = utmAska.getUtmParams()
      console.log(utmParams)
    </script>
  </body>
</html>
```

### In a web application using a bundler such as webpack:
```
import { getUtmParams } from "@norvikit/utm-aska"
const utmParams = getUtmParams()
console.log(utmParams)
```

### In a node application:

```
const utmAska = require("utm-aska");
utmAska.getUtmParams();
// or
const { getUtmParams } = require("utm-aska");
getUtmParams();
```
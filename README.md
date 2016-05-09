# px2rem-browser

v0.1.5

This is a web version of [px2rem](https://www.npmjs.com/package/px2rem) which could run in a browser.

## Usage

```
<script src="./build/px2rem.js"></script>
<script>
  var Px2rem = require('px2rem');
  var px2rem = new Px2rem();
  var originCssText = '...';
  var dpr = 2;
  var newCssText = px2remIns.generateRem(originCssText); // generate rem version stylesheet
  var newCssText = px2remIns.generateThree(originCssText, dpr); // generate @1x, @2x and @3x version stylesheet
</script>
```

## Build

Run `npm start` command.

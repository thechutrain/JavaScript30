# Notes on 01 - JavaScript Drum Kit

## Issues
- line 64: I could not use template literal syntax of es6...
```JavaScript
const audio = document.querySelector(`audio[data-key='{e.keyCode}']`);
```

### Other Features I can do:
* add a record button that will record what user plays:
  1) set a timer
  2) plays what they pressed

# js-oneliners
Javascript useful scripts in one line

### Change the first letter of a string to uppercase
```javascript
"someString".toString().split('').map((char, index) => index===0 ? char.toUpperCase() : char).join('');
```

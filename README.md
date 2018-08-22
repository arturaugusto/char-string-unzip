# char-string-unzip

```javascript
var csu = function(s){return s.split('').map(function(x,n){return !!~~x?s[n-1].repeat(~~x-1):x}).join('')}
csu('zs2z2l5')
//"zsszzlllll"
```

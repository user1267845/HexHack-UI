
# Bookmarklet
```javascript
javascript:(function(){fetch("https://raw.githubusercontent.com/user1267845/HexHack-UI/refs/heads/main/hexhack.js").then(function(a){if(!a.ok)throw new Error(a.status);return a.text()}).then(function(a){var c=new Blob([a],{type:"application/javascript"}),b=URL.createObjectURL(c),d=document.createElement("script");d.src=b;(document.head||document.documentElement).appendChild(d)})})();
```
###### full bookmarklet if you want
[bookmarklet.js](Dist/bookmarklet.js)

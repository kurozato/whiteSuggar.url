# whiteSuggar.url

replace url, convert query to array.    
write in pure javascript.

# How To Use
Quick Start
```js
//get serialize form
const form0 = document.getElementById('form0');

const searchString = whiteSuggar.url.convertSearchString(new FormData(form0));
//before -> https://host/mysite/index.html
whiteSuggar.url.replaceUrl(searchString, 'submit');
//After -> https://host/mysite/index.html?name0=value0&name1=value1&name2=value2#submit

const qry = whiteSuggar.url.querySerialize();
//qry = [{name:name0, value:value0}, {name:name1, value:value1}, {name:name2, value:value2}];
```

# Phrase object (with palindrome detector)

This is a sample NPM module created in [*Learn enough JavaScript to Be Dangerous*] (https://www.learnenough.com/javascript-tutorial).

The module can be use as follows:

```
$ npm install --global palindrome
$ vim test.js
let Phrase = require("palindrome");
let napoleonsLament = new Phrase("Able was I ere I saw Elba");
console.log(napoleonsLament.palindrome());
$node test.js
true 
```
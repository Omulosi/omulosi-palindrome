Phrase object (with palindrome detector)
=========================================

This is  sample NPM module created in [Learn Enough JavaScript to be
Dangerous](https://www.learnenough.com/javascript-tutorial).

The module can be used as follows:

```
$ npm install --global omulosi-palindrome
$ vim test.js
let Phrase = require('omulosi-palindrome');
let napoleonsLament = new Phrase("Able was I, ere I saw Elba");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```

jsmin.js
========

JS Minifier

It was originally written by Douglas Crockford 
(http://javascript.crockford.com/jsmin.html) and ported to JavaScript by 
Franck Marcia (http://www.fmarcia.info/jsmin/test.html). 

This version was patched to keep important comments (denoted with /*!) 
unchanged. The previous version of jsmin.js ate asterisk symbols and 
modified some characters as well (for example TAB was replaced by SPACE). 
Sometimes, comments should stay unchanged (for example, a function could 
keep its resources within comments). So this version does it. 

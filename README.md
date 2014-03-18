jsmin.js
========

JS Minifier

It was originally written by Douglas Crockford 
(http://javascript.crockford.com/jsmin.html) and ported to JavaScript by 
Franck Marcia (http://www.fmarcia.info/jsmin/test.html). 

This version was patched by Billy Hoffman to keep important comments (denoted with /*!) 
unchanged (http://zoompf.com/blog/2009/11/jsmin-important-comments-and-copyright-violations). 
The previous version of jsmin.js ate asterisk symbols and 
modified some characters as well (for example TAB was replaced by SPACE). 
Sometimes, comments should stay unchanged (for example, a function could 
keep its resources within comments). So this version does it. 

See the more details at the page http://with-love-from-siberia.blogspot.ru/2014/02/jsminjs-keeping-important-comments.html. Here you can find the jsmin.js.patch file once applied over the latest version of jsmin.js implements needful changes. 

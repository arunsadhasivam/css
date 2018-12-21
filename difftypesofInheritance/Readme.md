<ul class="main">
<li><div class="text1">1 ...HI</div></li>
</ul>
<div class="text2">2... HI</div>

Disadvantages of (>)
=====================

Need to mention who hierarchy to work e.g
ul>li>div.text1  if missing li like  ul>div.text1  wont work.


Advantages of (Space)
======================

since above is too huge to mention all hierarchy so inheritance with space is best.
no need to mention all things
like below.

    ul div.text1

works
=====

    ul div.text1 {
        background-color: red;
        font-weight: #000;
    }

works
=====

    ul.main div.text1 {
        background-color: red;
        font-weight: #000;
    }

not works
=========

since main class name is wrong.

    ul.main1 div.text1 {
        background-color: red;
        font-weight: #000;
    }

mix of inheritance types(>) and (.)
=========================================

works:
======

    ul>li>div.text1 {
        background-color: red;
        font-weight: #000;
    }


wont works
============

since missing li in hierarchy 

    ul>div.text1 {
        background-color: red;
        font-weight: #000;
    }



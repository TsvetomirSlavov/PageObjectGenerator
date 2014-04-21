PageObjectGenerator
===================

Page Object Generator by selecting elements from a page for Selenium Java.

#To Install
Add the following as a Bookmark

Title/Name   :  `JavaPageGenerator`


Location/URL  : `javascript:(function(){var s=document.createElement("script");s.setAttribute("type","text/javascript");s.setAttribute("src","https://raw.githubusercontent.com/rumal/PageObjectGenerator/master/script.js");var head=document.getElementsByTagName("head")[0];if(head){head.appendChild(s)}else{document.body.appendChild(s)}; return true;})()`

#How to use
1. Add the bookmark to the bookmark bar. (Refer Above on how to)
2. Goto the page you want to generate the page object.
3. Click on the bookmark
4. Right click on any elements you want to add to the page object.
5. Give a name to the element.
6. If you want to remove an element, right click on it again.
7. After adding all the elements, click on the bookmark again.
8. Give a name to the class, package and class it extends from and get the generated Java Class.

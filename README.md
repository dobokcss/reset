Reset CSS
=============================================

 My style mixed with the suggestion of [Eric Meyer CSS reset](http://meyerweb.com/eric/tools/css/reset/) and [Yahoo! (YUI 3) Reset CSS](http://cssreset.com/scripts/yahoo-css-reset-yui-3/)

# Minified

```css
/*
 * -------------------------------------------------
 * Reset CSS
 * -------------------------------------------------
 * Estefanio NS <estefanions AT gmail DOT com>
 * https://github.com/dobokcss/reset
 */

@charset "utf-8";a,abbr,acronym,address,applet,article,aside,audio,b,big,blockquote,body,canvas,caption,center,cite,code,dd,del,details,dfn,div,dl,dt,em,embed,fieldset,figcaption,figure,footer,form,h1,h2,h3,h4,h5,h6,header,hgroup,html,i,iframe,img,ins,kbd,label,legend,li,mark,menu,nav,object,ol,output,p,pre,q,ruby,s,samp,section,small,span,strike,strong,sub,summary,sup,table,tbody,td,tfoot,th,thead,time,tr,tt,u,ul,var,video{font-weight:400;font-family:inherit;font-size:100%;font-style:normal;outline:0;margin:0;padding:0;background:0 0;box-sizing:border-box;-moz-box-sizing:border-box;-webkit-box-sizing:border-box;vertical-align:baseline}body{color:#000;line-height:1}a,a:active,a:hover,a:link,a:visited,del,ins,s,strike,u{text-decoration:none}article,aside,details,figcaption,figure,footer,header,hgroup,hr,menu,nav,section{display:block}hr{height:1px;border-top:1px solid;margin:1em 0}input,select,textarea{vertical-align:middle}button,input{line-height:normal}button,html input[type=button],html input[type=reset],html input[type=submit]{cursor:pointer;-webkit-appearance:button}button,form label,input[type=button],input[type=reset],input[type=submit],input[type=radio],input[type=checkbox],select{cursor:pointer}input[type=search]{-webkit-box-sizing:content-box;-moz-box-sizing:content-box;box-sizing:content-box;-webkit-appearance:textfield}input[type=search]::-webkit-search-cancel-button,input[type=search]::-webkit-search-decoration{-webkit-appearance:none}textarea{overflow:auto;vertical-align:top}fieldset{margin:0 2px;padding:.35em .625em .75em}ol,ul{list-style:none}blockquote,q{quotes:none}blockquote:after,blockquote:before,q:after,q:before{content:'';content:none}table{border-collapse:collapse;border-spacing:0}fieldset,img{border:0}caption,th{text-align:left}:focus{outline:0}
```

# Dev
```css
@charset "utf-8";

/*
 * -------------------------------------------------
 * Reset CSS
 * -------------------------------------------------
 * Estefanio NS <estefanions AT gmail DOT com>
 * https://github.com/dobokcss/reset
 */

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center, dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
    font-weight: normal; font-family: inherit;
    font-size: 100%; font-style: normal;
    outline:0; margin:0; padding:0;  background:transparent; 
    box-sizing: border-box; -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    vertical-align: baseline; 
}

body{
    color: black; line-height: 1
}

u, s, del, ins, strike,
a, a:link, a:visited, a:hover, a:active
{
    text-decoration: none
}

figcaption,figure,footer,article,aside,details,
menu,nav,section,header,hgroup,hr{
    display: block
}

hr{
    height:1px; border-top:1px solid; margin:1em 0 
}

input,select,textarea {
    vertical-align: middle
}

button, input {
    *overflow: visible; line-height: normal 
}

button, html input[type="button"],
html input[type="reset"], 
html input[type="submit"]
{
    cursor: pointer; 
    -webkit-appearance: button
}

select,button,input[type="button"],input[type="reset"],
input[type="submit"],input[type="radio"],
input[type="checkbox"] {
    cursor: pointer
}

input[type="search"] {
    -webkit-box-sizing: content-box; 
    -moz-box-sizing: content-box;
    box-sizing: content-box; 
    -webkit-appearance: textfield
}

input[type="search"]::-webkit-search-decoration, 
input[type="search"]::-webkit-search-cancel-button {
-webkit-appearance: none
} 

textarea {
    overflow: auto; vertical-align: top
}

fieldset {
    border: 1px solid; margin: 0 2px; 
    padding: 0.35em 0.625em 0.75em 
}

ol, ul {
    list-style: none 
}

blockquote, q {
    quotes: none 
}

blockquote:before, blockquote:after,
q:before, q:after {
    content: ''; content: none; 
}

table {
    border-collapse: collapse; border-spacing: 0 
}

form label{
    cursor: pointer
}

fieldset, img {
    border: 0 none 
}

caption, th {
    text-align: left 
}

:focus {
    outline: 0 
}

```








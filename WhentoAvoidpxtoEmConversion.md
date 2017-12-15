
when converted to em it wont work correctly, if size gets increased or 
  for some css attributes,like converting from px to em not good, e.g
  
 2 things:
 =========
 
     -smaller the size px to em make em not visible at all which might be viewable in px.

     -larger the size px to em conversion will leade to reverse ie. it looks bigger than expected in em than in px. 

It is advised to changed px to em conversion only for px in range 10-18.

font-size : can be X-small,small,medium,Large,X-Large.

i.e css

font-size:medium|xx-small|x-small|small|large|x-large|xx-large|smaller|larger|length|initial|inherit;


header{

font-size:X-small;
}


X-Small-480px-10px 

Small-720px-13px   

Medium-1024px-15px

Large-1440px- 17px

X-Large-1920px- > 18px

larger: 40-50px.

  .imgHeader h1 {
margin: 35px 0 20px; } ,

converting this to equivalent is since image involved not good . so avoiding

using  px to em conversion.

 

.imgHeader h1  {
margin: 2.1875em 0 1.25em; }

 



.content-band h2 {
margin-bottom: 25px;
font-size: 38px; }  also for bigger font  sometimes it is not aligned so revert back.

 
      
      

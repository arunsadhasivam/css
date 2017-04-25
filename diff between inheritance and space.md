<style>
#table_container tr{
  color:red;

}

.tableinner tr{
  color:blue;
}

##see space applies to all childrens
## > aplies only to immediate child 
#table_container tr>td>.tableinner tr{
  color:black;
}

.tableinner>tr{
  color:black;
}

.tableouter tr{
  color:green;
}
</style>

<table id="table_container"> 

 <tr>
   <td>1 </td>
 </tr>

 <tr>
   <td> 2</td>
 </tr>

 <tr>
   <td> 
   
    <table class="tableinner">  
      <tr><td> inner table</td></tr>#########black
   
    </table>
   </td>
 </tr>

</table>

<table  class="tableouter"> 
  <tr>
    <td>outer table</td> ####green
  </tr>

</table>

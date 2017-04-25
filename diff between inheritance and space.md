<style>
#table_container tr{
  color:red;

}

.tableinner tr{
  color:blue;
}

#table_container>tableinner tr{
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
      <tr><td> inner table</td></tr>
   
    </table>
   </td>
 </tr>

</table>

<table  class="tableouter"> 
  <tr>
    <td>outer table</td>
  </tr>

</table>

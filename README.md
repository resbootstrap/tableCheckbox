# tableCheckbox

<title>Jquery表格行全选反选</title>
<link rel="stylesheet" href="css/bootstrap.min.css">

<div class="container" style="margin-top:150px;">
  第一步，引入CSS
  <code>< link rel="stylesheet" href="css/bootstrap.min.css"></code><br>
  
  第二步，引入JS
  <code>
    < script src="js/jquery-1.11.3.min.js"></script> <br>
    < script src="js/tableCheckbox.js"></script> <br>
  </code><br>
  
  第三步，调用tableCheck
  <code>$selecter.tableCheck()</code>
<hr>
   例子：选中行class为“warning”
  调用方法：<code>$("#myTable").tableCheck("warning");</code><br>
  <code>$selecter.tableCheck()</code>括号内为选中行的class，可自定义,example中使用的是Bootstrap，可用的class有 <code>waring</code>、<code>info</code>、<code>success</code>
  <script src="js/jquery-1.11.3.min.js"></script> 
  <script src="js/tableCheckbox.js"></script> 
  <script>
  $("#myTable").tableCheck("warning");
</script> 
</div>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="calculator.css">
</head>
<body>
    <h1>Yin-De calculator</h1>
<div class="cal">
   <table>
      
         <input id="text" type="text">
      
   <tr>
      <td><input type="button" onclick="cal()" value="MC"></td>
      <td><input type="button" onclick="cal(0)" value="0"></td>
      <td><input type="button"  onclick="cal(1)" value="1"></td>
      <td><input type="button"  onclick="cal(2)" value="2"></td>
      <td><input type="button"  onclick="cal('+')" value="+"></td>
   </tr>
   <tr>
   <td><input type="button" onclick="cal()" value="MS"></td>
   <td><input type="button" onclick="cal(3)" value="3"></td>
   <td><input type="button" onclick="cal(4)" value="4"></td>
   <td><input type="button" onclick="cal(5)" value="5"></td>
   <td><input type="button" onclick="cal('-')" value="-"></td>
   </tr>
   <tr>
      <td><input type="button" onclick="cal()" value="MR"></td>
      <td><input type="button" onclick="cal(6)" value="6"></td>
      <td><input type="button" onclick="cal(7)" value="7"></td>
      <td><input type="button" onclick="cal(8)" value="8"></td>
      <td><input type="button" onclick="cal('*')" value="*"></td>
      </tr>
      <tr>
         <td><input type="button" onclick="cal()" value="M+"></td>
         <td><input type="button" onclick="cal(9)" value="9"></td>
         <td><input type="button" onclick="cal()" value="+-"></td>
         <td><input type="button" onclick="Result()" value="="></td>
         <td><input type="button" onclick="cal('/')" value="/"></td>
         </tr>
         <tr>
            <td><input type="button" onclick="del()" value="DEL"></td>
            <td><input type="button" onclick="cal('.')" value="."></td>
            <td><input type="button" onclick="cal()" value="×2"></td>
            <td><input type="button" onclick="cal()" value="√"></td>
            <td><input type="button" onclick="clr()" value="C"></td>
            </tr>
   </table>
  
</div>
<script src="calculator.js"></script>
</body>
</html>

<html>
<head>
<style>
#yuo { background-color:white;
color:blue; font-size:50px; 
height:200px;
width :529px;
 border:10px solid;
border-bottom-color:#009900;/* Green */
border-top-color:#FF0000;/* Red */
border-left-color:#330000;/* Black */
border-right-color:#0000CC;/* Blue */
} 

#yui { background-color:yellow;
color:blue; 
font-size:80px; 
width:130px; 
height:130px; 
 border:10px solid;
border-bottom-color:#009900;/* Green */
border-top-color:#FF0000;/* Red */
border-left-color:#330000;/* Black */
border-right-color:#0000CC;/* Blue */
} 

#ypi { border:10px solid;
border-top-color:#009900;/* Green */
border-bottom-color:#FF0000;/* Red */
border-right-color:#330000;/* Black */
border-left-color:#0000CC;/* Blue */ }
body-color:gray


</style>
</head>

<body>
<FORM NAME="Calc"> <TABLE id="ypi" BORDER=4> <TR><TD>
<INPUT id="yuo" TYPE="text" NAME="Input" Size="16px">

           <br> 

           
         </TD></TR>
            <TR><TD>
<INPUT id="yui" TYPE="button" NAME="one" VALUE="1" onclick="Calc.Input.value +='1'">
<INPUT id="yui" TYPE="button" NAME="two" VALUE="2" onclick="Calc.Input.value +='2'">
<INPUT id="yui" TYPE="button" NAME="three" VALUE="3" onclick="Calc.Input.value +='3'">
<INPUT id="yui" TYPE="button" NAME="plus" VALUE="+" onclick="Calc.Input.value +='+'">

           <br>
         
           
           
<INPUT id="yui" TYPE="button" NAME="four" VALUE="4" onclick="Calc.Input.value +='4'">
<INPUT id="yui" TYPE="button" NAME="five" VALUE="5" onclick="Calc.Input.value +='5'">
<INPUT id="yui" TYPE="button" NAME="six" VALUE="6" onclick="Calc.Input.value +='6'">
<INPUT id="yui" TYPE="button" NAME="minus" VALUE="-" onclick="Calc.Input.value +='-'">
            
            <br>

<INPUT id="yui" TYPE="button" NAME="seven" VALUE="7" onclick="Calc.Input.value +='7'">
<INPUT id="yui" TYPE="button" NAME="eight" VALUE="8" onclick="Calc.Input.value +='8'">
<INPUT id="yui" TYPE="button" NAME="nine" VALUE="9" onclick="Calc.Input.value +='9'">
<INPUT id="yui" TYPE="button" NAME="times" VALUE="×" onclick="Calc.Input.value +='*'">
      
         <br id="UIO">
         
<INPUT id="yui" TYPE="button" NAME="clear" VALUE="c" onclick="Calc.Input.value =''">
<INPUT id="yui" TYPE="button" NAME="zero" VALUE="0" onclick="Calc.Input.value +='0'"> 
<INPUT id="yui" TYPE="button" NAME="Dolt" VALUE="=" onclick="Calc.Input.value += 
value +
eval(Calc.Input.value)">
<INPUT id="yui" TYPE="button" NAME="div" VALUE="/" onclick="Calc.Input.value +='/'">



         
</TD></TR> </TABLE></FORM>




</body>







</html>

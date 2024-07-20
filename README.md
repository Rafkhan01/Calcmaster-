<html>  
    <HEAD><TITLE>Calculator Made By Rafkhan</TITLE>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
        body {
	animation-name: backgroundColorPalette;
	animation-duration: 5s;
	animation-iteration-count: infinite;
	animation-direction: alternate;
	animation-timing-function: linear; 	
}

@keyframes backgroundColorPalette {
	0% {
    background: #8f00ff;
  }
  10% {
    background: #ff00b2;
  }
  20% {
    background: #ff000a;
  }
  30% {
    background: #ff7300;
  }
  40% {
    background: #fff100;
  }
  50% {
    background: #50ff00;
  }
  60% {
    background: #00ffc0;
  }
  70% {
    background: #00c0ff;
  }
  80%{
      background: #0057ff;
  }
  90%{
      background: #3b00ff;
  }
  100%{
      background: #a400ff;
  }
}

        .button {
  background-color: #a400ff;
  border: none;
  color: #00ffff;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}  
.button:hover{
    background-color:gold;
}
        .button1 {
  background-color:#ff0073 ;
  border: none;
  color: #00ffd5;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}  
     .button2 {
  background-color:white ;
  border: none;
  color: black;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}  
textarea{
    font-weight:bold;
    color:red;
    top:50%;
    text-align:right;
    text-shadow:3px 3px 3px green;
    
}

    </style><!-- for webpage -->
    <style>
        .rainbow {
  border: 5px solid transparent;
  border-image: linear-gradient(to bottom right, #b827fc 0%, #2c90fc 25%, #b8fd33 50%, #fec837 75%, #fd1892 100%);
  border-image-slice: 1;
  margin: 20px auto; 
}
</style><!-- script for fafa heart -->
    <script src='https://kit.fontawesome.com/a076d05399.js'></script>
    <SCRIPT>
        var a,b,c,d,e;
        a=prompt ("Please Enter your name:");
        b="<center>";
        c="</center>";
        d="<hr>";
        e=a[a.length-1];
        f=a[a.length-2];
        if (e=='a' || e=='e' || e=='i' || e=='o' || e=='u' ){
       onload = function() { 
       button=document.createElement('span');
        text=document.createTextNode(" "+"Miss."+" "+a);
        button.appendChild(text);
        var myDiv=document.getElementById("br");
        myDiv.appendChild(button); }
        }
        else if(f=='c')
        {
        onload = function() { 
       button=document.createElement('span');
        text=document.createTextNode(" "+"Miss."+" "+a);
        button.appendChild(text);
        var myDiv=document.getElementById("br");
        myDiv.appendChild(button); }
        }
        else
        {
        onload = function() { 
       button=document.createElement('span');
        text=document.createTextNode(" "+"Mr."+" "+a);
        button.appendChild(text);
        var myDiv=document.getElementById("br");
        myDiv.appendChild(button); }
        }
    </SCRIPT>
    </HEAD>
<body bgcolor="#ff0088" align="right" Link="red" Alink="green" onunload="Close()"> 
    <div class="rainbow"><br>
    <center>
        <i class="fa fa-heart-o" style="font-size:24px;"></i>&nbsp
        <span id="br" ondblclick="pic()">Welcome</span>&nbsp<span class="fa fa-heart-o" style="font-size:24px;"></span><hr>
    </center>
    <br><center><h2>
        <table border="3" bordercolor="gold"><tr><td bgcolor="blue">
<br><CENTER><h2><details>
    <summary><FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>Basic Calculator </i></u></FONT></summary>      
  <TABLE border="2">
        <TR><TD bgcolor="gold">
            <FORM NAME="frm">
                <CENTER>
                    
                     <textarea name="txt1" rols="5" cols="32" placeholder="Enter the calculation"></textarea>
                 <BR>
            <br><table border="1"><tr><td bgcolor="red">
<button type="button" onClick="one()" class="button">1
</button>&nbsp</td>&nbsp<td bgcolor="red">
<button type="button" class="button" onClick="two()">2</button>&nbsp</td>&nbsp<td bgcolor="red">
    <button type="button" class="button" onClick="three()">3
</button>&nbsp</td></tr><tr><td bgcolor="red">
<button type="button" class="button" onClick="four()">4
</button>&nbsp</td><td bgcolor="red">
<button type="button" class="button" onClick="five()">5
</button><br></td><td bgcolor="red">
<button type="button" class="button" onClick="six()">6
</button>&nbsp</td></tr><tr><td bgcolor="red">
<button type="button" class="button" onClick="seven()">7
</button>&nbsp</td><td bgcolor="red">
<button type="button" class="button" onClick="eight()">8
</button>&nbsp</td><td bgcolor="red">
<button type="button" class="button" onClick="nine()">9
</button>&nbsp</td></tr><tr><td bgcolor="red">
<button type="button" class="button" onClick="zero()">0
</button>&nbsp</td><td bgcolor="green">
<button type="button" class="button1" onClick="plus()">+</button></td><td bgcolor="green">
<button type="button" class="button1" onClick="minus()">-</button></td></tr><tr><td bgcolor="green">
    <button type="button" class="button1" onClick="mult()">x</button>
</td>
<td bgcolor="green"><button type="button" class="button1" onClick="div()">/</button><br></td><td bgcolor="black">
<INPUT Type="Reset" class="button2" Value="AC">&nbsp</td></tr>
<tr><td></td><td bgcolor="black">
<button type ="button" class="button2" onClick="Print()">=</button>&nbsp</td>   
              <td></CENTER>
            </FORM>
        </td></tr></table></TD></TR></TABLE></details>
    </h2></center>
    <hr size="10" Align="center" color="red">
<br><CENTER><h2><details>
    <summary><FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>Scientific Calculator</i></u></FONT></summary>      
  <TABLE BORDER="5" bordercolor="green"><TR><TD bgcolor="red">
    <FORM NAME="frmSum">
        <CENTER>
            Enter number n 
            <INPUT Type="text" Name="txt1">
            <BR>
            <table border="1" bgcolor="#e300ff"><tr><td>
<button type="button" onClick="on()">1
</button>&nbsp</td>&nbsp<td>
<button type="button" onClick="tw()">2</button>&nbsp</td>&nbsp<td>
    <button type="button" onClick="thre()">3
</button>&nbsp</td><td>
<button type="button" onClick="fou()">4
</button>&nbsp</td><td>
<button type="button" onClick="fiv()">5
</button><br></td><td>
<button type="button" onClick="si()">6
</button>&nbsp</td><td>
<button type="button" onClick="seve()">7
</button>&nbsp</td><td>
<button type="button" onClick="eigh()">8
</button>&nbsp</td><td>
<button type="button" onClick="nin()">9
</button>&nbsp</td><td>
<button type="button" onClick="zer()">0
</button>&nbsp</td></tr></table>

            <br><b><u><i> Choose method: </i></u></b><br>  
<input type="radio" id="x^n" value="x^n">x<sup>n</sup>&nbsp
<input type="radio" id="npr" value="npr">npr&nbsp
<input type="radio" id="ncr" value="ncr">ncr&nbsp
<input type="radio" id="nrootx" value="nrootx">nroot(x)

<br>
<button type="button" onClick="sqt()">root(x)</button>&nbsp
<button type="button" onClick="fact()">n!</button>&nbsp
<button type="button" onClick="sqr()">x<sup>2</sup></button>&nbsp
<button type="button" onClick="cube()">x<sup>3</sup></button>&nbsp
<button type="button" onClick="cuberoot()">cuberoot</button>&nbsp
<button type="button" onClick="hm()">hr to min</button><br>
<button type="button" onClick="hs()">hr to s</button>&nbsp
<button type="button" onClick="hms()">s to h:m:s</button>&nbsp
<button type="button" onClick="ctof()">celsius to farentheit</button>&nbsp
<button type="button" onClick="sin()">sin()</button>&nbsp
<br>
            Enter Number r
            <INPUT Type="text" Name="txt2">
            <BR>
            <table border="1" bgcolor="#ce00ff"><tr><td>
<button type="button" onClick="ona()">1
</button>&nbsp</td>&nbsp<td>
<button type="button" onClick="twa()">2</button>&nbsp</td>&nbsp<td>
    <button type="button" onClick="threa()">3
</button>&nbsp</td><td>
<button type="button" onClick="foua()">4
</button>&nbsp</td><td>
<button type="button" onClick="fiva()">5
</button><br></td><td>
<button type="button" onClick="sia()">6
</button>&nbsp</td><td>
<button type="button" onClick="sevea()">7
</button>&nbsp</td><td>
<button type="button" onClick="eigha()">8
</button>&nbsp</td><td>
<button type="button" onClick="nina()">9
</button>&nbsp</td><td>
<button type="button" onClick="zera()">0
</button>&nbsp</td></tr></table>
            The Sum is &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
            <INPUT Type="text" Name="xyz">
            <BR><BR>
            </TD></TR>
            </CENTER>
            <TR><TD bgcolor="#00ffc0">
            <CENTER>
            <button type="button" onclick=" checkButton()"> Submit </button>&nbsp
            <INPUT Type="Reset" Value="AC">&nbsp
            <button type="button" onClick="avg()">Average</button>
            </CENTER>
            </TD></TR>
            </FORM>
            </TABLE></details></h2></CENTER>
            <hr size="10" Align="center" color="red">
            <center><h2><details>
   <summary><FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>Number Conversion</i></u></FONT></summary>
            <br><br>
            <CENTER><FORM Name="frmconvrt">
            <TABLE BORDER="3">
                <TR> <TD bgcolor="#00ff2d">
                <center>
                    <FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>Number Conversion</i></u></FONT><br>
                    Enter The Number 
                    <input type="text" Name="num"><br>
                    The converted number is
                    <input type="text" Name="cnum"><br>
                <button type="button" onClick="dtob()">10to2()</button>&nbsp
                <button type="button" onClick="dtoO()">10to8()</button>&nbsp
                <button type="button" onClick="dtoh()">10to16()</button>
                <button type="button" onClick="btod()">2to10</button>&nbsp
                <button type="button" onClick="otod()">8to10</button>&nbsp
                <button type="button" onClick="htod()">16to10</button>&nbsp
                <button type="button" onClick="btoO()">2to10</button>&nbsp
                <button type="button" onClick="btoh()">2to16</button>&nbsp
                <button type="button" onClick="otob()">8to2</button>&nbsp
                <button type="button" onClick="Otoh()">8to16</button>
                <INPUT Type="Reset" Value="AC">&nbsp
                </center>
                </TD></TR>
            </TABLE></FORM></CENTER></details></h2></center><hr size="10" Align="center" color="red">
            <center><h2><details><summary>
 <FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>Simple Interest</i></u></FONT></summary>
            <table border="3"><tr><td bgcolor="#ff0088">
                <FORM NAME="frminterest">
                Enter the value
                <input type="text" name="val"><br>
                Enter the number of years
                <input type="text" name="nyear"><br>
                Enter the Percentage of interest
                <input type="text" name="inter"><br>
                The answer is
                <input type="text" name="ans"><br>
                <button type="button" onClick="interest ()">Find</button>
                <input type="reset" value="AC"></FORM>
                </td></tr></table></details></h2></center>
                <hr size="10" Align="center" color="red">
               <center><h2><details><summary>
<FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>Trignometry functions</i></u></FONT></summary>
               <table border="3" bordercolor="green"><tr><td><form name="frmtrig">
               Enter the value of x
               <input type="text" name="x"><br>
               The value of the function is 
               <input type="text" name="y">
               <center><button type="button" onClick="sin()">sin()</button>
               <button type="button" onClick="cos()">cos()</button>
               <button type="button" onClick="tan()">tan()</button>
               <button type="button" onClick="sec()">sec()</button>
               <button type="button" onClick="cosec()">cosec()</button>
               <button type="button" onClick="cot()">cot()</button>
               </center>
               </form></td></tr></table>
               </details></h2></center>
               <hr size="10" Align="center" color="red">
               <center><h2><details><summary>
 <FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>Matrix and Determinant</i></u></FONT></summary>
               <table border="3" bordercolor="gold"><tr><td><button type="button" onClick="matrix()">Matrix Multiplication</button><br>
               <button type="button" onClick="matrix()">A<sup>-1</sup></button>
           &nbsp <button type="button" onClick="matrix()">|A|</button></td></tr>
           </table></details></h2></center>
           <hr size="10" Align="center" color="red">
<center><h2><details><summary><FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>For String</i></u></FONT></summary><form name="frmstrg">
<table border="3" bordercolor="gold"><tr><td>
    Enter the String 
    <input type="text" name="str"><br>
    The Answer is &nbsp
    <input type="text" name="stg">
    
<center><button type="button" onClick="pyrmd()">Print name in pyramid</button>&nbsp&nbsp&nbsp
    <button type="button" onClick="rev()">Reverse name</button>&nbsp
    <button type="button" onClick="len()">length of character</button></center></td></tr></table>
    </form></details></h2></center>
    <hr size="10" Align="center" color="red"> 
    <center><h2><details><summary>
<FONT COLOR="#ff0073" FACE="Courier New" SIZE="4"><u><i>Number to Word</i></u></FONT></summary>
               <table border="3" bordercolor="green"><tr><td><form name="frmcnvrt">
               Enter the Number 
               <input type="text" placeholder="Number in digits" name="a1">
               <br>
               In Words  <br>
               <textarea  name="a2" rows="5" cols="35">
        </textarea><br>
       
              
               <center>
<button type="button" onClick="ntowini()">Indian <br> Number <br> System</button>&nbsp
<button type="button" onClick="ntow()">International <br> Number <br> System</button>
               &nbsp<INPUT Type="Reset" Value="Clear All"></center>
               </form>
</td></tr></table></details></center>
    <hr size="10" Align="center" color="red"> 
<details><summary><b><i><u>Contact Me</u></i></b></summary>
                <a href="tel:8129925845">Contact Rafkhan</a><br><br>
                <a href=mailto:"rafkhanb0@gmail.com">
    Mail</a>
                <br>
                <a href="https://wa.me/8129925845">WhatsApp </a>
              <br> <a href="https://www.instagram.com/r_afkhan">Instagram</a> 
                </details><!--  
<details><summary><i><b>Contact my Friends
</b></i></summary>
<table border="3" bordercolor="gold">
<tr><td>Call</td><td>WhatsApp</td><td>Mail
</td></tr>
<tr><td><a href="tel:+91 75920 64546">Adhithyan</a></td>
<td><a href="https://wa.me/75920 64546">Adhithyan</a></td><td>Null</td></tr>
<tr><td><a href="tel:+91 94006 93363">Afzal B R</a></td>
<td><a href="https://wa.me/+91 94006 93363">Afzal B R</a></td><td><a href=mailto:"afsalafsu9870@gmail.com">Afzal B R</a></td></tr>
<tr><td><a href="tel:+91 90489 20366">Ajmal
</a></td>
<td><a href="https://wa.me/9048920366">Ajmal</a></td>
<td><a href=mailto:"idofajmalmohdazim@gmail.com">
    Ajmal</a></td></tr>
<tr><td><a href="tel:+91 96334 61324">Farhana</a></td>
<td><a href="https://wa.me/+91 96334 61324">Farhana</a></td>
<td><a href=mailto:"fn83860@gmail.com">
    Farhana 
</a></td></tr>
<tr><td><a href="tel:+91 6282 323 174">Kalyani</a></td>
<td><a href="https://wa.me/+91 6282 323 174">Kalyani</a></td><td>Null</td></tr>
<tr><td><a href="tel:1+91 82818 21140">Ganga</a></td>
<td><a href="https://wa.me/+91 82818 21140">Ganga</a></td><td>Null</td></tr>
</table></details> -->
</tr></table></h1>
<footer>Last Opened By:
<div id="demo"></div></footer>
</div>
</body>  

<script>  <!-- for basic calc -->
    function one()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+1;
    document.frm.txt1.value=b;
}
function two()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+2;
    document.frm.txt1.value=b;
}
function three()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+3;
    document.frm.txt1.value=b;
}
function four()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+4;
    document.frm.txt1.value=b;
}
function five()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+5;
    document.frm.txt1.value=b;
}
function six()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+6;
    document.frm.txt1.value=b;
}
function seven()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+7;
    document.frm.txt1.value=b;
}
function eight()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+8;
    document.frm.txt1.value=b;
}
function nine()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+9;
    document.frm.txt1.value=b;
}
function zero()
{
    var a,b;
    a=document.frm.txt1.value;
    b=a+0;
    document.frm.txt1.value=b;
}
function plus()
{
    var a,b,c;
    a=document.frm.txt1.value;
    c="+";
    b=a+c;
    document.frm.txt1.value=b;
}
function minus()
{
    var a,b,c;
    a=document.frm.txt1.value;
    c="-";
    b=a+c;
    document.frm.txt1.value=b;
}
function mult()
{
    var a,b,c;
    a=document.frm.txt1.value;
    c="*";
    b=a+c;
    document.frm.txt1.value=b;
}
function div()
{
    var a,b,c;
    a=document.frm.txt1.value;
    c="/";
    b=a+c;
    document.frm.txt1.value=b;
}
function Print()
{
    var a,b,c,d;
    a=document.frm.txt1.value;
    b=eval(a);
    document.frm.txt1.value=b;
    
}
function on()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+1;
    document.frmSum.txt1.value=b;
}
function tw()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+2;
    document.frmSum.txt1.value=b;
}
function thre()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+3;
    document.frmSum.txt1.value=b;
}
function fou()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+4;
    document.frmSum.txt1.value=b;
}
function fiv()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+5;
    document.frmSum.txt1.value=b;
}
function si()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+6;
    document.frmSum.txt1.value=b;
}
function seve()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+7;
    document.frmSum.txt1.value=b;
}
function eigh()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+8;
    document.frmSum.txt1.value=b;
}
function nin()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+9;
    document.frmSum.txt1.value=b;
}
function zer()
{
    var a,b;
    a=document.frmSum.txt1.value;
    b=a+0;
    document.frmSum.txt1.value=b;
}
function ona()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+1;
    document.frmSum.txt2.value=b;
}
function twa()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+2;
    document.frmSum.txt2.value=b;
}
function threa()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+3;
    document.frmSum.txt2.value=b;
}
function foua()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+4;
    document.frmSum.txt2.value=b;
}
function fiva()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+5;
    document.frmSum.txt2.value=b;
}
function sia()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+6;
    document.frmSum.txt2.value=b;
}
function sevea()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+7;
    document.frmSum.txt2.value=b;
}
function eigha()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+8;
    document.frmSum.txt2.value=b;
}
function nina()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+9;
    document.frmSum.txt2.value=b;
}
function zera()
{
    var a,b;
    a=document.frmSum.txt2.value;
    b=a+0;
    document.frmSum.txt2.value=b;
}
function checkButton() {    
          var a,b,c=1;
         a=Number(document.frmSum.txt1.value);
         b=Number(document.frmSum.txt2.value); if(document.getElementById('x^n').checked) {
                for(i=0;i<b;i++)
                c=c*a;
                document.frmSum.xyz.value=c;
            }
            else if(document.getElementById('npr').checked)
            {
                var z,n=1,r=1,npr,i;
                if(a<b)
        {
            alert("Please enter valid value n>=r>=0")
            return;
        }
        else
        {
        for(i=1;i<=a;i++)
        n=n*i;
        z=a-b;
        for(i=1;i<=z;i++)
        r=r*i;
        npr=n/r;
        document.frmSum.xyz.value=npr;
        }
            }
            else if(document.getElementById('ncr').checked)
            {
                var x,ncr,i,n=1,r=1,y=1;
                if(a<b)
        {
            alert("please enter valid value n>=r>=0")
            return;
        }
        else
        {
        for(i=1;i<=a;i++)
        n=n*i;
        x=a-b;
        for(i=1;i<=x;i++)
        r=r*i;
        for(i=1;i<=b;i++)
        y=y*i;
        ncr=n/(y*r);
        document.frmSum.xyz.value=ncr;
        }
           }
           else if(document.getElementById('nrootx'). checked){
               var c,d;
               c=Math.pow(a,1/b);
               d=Math.round(c);
               document.frmSum.xyz.value=d;
           }
            else
alert("You have not selected any method");    
        }   
        function sqt()
        {
        var c;
        a=Number (document.frmSum.txt1.value);
            c=Math.sqrt(a);
            document.frmSum.xyz.value=c;
        }
        function fact()
        {
            var a,i,c=1;
            a=Number(document.frmSum.txt1.value);
            for(i=1;i<=a;i++)
            c=c*i;
            document.frmSum.xyz.value=c;
        }
        function sqr()
        {
            var a,c;
            a=Number (document.frmSum.txt1.value)
            c=a*a;
            document.frmSum.xyz.value=c;
        }
        function cube()
        {
        var a,b;
            a=Number (document.frmSum.txt1.value);
            b=(a*a)*a;
            document.frmSum.xyz.value=b;
        }
        function cuberoot()
        {
            var a,b;
            a=Number (document.frmSum.txt1.value);
            b=Math.cbrt(a);
            document.frmSum.xyz.value=b;
        }
        function hm()
        {
            var a,b;
            a=Number (document.frmSum.txt1.value);
            b=a*60;
            document.frmSum.xyz.value=b;
        }
        function hs()
        {
            var a,b;
            a=Number (document.frmSum.txt1.value);
            b=a*3600;
            document.frmSum.xyz.value=b;
        }
        function hms()
        {
            var s,m,h,x,y;
            var a;
            s=Number(document.frmSum.txt1.value);
          a=":";
          x=s/3600;
          h=Number.parseInt(x);          
          s=s%3600;
          y=s/60;
          m=Number.parseInt(y);
          s=s%60;
          document.frmSum.xyz.value=h+a+m+a+s;
          
        }
        function ctof()
        {
            var a,b;
            a=Number (document.frmSum.txt1.value);
            b=1.8*a+32;
            document.frmSum.xyz.value=b;
                }
        function dtob()
        {
            var x,y;
            x=Number (document.frmconvrt.num.value);
            y=x.toString(2);
            document.frmconvrt.cnum.value=y;
        }
        function dtoO()
        {
            var a,b;
            a=Number (document.frmconvrt.num.value);
            b=a.toString(8);
            document.frmconvrt.cnum.value=b;
        }
        function dtoh()
        {
            var a,b;
            a=Number (document.frmconvrt.num.value);
            b=a.toString(16);
            document.frmconvrt.cnum.value=b;
        }
        function btod()
        {
            var a,b;     a=Number(document.frmconvrt.num.value);
            b=parseInt(a,2);
            document.frmconvrt.cnum.value=b;
        }
        function otod()
        {
            var a,b;
            a=Number (document.frmconvrt.num.value);
            b=parseInt(a,8);
            document.frmconvrt.cnum.value=b;
        }
        function htod()
        {
        var a,b;
        a=document.frmconvrt.num.value;
        b=parseInt(a,16);
        document.frmconvrt.cnum.value=b;
        }
        function btoO()
        {
            var a,b,c;
            a=Number(document.frmconvrt.num.value);
            b=parseInt(a,2);
            c=b.toString(8);
            document.frmconvrt.cnum.value=c;
        }
        function btoh()
        {
            var a,b,c;
            a=Number(document.frmconvrt.num.value);
            b=parseInt(a,2);
            c=b.toString(16);
            document.frmconvrt.cnum.value=c;
        }
        function otob()
        {
            var a,b,c;
            a=Number (document.frmconvrt.num.value);
            b=parseInt(a,8);
            c=b.toString(2);
            document.frmconvrt.cnum.value=c;
        }
        function Otoh()
        {
            var a,b,c,d,e;
            a=document.frmconvrt.num.value;
            b=parseInt(a,8);
            c=b.toString(2);
            d=parseInt(c,2);
            e=d.toString(16);
            document.frmconvrt.cnum.value=e;
        }
        function interest ()
        {
            var a,b,c,d;
            a=Number (document.frminterest.val.value);
            b=Number (document.frminterest.nyear.value);
            c=Number (document.frminterest.inter.value);
            d=a*b*c/100;
            document.frminterest.ans.value=d;
        }
        function avg()
        {
            var i,n,score,avg,sum=0;
            n=prompt("How many Values taking average ");
            for (i=1;i<=n;++i)
            {
                score=prompt("Please Enter the Value  "+i);
                sum=Number (sum)+Number (score);
            }
            avg=sum/n;
            document.frmSum.xyz.value=avg;
        }
        function sin()
        {
            var a,b,c;
            a=Number (document.frmtrig.x.value);
            b=Math.sin(a*(3.14/180));
            c=b.toFixed(2);
            document.frmtrig.y.value=c;
        }
        function cos()
        {
            var a,b,c;
            a=Number (document.frmtrig.x.value);
            b=Math.cos(a*3.14/180);
            c=b.toFixed(2);
            document.frmtrig.y.value=c;
        }
        function tan()
        {
            var a,b,c;
            a=Number (document.frmtrig.x.value);
            b=Math.tan(a*3.14/180);
            c=b.toFixed(2);
            document.frmtrig.y.value=c;
        }
        function cosec()
        {
            var a,b,c;
            a=Number (document.frmtrig.x.value);
            b=Math.sin(a*3.14/180);
            c=1/b;
            d=c.toFixed(2);
            document.frmtrig.y.value=d;
        }
        function sec()
        {
            var a,b,c;
            a=Number (document.frmtrig.x.value);
            b=Math.cos(a*3.14/180);
            c=1/b;
            d=c.toFixed(2);
            document.frmtrig.y.value=d;
        }
        function cot()
        {
            var a,b,c;
            a=Number (document.frmtrig.x.value);
            b=Math.tan(a*3.14/180);
            c=1/b;
            d=c.toFixed(2);
            document.frmtrig.y.value=d;
      }
      function pyrmd()
        {
            var a,b,i,j,c,d,e,f;
            a=document.frmstrg.str.value;
            b=a.toUpperCase();
            f=" ";
            c="Thank you "+a+f+"for visiting my website ";
            alert(c);
            document.write("<center>");
            for(i=0;i<b.length;i++)
            {
                for(j=0;j<=i;j++)
                document.write(b[j]+"&nbsp");
                document.write("<br>");
            }
                  document.write("</center>");    
        }
        function rev()
        {
            var a,b="",i,c;
            c=document.frmstrg.str.value;
            a=c.toUpperCase();
            for (i=a.length-1;i>=0;i--)
            {
                b+=a[i];
            }
            document.frmstrg.stg.value=b;
        }
        function len()
        {
            var a,b;
            a=document.frmstrg.str.value;
            b=a.length;
            document.frmstrg.stg.value=b;
        }
        </script>
        <script>
        function ntow(){
var a=document.frmcnvrt.a1.value;
var i,b,c,x;
b=a;
c=a.slice(3);
for (i=1;i<=15;i++){
x=document.frmcnvrt.a2.value;
if (a=='0'){
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.charAt(0)=='1' && (a.length=='2' || a.length=='5' || a.length=='8' || a.length=='11' || a.length=='14'))
{
if (a. charAt(1)=='1'){
document.frmcnvrt.a2.value=(x+"Eleven ");
if (a.length=='5'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Thousand ");}
else if(a.length=='8'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Million ");}
else if(a.length=='11'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Billion ");}
else if(a.length=='14'){
    x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Trillion");
}}
else if(a. charAt(1)=='2'){
document.frmcnvrt.a2.value=(x+"Twelve ");
if (a.length=='5'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Thousand ");}
else if(a.length=='8'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Million ");}
else if(a.length=='11'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Billion ");}
else if(a.length=='14'){
    x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Trillion");
}}
else if(a. charAt(1)=='3'){
document.frmcnvrt.a2.value=(x+"Thirteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='8')
document.frmcnvrt.a2.value=(x+"Million ");
else if(a.length=='11')
document.frmcnvrt.a2.value=(x+"Billion ");
else if(a.length=='14')
document.frmcnvrt.a2.value=(x+"Trillion ");}
else if(a. charAt(1)=='4'){
document.frmcnvrt.a2.value=(x+"Fourteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='8')
document.frmcnvrt.a2.value=(x+"Million ");
else if(a.length=='11')
document.frmcnvrt.a2.value=(x+"Billion ");
else if(a.length=='14')
document.frmcnvrt.a2.value=(x+"Trillion ");}
else if(a. charAt(1)=='5'){
document.frmcnvrt.a2.value=(x+"Fifteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='8')
document.frmcnvrt.a2.value=(x+"Million ");
else if(a.length=='11')
document.frmcnvrt.a2.value=(x+"Billion ");
else if(a.length=='14')
document.frmcnvrt.a2.value=(x+"Trillion ");}
else if(a. charAt(1)=='6'){
document.frmcnvrt.a2.value=(x+"Sixteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='8')
document.frmcnvrt.a2.value=(x+"Million ");
else if(a.length=='11')
document.frmcnvrt.a2.value=(x+"Billion ");
else if(a.length=='14')
document.frmcnvrt.a2.value=(x+"Trillion ");}
else if(a. charAt(1)=='7'){
document.frmcnvrt.a2.value=(x+"Seventeen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='8')
document.frmcnvrt.a2.value=(x+"Million ");
else if(a.length=='11')
document.frmcnvrt.a2.value=(x+"Billion ");
else if(a.length=='14')
document.frmcnvrt.a2.value=(x+"Trillion ");}
else if(a. charAt(1)=='8'){
document.frmcnvrt.a2.value=(x+"Eighteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='8')
document.frmcnvrt.a2.value=(x+"Million ");
else if(a.length=='11')
document.frmcnvrt.a2.value=(x+"Billion ");
else if(a.length=='14')
document.frmcnvrt.a2.value=(x+"Trillion ");}
else if(a. charAt(1)=='9'){
document.frmcnvrt.a2.value=(x+"Nineteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='8')
document.frmcnvrt.a2.value=(x+"Million ");
else if(a.length=='11')
document.frmcnvrt.a2.value=(x+"Billion ");
else if(a.length=='14')
document.frmcnvrt.a2.value=(x+"Trillion ");}

else if(a.charAt(1)=='0'){
x=document.frmcnvrt.a2.value;
    if (a.length=='2')
    document.frmcnvrt.a2.value=(x+"Ten");
    else if(a.length=='5')
    document.frmcnvrt.a2.value=(x+"Ten Thousand "); 
    else if(a.length=='8')  
    document.frmcnvrt.a2.value=(x+"Ten Million ");
    else if(a.length=='11')
document.frmcnvrt.a2.value=(x+"Ten Billion ");
    else if(a.length=='14')
document.frmcnvrt.a2.value=(x+"Ten Trillion ");
}
else
document.frmcnvrt.a2.value=(x+" ");
a=a.slice(1);
}
else{
if (a.length=='1')
{
    if (a=='1')
    document.frmcnvrt.a2.value=(x+"One");
    else if(a=='2')
    document.frmcnvrt.a2.value=(x+"Two");
    else if(a=='3')
    document.frmcnvrt.a2.value=(x+"Three");
    else if(a=='4')
    document.frmcnvrt.a2.value=(x+"Four");
    else if(a=='5')
    document.frmcnvrt.a2.value=(x+"Five");
    else if(a=='6')
    document.frmcnvrt.a2.value=(x+"Six");
    else if(a=='7')
    document.frmcnvrt.a2.value=(x+"Seven");
    else if(a=='8')
    document.frmcnvrt.a2.value=(x+"Eight");
    else if(a=='9')
    document.frmcnvrt.a2.value=(x+"Nine");
    else 
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='2' || a.length=='5' || a.length=='8' || a.length=='11' || a.length=='14'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"Ten ");
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Twenty ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Thirty ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Forty ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Fifty ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Sixty ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seventy ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eighty ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Ninety ");
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='3' || a.length=='6' || a.length=='9' || a.length=='12' || a.length=='15'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Hundred ");
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Hundred ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Hundred ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Hundred ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Hundred ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Hundred ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Hundred ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Hundred ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Hundred ");
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='4'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Thousand ")
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Thousand ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Thousand ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Thousand ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Thousand ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Thousand ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Thousand ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Thousand ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Thousand ");
    else if(a.charAt(0)=='0'){
    if (b.length=='5' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='6' && (b.charAt(1)!='0' || b.charAt(0)!='0'))
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='7' && (b.charAt(2)!='0' || b.charAt(1)!='0'))
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='8' && (b.charAt(3)!='0' || b.charAt(2)!='0'))
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='9' && (b.charAt(4)!='0' || b.charAt(3)!='0'))
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='10' && (b.charAt(5)!='0' || b.charAt(4)!='0'))
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='11' && (b.charAt(6)!='0' || b.charAt(5)!='0'))
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='12' && (b.charAt(7)!='0' || b.charAt(6)!='0'))
    document.frmcnvrt.a2.value=x+"Thousand ";
    }
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='7'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Million ")
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Million ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Million ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Million ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Million ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Million ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Million ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Million ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Million ");
    else if(a.charAt(0)=='0'){
    if(b.length=='8' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=x+"Million ";
    else if(b.length=='9' && (b.charAt(1)!='0' || b.charAt(0)!='0'))
    document.frmcnvrt.a2.value=x+"Million ";
    else if(b.length=='10' && (b.charAt(2)!='0' || b.charAt(1)!='0'))
    document.frmcnvrt.a2.value=x+"Million ";
    else if(b.length=='11' && (b.charAt(3)!='0' || b.charAt(2)!='0'))
    document.frmcnvrt.a2.value=x+"Million ";
    else if(b.length=='12' && (b.charAt(4)!='0' || b.charAt(3)!='0'))
    document.frmcnvrt.a2.value=x+"Million ";
    else if(b.length=='13' && (b.charAt(5)!='0' || b.charAt(4)!='0'))
    document.frmcnvrt.a2.value=x+"Million ";
    else if(b.length=='14' && (b.charAt(6)!='0' || b.charAt(5)!='0'))
    document.frmcnvrt.a2.value=x+"Million ";
    else if(b.length=='15' && (b.charAt(7)!='0' || b.charAt(6)!='0'))
    document.frmcnvrt.a2.value=x+"Million ";
    }
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='10'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Billion ");
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Billion ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Billion ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Billion ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Billion ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Billion ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Billion ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Billion ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Billion ");
    else if(a.charAt(0)=='0'){
    if (b.length=='11' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=x+"Billion ";
    else if(b.length=='12' && (b.charAt(1)!='0' || b.charAt(0)!='0'))
    document.frmcnvrt.a2.value=x+"Billion ";
    else if(b.length=='13' && (b.charAt(2)!='0' || b.charAt(1)!='0'))
    document.frmcnvrt.a2.value=x+"Billion ";
    else if(b.length=='14' && (b.charAt(3)!='0' || b.charAt(2)!='0'))
    document.frmcnvrt.a2.value=x+"Billion ";
    else if(b.length=='15' && (b.charAt(4)!='0' || b.charAt(3)!='0'))
    document.frmcnvrt.a2.value=x+"Billion ";  
    }}
    else if(a.length=='13'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Trillion ");
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Trillion ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Trillion ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Trillion ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Trillion ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Trillion ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Trillion ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Trillion ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Trillion ");
    else if(a.charAt(0)=='0'){
    document.frmcnvrt.a2.value=x+"Trillion ";
    }        
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else 
document.frmcnvrt.a2.value=(x+"");
}
a=a.slice(1);
}
}
        </script>
        <script>
function ntowini(){
var a=document.frmcnvrt.a1.value;
var i,b,c,x;
b=a;
c=a.slice(3);
for (i=1;i<=17;i++){
x=document.frmcnvrt.a2.value;
if (a=='0'){
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.charAt(0)=='1' && (a.length=='2' || a.length=='5' || a.length=='7' || a.length=='9' || a.length=='12'||a.length=='14' || a.length=='16'))
{
if (a. charAt(1)=='1'){
document.frmcnvrt.a2.value=(x+"Eleven ");
if (a.length=='5' || a.length=='12'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Thousand ");}
else if(a.length=='7' || a.length=='14'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Lakh ");}
else if(a.length=='9'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Crore ");}
else if(a.length=='16'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Crore Crore");}
}
else if(a. charAt(1)=='2'){
document.frmcnvrt.a2.value=(x+"Twelve ");
if (a.length=='5' || a.length=='12'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Thousand ");}
else if(a.length=='7' || a.length=='14'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Lakh ");}
else if(a.length=='9'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Crore ");}
else if(a.length=='16'){
x=document.frmcnvrt.a2.value;
document.frmcnvrt.a2.value=(x+"Crore Crore");}
}
else if(a. charAt(1)=='3'){
document.frmcnvrt.a2.value=(x+"Thirteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5' || a.length=='12')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='7' || a.length=='14')
document.frmcnvrt.a2.value=(x+"Lakh ");
else if(a.length=='9')
document.frmcnvrt.a2.value=(x+"Crore ");
else if(a.length=='16')
document.frmcnvrt.a2.value=(x+"Crore Crore");
}
else if(a. charAt(1)=='4'){
document.frmcnvrt.a2.value=(x+"Fourteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5' || a.length=='12')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='7' || a.length=='14')
document.frmcnvrt.a2.value=(x+"Lakh ");
else if(a.length=='9')
document.frmcnvrt.a2.value=(x+"Crore ");
else if(a.length=='16')
document.frmcnvrt.a2.value=(x+"Crore Crore");
}
else if(a. charAt(1)=='5'){
document.frmcnvrt.a2.value=(x+"Fifteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5' || a.length=='12')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='7' || a.length=='14')
document.frmcnvrt.a2.value=(x+"Lakh ");
else if(a.length=='9')
document.frmcnvrt.a2.value=(x+"Crore ");
else if(a.length=='16')
document.frmcnvrt.a2.value=(x+"Crore Crore");
}
else if(a. charAt(1)=='6'){
document.frmcnvrt.a2.value=(x+"Sixteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5' || a.length=='12')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='7' || a.length=='14')
document.frmcnvrt.a2.value=(x+"Lakh ");
else if(a.length=='9')
document.frmcnvrt.a2.value=(x+"Crore ");
else if(a.length=='16')
document.frmcnvrt.a2.value=(x+"Crore Crore");
}
else if(a. charAt(1)=='7'){
document.frmcnvrt.a2.value=(x+"Seventeen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5' || a.length=='12')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='7' || a.length=='14')
document.frmcnvrt.a2.value=(x+"Lakh ");
else if(a.length=='9')
document.frmcnvrt.a2.value=(x+"Crore ");
else if(a.length=='16')
document.frmcnvrt.a2.value=(x+"Crore Crore");
}
else if(a. charAt(1)=='8'){
document.frmcnvrt.a2.value=(x+"Eighteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5' || a.length=='12')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='7' || a.length=='14')
document.frmcnvrt.a2.value=(x+"Lakh ");
else if(a.length=='9')
document.frmcnvrt.a2.value=(x+"Crore ");
else if(a.length=='16')
document.frmcnvrt.a2.value=(x+"Crore Crore");
}

else if(a. charAt(1)=='9'){
document.frmcnvrt.a2.value=(x+"Nineteen ");
x=document.frmcnvrt.a2.value;
if (a.length=='5' || a.length=='12')
document.frmcnvrt.a2.value=(x+"Thousand ");
else if(a.length=='7' || a.length=='14')
document.frmcnvrt.a2.value=(x+"Lakh ");
else if(a.length=='9' )
document.frmcnvrt.a2.value=(x+"Crore ");
else if(a.length=='16')
document.frmcnvrt.a2.value=(x+"Crore Crore");
}

else if(a.charAt(1)=='0'){
x=document.frmcnvrt.a2.value;
    if (a.length=='2')
    document.frmcnvrt.a2.value=(x+"Ten");
    else if(a.length=='5' || a.length=='12')
    document.frmcnvrt.a2.value=(x+"Ten Thousand "); 
    else if(a.length=='7' || a.length=='14')  
    document.frmcnvrt.a2.value=(x+"Ten Lakh ");
    else if(a.length=='9')
document.frmcnvrt.a2.value=(x+"Ten Crore ");
    else if(a.length=='16')    
    document.frmcnvrt.a2.value=(x+"Ten Crore Crore ");
}
else
document.frmcnvrt.a2.value=(x+" ");
a=a.slice(1);
}
else{
if (a.length=='1')
{
    if (a=='1')
    document.frmcnvrt.a2.value=(x+"One");
    else if(a=='2')
    document.frmcnvrt.a2.value=(x+"Two");
    else if(a=='3')
    document.frmcnvrt.a2.value=(x+"Three");
    else if(a=='4')
    document.frmcnvrt.a2.value=(x+"Four");
    else if(a=='5')
    document.frmcnvrt.a2.value=(x+"Five");
    else if(a=='6')
    document.frmcnvrt.a2.value=(x+"Six");
    else if(a=='7')
    document.frmcnvrt.a2.value=(x+"Seven");
    else if(a=='8')
    document.frmcnvrt.a2.value=(x+"Eight");
    else if(a=='9')
    document.frmcnvrt.a2.value=(x+"Nine");
    else 
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='2' || a.length=='5' || a.length=='7' || a.length=='9' || a.length=='12' || a.length=='14' || a.length=='16'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"Ten ");
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Twenty ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Thirty ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Forty ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Fifty ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Sixty ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seventy ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eighty ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Ninety ");
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='3' || a.length=='10' || a.length=='17'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Hundred ");
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Hundred ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Hundred ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Hundred ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Hundred ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Hundred ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Hundred ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Hundred ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Hundred ");
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='4'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Thousand ")
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Thousand ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Thousand ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Thousand ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Thousand ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Thousand ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Thousand ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Thousand ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Thousand ");
    else if(a.charAt(0)=='0'){
    if (b.length=='5' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='6' && b.charAt(1)!='0' )
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='7' && b.charAt(2)!='0' )
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='8' && b.charAt(3)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='9' && b.charAt(4)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='10' && b.charAt(5)!='0' )
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='11' && b.charAt(6)!='0' )
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if(b.length=='12' && b.charAt(7)!='0')
    document.frmcnvrt.a2.value=x+"thousand ";
    else if(b.length=='13' && b.charAt(8)!='0')
    document.frmcnvrt.a2.value=x+"thousand ";
    else if(b.length=='14' && b.charAt(9)!='0')
    document.frmcnvrt.a2.value=x+"thousand ";
    else if(b.length=='15' && b.charAt(10)!='0')
    document.frmcnvrt.a2.value=x+"thousand ";
    else if(b.length=='16' && b.charAt(11)!='0')
    document.frmcnvrt.a2.value=x+"thousand ";
    else if(b.length=='17' && b.charAt(12)!='0')
    document.frmcnvrt.a2.value=x+"thousand ";
    }
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='6'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Lakh ")
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Lakh ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Lakh ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Lakh ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Lakh ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Lakh ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Lakh ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Lakh ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Lakh ");
    else if(a.charAt(0)=='0'){
    if(b.length=='7' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='8' && b.charAt(1)!='0')
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='9' && b.charAt(2)!='0' )
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='10' && b.charAt(3)!='0')
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='11' && b.charAt(4)!='0')
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='12' && b.charAt(5)!='0')
   document.frmcnvrt.a2.value=x+"Lakh "; 
    else if(b.length=='13' && b.charAt(6)!='0' )
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='14' && b.charAt(7)!='0' )
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='15' && b.charAt(8)!='0' )
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='16' && b.charAt(9)!='0' )
    document.frmcnvrt.a2.value=x+"Lakh ";
    else if(b.length=='17' && b.charAt(10)!='0' )
    document.frmcnvrt.a2.value=x+"Lakh ";
    }
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='11'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Thousand ")
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Thousand ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Thousand ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Thousand ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Thousand ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Thousand ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Thousand ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Thousand ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Thousand ");
    else if(a.charAt(0)=='0'){
    if (b.length=='12' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if (b.length=='13' && b.charAt(1)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if (b.length=='14' && b.charAt(2)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if (b.length=='15' && b.charAt(3)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if (b.length=='16' && b.charAt(4)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    else if (b.length=='17' && b.charAt(5)!='0')
    document.frmcnvrt.a2.value=x+"Thousand ";
    } 
    else
    document.frmcnvrt.a2.value=(x+" ");
}
else if(a.length=='8'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Crore ");
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Crore ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Crore ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Crore ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Crore ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Crore ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Crore ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Crore ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Crore ");
    else if(a.charAt(0)=='0'){
    if (b.length=='9' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=x+"Crore "; 
    else if (b.length=='10' && (b.charAt(1)!='0' || b.charAt(0)!='0'))
    document.frmcnvrt.a2.value=x+"Crore ";
    else if (b.length=='11' && (b.charAt(1)!='0' || b.charAt(0)!='0' || b.charAt(2)!='0'))
    document.frmcnvrt.a2.value=x+"Crore ";
    else if (b.length=='12' && (b.charAt(1)!='0' || b.charAt(0)!='0' || b.charAt(2)!='0' || b.charAt(3)!='0'))
    document.frmcnvrt.a2.value=x+"Crore ";
    else if (b.length=='13' && (b.charAt(1)!='0' || b.charAt(0)!='0' || b.charAt(2)!='0' || b.charAt(3)!='0' || b.charAt(4)!='0'))
    document.frmcnvrt.a2.value=x+"Crore ";
    else if (b.length=='14' && (b.charAt(1)!='0' || b.charAt(0)!='0' || b.charAt(2)!='0' || b.charAt(3)!='0' || b.charAt(4)!='0' || b.charAt(5)!='0'))
    document.frmcnvrt.a2.value=x+"Crore ";
    
    
    
    } 
    }
else if(a.length=='13'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Lakh ")
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Lakh ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Lakh ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Lakh ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Lakh ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Lakh ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Lakh ");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Lakh ");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Lakh ");
    else if(a.charAt(0)=='0'){
    if(b.length=='14' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=(x+"Lakh ");
    else if(b.length=='15' && b.charAt(1)!='0')
    document.frmcnvrt.a2.value=(x+"Lakh ");
    else if(b.length=='16' && b.charAt(2)!='0')
    document.frmcnvrt.a2.value=(x+"Lakh ");
    else if(b.length=='17' && b.charAt(3)!='0')
    document.frmcnvrt.a2.value=(x+"Lakh ");
    
}}
else if(a.length=='15'){
    if (a.charAt(0)=='1')
    document.frmcnvrt.a2.value=(x+"One Crore  Crore ");
    else if (a.charAt(0)=='2')
    document.frmcnvrt.a2.value=(x+"Two Crore Crore ");
    else if (a.charAt(0)=='3')
    document.frmcnvrt.a2.value=(x+"Three Crore Crore ");
    else if (a.charAt(0)=='4')
    document.frmcnvrt.a2.value=(x+"Four Crore Crore ");
    else if (a.charAt(0)=='5')
    document.frmcnvrt.a2.value=(x+"Five Crore Crore ");
    else if (a.charAt(0)=='6')
    document.frmcnvrt.a2.value=(x+"Six Crore Crore ");
    else if (a.charAt(0)=='7')
    document.frmcnvrt.a2.value=(x+"Seven Crore Crore");
    else if (a.charAt(0)=='8')
    document.frmcnvrt.a2.value=(x+"Eight Crore Crore");
    else if (a.charAt(0)=='9')
    document.frmcnvrt.a2.value=(x+"Nine Crore Crore");
    else if(a.charAt(0)=='0'){
    if(b.length=='16' && b.charAt(0)!='0')
    document.frmcnvrt.a2.value=(x+"Crore Crore");
    else if(b.length=='17' && (b.charAt(0)!='0' || b.charAt(1)!='0'))
    document.frmcnvrt.a2.value=(x+"Crore Crore");
    } 
    }    
else 
document.frmcnvrt.a2.value=(x+"");
}
a=a.slice(1);
}
}
        </script>
        <script>  
        const date = new Date();
document.getElementById("demo").innerHTML = date;
</script> 
<script>
    window.onclose = function()
    {
        alert("Hello");
    }
</script>    
</html>

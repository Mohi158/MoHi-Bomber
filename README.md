<html>
<head>
<title># sms Bomber Mr Mohsen #</title>
</head>
<body onload="writetext()" bgcolor="#000000" text="#167715" link="#167715" alink="#167715" vlink="#167715" background="" style="background-position: 0px 200px;">
<center>
<tbody>
<tr>
<td>
<p>
<table align="center" cellpadding="10">
<tbody>
<tr bgcolor="black">
<td>
<p></p>
<script language="JavaScript">
msg = new Array(); //strings written in screen
msg[0] = "<h2><font size=30><font face='Courier'> >> - Mr Mohsen << </font></font><br><font color='#00FF00' size=30>================================= <font face='Courier'><br>Sms Bomber MoHi</u></font></font></h2>";
msg[1] = "<b> A free and fast sms Bomber made by Mr Mohsen<font face='Courier' color='#00FF00'></font>";
msg[2] = "<b> Contact Us : <font face='Courier' color='#00FF00'> <a href=ymsgr:sendim?Mr Mohsen>telegram: @ID_Mr_Mohi</a></font>";
msg[3] = "<b><font face='Courier' color='#00FF00'> </font>";
msg[4] = "<b><font face='Courier' color='#00FF00'> </font></font><br><br>I am  <font face='Courier' color='#00FF00'>Mr Mohsen </br><br></font><font color='#00FF00' size=30>================================= ";
text1 = ""; //the same as text2, only the last character is highlighted
text2 = ""; //current string, which will be written
count = 0; //char index in string text
count2 = 0; //number of strings
text = msg[0].split(""); //text - string written
function writetext() { //show strings above on screen
text1 = text2 + "<font color='#00FF00'>" + text[count] + "</font>";
text2 += text[count];
document.all["nothing"].innerHTML = text1; //where to write
if (count < text.length-1){
count++;
setTimeout('writetext()', 25);
}
else { //if this string is written, get the new string
count = 0;
if (count2 != 4) { //write 4 strings
count2++;
text2 += "<p>"; //a new line
text = eval('msg['+count2+'].split("")'); //get the new string to text
setTimeout('writetext()', 25);
}
}
}
</script>
<div id="nothing" style="font-family: 'Courier';"><h2><font size="30"><font face="Courier">=================================</font></font><br><font color="#00FF00" size="30">
<u>Hacked By <font face="Courier">Virus 32</font></u></font></h2><p><b>your security is funny! 
<font face="Courier" color="#00FF00"> i know who are you!</font></b></p><p><b><b> Contact Us : <font face="Courier" color="#00FF00"> <a href="ymsgr:sendim?hack666m">hack666m</a></font></b></b></p><p><b><b><b> Hey Admin, <font face="Courier" color="#00FF00"> you are realy a Dull !.</font></b></b></b></p><p><b><b><b><b> this is not funny stupid ! <font face="Courier" color="#00FF00"> It's Really suck ! yep</font> LOL!<br><br>team<font face="Courier" color="#00FF00"> Virus32 cpr 2008<br><br></font><font size="30">=================================<font color="#00FF00"> </font></font></b></b></b></b></p></div>
<font face="Courier">
<script>
var isNS = (navigator.appName == "Netscape") ? 1 : 0;
if(navigator.appName == "Netscape") document.captureEvents(Event.MOUSEDOWN||Event.MOUSEUP);
function mischandler(){
return false;
}
function mousehandler(e){
var myevent = (isNS) ? e : event;
var eventbutton = (isNS) ? myevent.which : myevent.button;
if((eventbutton==2)||(eventbutton==3)) return false;
}
document.oncontextmenu = mischandler;
document.onmousedown = mousehandler;
document.onmouseup = mousehandler;
</script>
</html>

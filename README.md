SCRIPT
======
<script type='text/javascript'>
//<![CDATA[
<!-- 
document.writeln(" <html> "); 
document.writeln(" <head> "); 
document.writeln(" <title>SISTEMA DE INGRESO PARA CURSO DE DISEÑO GRAFICO<\/title> "); 
document.writeln(" <\/head> "); 
document.writeln(" <body text=\"016E63\" background=\"fondo.jpg\" style=\"background-repeat:no-repeat\"> "); 
document.writeln(" <div align=\"center\"><H2>BIENVENIDO AL SISTEMA DE INGRESO <br>DEL CURSO DE DISEÑO GRAFICO FACCI ONLINE<\/H2><br> "); 
document.writeln(" <p>Dirigido a Estudiantes Universitarios, Egresados y Profesionales de la Carrera de Ingeniería en Sistemas, personas con conocimientos de "); 
document.writeln(" Publicidad, Artes Gráficas, Creativos Gráfico, e Interesados a nivel general.<\/p> "); 
document.writeln(" <div style=\"border-style:solid; border-color:white; border-widht:2px;\"><H4>INGRESE SUS DATOS<\/H4> "); 
document.writeln(" <div> NOMBRES <input type=\"text\" id=\"name\" name=\"form\"><\/div><br> "); 
document.writeln(" <div> APELLIDOS <input type=\"text\" id=\"apellido\" name=\"form\"><\/div><br> "); 
document.writeln(" <div> C.I. <input type=\"text\" id=\"ci\" name=\"form\"><\/div><br> "); 
document.writeln(" <div> CORREO ELECTRONICO <input type=\"text\" id=\"email\" name=\"form\"><\/div><br> "); 
document.writeln(" <div> TELEFONO <input type=\"text\" id=\"movil\" name=\"form\"><\/div><br> "); 
document.writeln(" <div> FECHA NACIMIENTO <input type=\"date\" id=\"edad\" name=\"form\"><\/div><br> "); 
document.writeln(" <div> Seleccionar horario <br> "); 
document.writeln(" <input type=\"radio\" id=\"matu\" name=\"horario\" value=\"matu\"> Matutino "); 
document.writeln(" <input type=\"radio\" id=\"vesper\" name=\"horario\" value=\"vesper\"> Vespertino<\/div> "); 
document.writeln(" <br><b> INGRESE EN QUE ESPECIAL LE GUSTARIA INCURSIONAR<\/b><br> "); 
document.writeln(" CURSO DE ILUSTRADOR<br> "); 
document.writeln(" CURSO DE ADOBE PHOTOSHOP<br> "); 
document.writeln(" CURSO DE INDESIGN<br> "); 
document.writeln(" COREL DRAW<br> "); 
document.writeln(" XARA 3D <br> "); 
document.writeln(" IMAGE READY<br> "); 
document.writeln(" <input type=\"text\" id=\"seleccion\" name=\"form\"> "); 
document.writeln(" <input type=\"button\" id=\"editorseleccion\" value=\"Validar si esta disponible\" onclick=\"seleccioncurso()\"><br> "); 
document.writeln(" <input type=\"button\" id=\"aceptar\" value=\"Aceptar\" onclick=\"aceptar1();\"> "); 
document.writeln(" <\/div> "); 
document.writeln(" <\/body> "); 
document.writeln(" <\/html> "); 
document.writeln("  "); 
document.writeln(" <script type=\"text/javascript\"> "); 
document.writeln(" function seleccioncurso() { "); 
document.writeln(" 	if((document.getElementById(\"seleccion\")).value==\"CURSO ILUSTRADOR\" || (document.getElementById(\"seleccion\")).value==\"CURSO DE ADOBE PHOTOSHOP\" || (document.getElementById(\"seleccion\")).value==\"CURSO DE INDESIGN\" || "); 
document.writeln(" 	(document.getElementById(\"seleccion\")).value==\"COREL DRAW\" || (document.getElementById(\"seleccion\")).value==\"XARA 3D\" || (document.getElementById(\"seleccion\")).value==\"IMAGE READY\"){ "); 
document.writeln(" 	alert(\"DISPONIBLE\"); "); 
document.writeln(" 	} "); 
document.writeln(" 	else {alert (\"NO ESTA DISPONIBLE!\");} "); 
document.writeln(" } "); 
document.writeln(" function aceptar1 (){ "); 
document.writeln(" 	for(i=0;i<document.getElementsByName(\"form\").length;i++){ "); 
document.writeln(" 		if(document.getElementsByName(\"form\")[i].value==\"\") { "); 
document.writeln(" 		alert(\"DATOS NO INGRESADOS!\"); "); 
document.writeln(" 		}else{}  "); 
document.writeln(" 	} "); 
document.writeln(" 	if(!document.getElementsByName(\"form\")[0].value==\"\" && !document.getElementsByName(\"form\")[1].value==\"\" && !document.getElementsByName(\"form\")[2].value==\"\" &&  "); 
document.writeln(" 	!document.getElementsByName(\"form\")[3].value==\"\" && !document.getElementsByName(\"form\")[4].value==\"\" && !document.getElementsByName(\"form\")[5].value==\"\"){ "); 
document.writeln(" 	 "); 
document.writeln(" 	alert(\"DATOS COMPLETADOS FELICITACIONES!\")} "); 
document.writeln(" } "); 
document.writeln(" <\/script> "); 
document.writeln("  ");
 // -->
//]]>
</script>

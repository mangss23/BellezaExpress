<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Login para varios usuario</title>
</head>

<body>
<h1>Ingresa Tus Datos 
</h1> 
<form name="login"> 
     <table width="200" border="0"> 
       <tr> 
         <th scope="row"><h2>Usuario</h2></th> 
         <td><span class="cnt"> 
           <input name="usuario" type="text" class="Input" value="" size="20" /> 
         </span></td> 
       </tr> 
       <tr> 
         <th height="33" scope="row"><h2>Clave</h2></th> 
         <td><span class="cnt"> 
           <input name="password" type="password" class="Input" value="" size="20" /> 
         </span></td> 
         <td><span class="cnt"> 
           <input value="Entrar" target="_parent" onclick="Login()" type="button" class="boton"/> 
         </span></td> 
       </tr> 
       <tr> 
         <th scope="row"><input type="reset" name="Borrar" id="Borrar" value="Reset" class="boton" /></th> 
       </tr> 
     </table> 
</form> 

<script language="JavaScript"> 
function Login(){ 
var done=0; 
var usuario=document.login.usuario.value; 
var password=document.login.password.value; 
if (usuario=="USUARIO1" && password=="CONTRASEÑA1") { 
window.location="TU_PAGINA_WEB.HTML"; 
} 
if (usuario=="USUARIO2" && password=="CONTRASEÑA2") { 
window.location="TU_PAGINA_WEB.HTML"; 
} 
if (usuario=="" && password=="") { 
window.location="errorpopup.html"; 
} 
} 
        </script> 
</center> 
<script language="Javascript"> 
<!-- Begin 
document.oncontextmenu = function(){return false} 
// End --> 
</script>
</body>
</html>

# execultavel.bat
<h2>Como isso funciona</h2>
<br>
<p>
Bem é assim, isso foi feito com foco de auto executar um aplicativo, sendo mais especifico executar o PHP.EXE, 
automaticamente quando o windows iniciar/ligar</p>
<br>
<p> <b>windows + R</b>= e cole isso usando o windows claro <br>
%AppData%\Microsoft\Windows\Start Menu\Programs\Startup<br></p>

<p>agora copie o atalho do arquivo.bat aqui e quando o windows iniciar/ligar será auto executavél, olha isso vale para
qualquer aplicativo aqui dentro da pasta <b>Startup</b> será iniciado</p>

agora é só configurar o .bat de forma que quiser<br>
<b>EXEMPLO></b>:  START php -S localhost:8080

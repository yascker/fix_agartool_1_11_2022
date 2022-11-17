# fix_agartool_1_11_2022
Una solución temporal para el problema de visualización de agar.io con agartool  
  
1.- Necesitamos un navegador basado en chromium como google-chrome, microsoft-edge, opera, brave, etc.  
2.- Descargamos una extención que se llama spybot  
3.- https://chrome.google.com/webstore/detail/stylebot/oiaejidbmkiecgbjeifoejpgmdaleoha  
4.- Abrirmos agar.io  
5.- Buscamos la extención y la abrimos  
6.- En la ventana que se abre pegamos el siguiente código css  
  
body{
  overflow: hidden;
}
#canvas{
  margin: 0;
  padding: 0;
}
#fb-root,#oferwallContainer{
  display: none;
}
html{
  background-color: #000;
}

7.- Cerramos la ventana  
8.- Morimos como eternos novatos :)  
  
NOTA: al cerrar y abrir nuevamente el navegador es necesario volver a a abrir y cerrar Stylebot para que se aplique la solución nuevamente.

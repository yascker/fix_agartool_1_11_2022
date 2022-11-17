# fix_agartool_1_11_2022
Una solución temporal para el problema de visualización de agar.io con agartool  
  
1.- Necesitamos un navegador basado en chromium como google-chrome, microsoft-edge, opera, brave, etc.  
2.- Descargamos una extención que se llama spybot:  
    https://chrome.google.com/webstore/detail/stylebot/oiaejidbmkiecgbjeifoejpgmdaleoha  
3.- Abrirmos agar.io  
4.- Buscamos la extención y la abrimos  
5.- En la ventana que se abre pegamos el siguiente código css (elegir segun tema oscuro o claro)

#Tema oscuro:

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

-----

#Tema claro:

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
  background-color: #fff;
}


6.- Cerramos la ventana de Stylebot  
7.- Morimos como eternos novatos :)  
  
NOTA: al cerrar y abrir nuevamente el navegador es necesario volver a a abrir y cerrar Stylebot para que se aplique la solución nuevamente.

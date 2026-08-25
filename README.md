# windows.tptecno.com

Sirve el catálogo de notebooks Windows en su propio subdominio.

`index.html` es la misma página que `tptecno/catalogo`, abriendo en la categoría
Windows. La navegación de arriba sigue funcionando: `#macbook`, `#iphone`, etc.
quedan dentro de este mismo dominio.

**No editar a mano.** Lo actualiza `publicar.sh` del repo `catalogo`, que es donde
vive el generador.

Los precios de Windows se leen **en vivo** de la pestaña `Windows` de la hoja de
catálogo (gid 661876936), en el navegador de quien abre la página: un cambio en la
planilla se ve al instante, sin esperar a que se regenere nada.

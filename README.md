(https://github.com/user-attachments/files/34834961/LEEME.txt)
CALLEJERO DE VALLADOLID — App para móvil y tablet
=================================================

Esta carpeta es una app web instalable (PWA). Funciona en Android, iPhone, iPad y
tabletas, se instala con su propio icono en la pantalla de inicio, se abre a
pantalla completa y, después de abrirla una vez, funciona sin conexión.

Contenido
  index.html             la app completa (mapa, datos y juegos)
  manifest.webmanifest   nombre, colores e iconos de la app
  sw.js                  modo sin conexión
  icons/                 iconos de la app


1) INSTALARLA EN EL MÓVIL O LA TABLETA
--------------------------------------
  Android (Chrome):  abre la dirección → menú ⋮ → «Instalar aplicación»
                     (o «Añadir a pantalla de inicio»).
  iPhone / iPad (Safari): abre la dirección → botón Compartir →
                     «Añadir a pantalla de inicio».

  Ábrela una vez con conexión; a partir de ahí funciona también sin internet.

2) ACTUALIZARLA
---------------
Si cambias index.html, sube la carpeta de nuevo y cambia en sw.js la línea
  const VERSION = 'callejero-v1';
por 'callejero-v2' (y así sucesivamente) para que los móviles descarguen la
versión nueva.

Datos: Ayuntamiento de Valladolid (GISAVA) y © colaboradores de OpenStreetMap (ODbL).

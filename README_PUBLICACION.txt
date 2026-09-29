PRESENTACIÓN EPOANT — PUBLICACIÓN EN EDUPSIC.COM

Dominio preparado: reunion.edupsic.com

ARCHIVOS QUE DEBEN SUBIRSE A LA RAÍZ DEL REPOSITORIO DE GITHUB:
- index.html
- CNAME
- .nojekyll
- carpeta assets/

CONFIGURACIÓN EN GITHUB PAGES
1. Crear o abrir el repositorio que se usará para la presentación.
2. Subir TODOS los archivos de esta carpeta a la raíz del repositorio.
3. En GitHub: Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: main / root.
6. En Custom domain escribir: reunion.edupsic.com
7. Guardar y activar Enforce HTTPS cuando GitHub lo permita.

CONFIGURACIÓN DNS EN SQUARESPACE / EDUPSIC.COM
Crear un registro CNAME:
- Host/Nombre: reunion
- Tipo: CNAME
- Valor/Destino: TU-USUARIO-DE-GITHUB.github.io

IMPORTANTE:
Reemplaza TU-USUARIO-DE-GITHUB por el nombre real de tu cuenta de GitHub.
No agregues https:// en el valor del CNAME.

Una vez propagado el DNS, la presentación quedará disponible en:
https://reunion.edupsic.com

# Git y Github
Git != Github
Github utiliza git para ofrecer un servicio en la nube. 
1 Repositorio Remoto == FUENTE DEL CÓDIGO PARA TODOS LOS DESARROLLADORES
X Repositorios Locales == Copia del repositorio remoto donde vamos a trabajar y que en algún momento se va a sincronizar.
Subir nuestros cambios
Descargar los cambios de los demas
---
# Flujo de trabajo
Subir cambios al repositorio remoto desde el repositorio local

- Una diferencia de código (se agrego o elimino un archivo, se agregaron o eliminaron lineas de código dentro de un archivo)
- Fecha y hora
- Autor
- Commit

0) git init para inicializar repo local

1) git add NOMBRE_ARCHIVO o git add . == Añadir archivos al stage (contenedor de cambios)



2) Commitearlos == Se añade un texto descriptivo de los cambios que se hicieron

3) Git push

# Para el clonado

1) Entramos al github de nuestro compalero, damos click en CODE y seleccionamos la opcion de SSH y copiamos la URL.

2) Desde la consola, en una carpeta ejecutamos el comando git clone + la URL que copiamos desde el github de nuestro compañero y damos enter

3) Se generara una nueva carpeta con el repositorio de github que clonamos

# Práctica Servidor Web

## 1. Título

**Comandos de Linux**

## 2. Tiempo de duración

**6 Horas**

## 3. Fundamentos

En la práctica se llevaron a cabo varios pasos fundamentales para su desarrollo:

El primero consistió en la instalación de **Ubuntu WSL**, específicamente la versión 24.04.06.

### ¿Qué es Ubuntu WSL?

Según el repositorio de Learn Microsoft, Ubuntu WSL es una característica de Windows que permite ejecutar un entorno Linux en la máquina Windows, sin necesidad de una máquina virtual independiente o arranque dual. WSL está diseñado para proporcionar una experiencia perfecta y productiva para los desarrolladores que quieren usar Windows y Linux al mismo tiempo.

A continuación, se revisaron conceptos básicos sobre los comandos de Linux, los cuales se definen como "palabras reservadas utilizadas por el sistema operativo para ejecutar acciones específicas mediante una terminal o línea de comandos" (Hetpro Store, 2025).

He creado una lista con los comandos a modo de guía, misma que registro en mi Notion personal mientras me voy familiarizando con cada uno de ellos. Esta lista me ha ayudado a organizar y comprender el uso de los comandos más básicos.


| Comando  | Descripción                                                  | Ejemplo                          |
|----------|--------------------------------------------------------------|----------------------------------|
| `pwd`    | Muestra la ruta actual del directorio de trabajo.           | `/home/usuario/proyecto`        |
| `cd`     | Cambia el directorio de trabajo.                            | `cd Documents/`                 |
| `ls`     | Lista los archivos y carpetas dentro del directorio actual. | `ls /home/usuario/`             |
| `mkdir`  | Crea una nueva carpeta.                                     | `mkdir nueva_carpeta`           |
| `rm`     | Elimina archivos.                                           | `rm archivo.txt`                |
| `cp`     | Copia archivos o carpetas a una ubicación específica.       | `cp archivo.txt /home/usuario/` |
| `mv`     | Mueve archivos o carpetas a otra ubicación.                 | `mv archivo.txt /home/usuario/` |
| `touch`  | Crea un archivo vacío.                                      | `touch nuevo_archivo.txt`       |
| `cat`    | Muestra el contenido de un archivo.                         | `cat archivo.txt`               |
| `history`| Muestra el historial de comandos ejecutados en la terminal. | `history`                        |

Seguido de esto, ejecuto Ubuntu, creo un usuario y una contraseña, y procedo con la práctica.
## 4. Conocimientos previos

Para realizar esta práctica el estudiante necesita tener claro los siguientes temas:

- Comandos Linux.
- Manejo de navegador.
- etc.

## 5. Objetivos a alcanzar

- Implementar contenedores con Nginx.
- Manipular archivos de configuración.
- ...

## 6. Equipo necesario

- Computador con sistema operativo Windows/Linux/Mac.
- Cuenta en Docker Play.
- Docker vXXXX.
- etc.

## 7. Material de apoyo

- Documentación de Docker.
- Guía de asignatura.
- Cheat sheet Linux.
- etc.
  
## 8. Procedimiento

**Paso 1:**  
En tu directorio de trabajo, crea una carpeta llamada `proyecto_comandos`.
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/1.jpg?raw=true)



**Paso 2:**  
Dentro de `proyecto_comandos`, crea tres subcarpetas: `documentos`, `imagenes` y `scripts`.
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/2.jpg?raw=true)

**Paso 3:**  
Dentro de la carpeta `documentos`, crea un archivo de texto llamado `notas.txt`.

![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/3.jpg?raw=true)

**Paso 4:**  
Agrega al menos tres líneas de texto en `notas.txt` utilizando un editor de texto en la terminal (nano, vim) o con redireccionamiento (`echo`).
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/4.jpg?raw=true)

**Paso 5:**  
Copia el archivo `notas.txt` a la carpeta `scripts` y cambia su nombre a `backup_notas.txt`.

![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/5.1.jpg?raw=true)
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/5.2.jpg?raw=true)

**Paso 6:**  
Mueve el archivo `backup_notas.txt` a la carpeta `imagenes`.
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/6.jpg?raw=true)

**Paso 7:**  
Crea un archivo llamado `resumen.txt` en `documentos`.
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/7.jpg?raw=true)

**Paso 8:**  
Redirecciona el contenido de `notas.txt` a `resumen.txt`.
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/8.jpg?raw=true)


**Paso 9:**  
Añade una nueva línea de texto a `resumen.txt` sin sobrescribir su contenido.
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/9.jpg?raw=true)

**Paso 10:**  
Elimina el archivo `backup_notas.txt` de la carpeta `imagenes`.
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/10.jpg?raw=true)


**Paso 11:**  
Elimina la carpeta `imagenes` (solo si está vacía).

![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/11.jpg?raw=true)


**Paso 12:**  
Vuelca el contenido del comando `history` a un archivo llamado `tarea-s1-nombre_apellido.txt` utilizando tuberías. Sustituye `nombre_apellido` por tu nombre y apellido correspondiente.
![Descripción de la imagen](https://github.com/Edissonfierro/Comandoslinux/blob/main/12.jpg?raw=true)


## 9. Resultados esperados

Se cumplió con los objetivos de la práctica:

Se creó la estructura de carpetas proyecto_comandos con las subcarpetas documentos, imagenes y scripts.

Se manipuló el archivo notas.txt, se copió y renombró a backup_notas.txt, y se movió a imagenes.

Se creó resumen.txt, redirigiendo el contenido de notas.txt y añadiendo nueva información sin sobrescribir.

Se eliminó el archivo backup_notas.txt y la carpeta vacía imagenes.

Se volcó el historial de comandos en un archivo tarea-s1-nombre_apellido.txt y se subió al repositorio.

Se envia audio con lo aprendido. 



## 10. Bibliografía

- Microsoft. (n.d.). *Sobre el Subsistema de Windows para Linux (WSL)*. Microsoft Docs. Recuperado el 5 de abril de 2025, de https://learn.microsoft.com/es-es/windows/wsl/about
- Giménez, E., & Castéran, P. (2005). *A tutorial on [co-]inductive types in Coq*. https://www.fing.edu.uy/inco/cursos/sistoper/recursosLaboratorio/tutorial0.pdf
- IONOS. (2024, 21 de noviembre). *Los comandos de Linux más importantes*. IONOS. Recuperado de https://www.ionos.com/es-us/digitalguide/servidores/configuracion/comandos-de-linux-la-lista-fundamental/
- HeTPro. (s.f.). *Comandos Linux - nivel básico*. Recuperado de https://hetpro-store.com/TUTORIALES/comandos-linux-nivel-basico/

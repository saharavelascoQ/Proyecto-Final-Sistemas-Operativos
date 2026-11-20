
# Ficha de verificación de versión · Grupo 1

## ¿Qué es esta ficha?

Esta ficha permite comprobar que las versiones de las distribuciones Linux elegidas sirven para desarrollar el proyecto. Se debe consultar la información en fuentes oficiales y agregar el enlace donde se verificó cada respuesta.

Fecha de consulta: 20/11/2026

## Distribuciones del Grupo 1

- Kubuntu (máquina virtual gráfica).
- Debian (máquina virtual de consola).
- Ubuntu (imagen base del Dockerfile).

## 1. Kubuntu (VM gráfica)

| **Pregunta** | **Respuesta** | **Enlace donde lo comprobamos** |
|---|---|---|
| Versión elegida y fecha de lanzamiento |Kubuntu 26.04 LTS, lanzada el 23 de abril de 2026.|https://kubuntu.org/news/kubuntu-26-04-release-notes/|
| Hasta cuándo recibe actualizaciones de seguridad |Hasta abril de 2029.|https://kubuntu.org/es/download/|
| Requisitos de hardware y si funciona en VirtualBox |Necesitamos al menos un procesador de doble núcleo a 2 GHz (64-bit), 6 GB de RAM y 25 GB de espacio en disco.|https://kfocus.org/wf/reinstall.html|
| ¿El instalador permite particionado manual? |Sí, permite realizar el particionado manual durante la instalación.|https://kfocus.org/wf/reinstall.html |
| Guía oficial para instalar Docker Engine en esa familia |Para instalar Docker Engine en Kubuntu 26.04 LTS ("Resolute Raccoon"), se utiliza el método recomendado del repositorio oficial de APT de Docker para Ubuntu (ya que Kubuntu comparte exactamente la misma base de paquetes y nombre clave|https://docs.docker.com/engine/install/ubuntu/|
| Imagen base del Dockerfile para esa versión |No aplica. La imagen base elegida para el proyecto será Ubuntu 26.04.|https://hub.docker.com/_/ubuntu|

**Memoria RAM asignada a la VM:**4 GB (4096 MB).

**¿Por qué elegimos esa cantidad de RAM?**

Elegimos 4 GB porque nuestro computador cuenta con 16 GB de memoria RAM y esta cantidad permite que Kubuntu funcione con su entorno gráfico y podamos realizar las actividades del proyecto.

## 2. Debian (VM de consola)

| **Pregunta** | **Respuesta** | **Enlace donde lo comprobamos** |
|---|---|---|
| Versión elegida y fecha de lanzamiento |Debian 13.7 (Trixie), publicada el 12 de septiembre de 2026. Su versión inicial, Debian 13.0, fue lanzada el 9 de agosto de 2025 |https://www.debian.org/releases/trixie/|
| Hasta cuándo recibe actualizaciones de seguridad |Soporte completo hasta el 9 de agosto de 2028 y soporte LTS hasta el 30 de junio de 2030|https://www.debian.org/releases/|
| Requisitos de hardware y si funciona en VirtualBox |Debian 13 ("Trixie") funciona perfectamente en VirtualBox y requiere un mínimo de 1 GB de RAM y 10 GB de disco si incluye entorno gráfico (o 512 MB de RAM y 4 GB de disco en modo servidor sin interfaz).|https://www.youtube.com/watch?v=J-lH150zjc4|
| ¿El instalador permite particionado manual? |Sí, el instalador de Debian permite seleccionar y configurar las particiones manualmente.|https://www.debian.org/releases/stable/amd64/ |
| Guía oficial para instalar Docker Engine en esa familia |Docker cuenta con instrucciones oficiales para instalar Docker Engine en Debian 13.|https://docs.docker.com/engine/install/debian/|

**Memoria RAM asignada a la VM:**2 GB (2048 MB).

**¿Por qué elegimos esa cantidad de RAM?**

Elegimos 2 GB porque Debian se utilizará principalmente mediante consola y no necesita tantos recursos gráficos. Así podemos aprovechar la memoria de nuestro computador para ejecutar el sistema y realizar las actividades del proyecto.

## 3. Ubuntu (imagen base del Dockerfile)

| **Pregunta** | **Respuesta** | **Enlace donde lo comprobamos** |
|---|---|---|
| Versión elegida y fecha de lanzamiento | | |
| Hasta cuándo recibe actualizaciones de seguridad | | |
| Requisitos de hardware y si funciona en VirtualBox | | |
| ¿El instalador permite particionado manual? | | |
| Guía oficial para instalar Docker Engine en esa familia | | |
| Imagen base del Dockerfile para esa versión | | |

**Etiqueta de la imagen en Docker Hub:** __________________

**Gestor de paquetes que utilizaremos:** __________________

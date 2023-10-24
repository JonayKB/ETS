<div align = "justify">

# Instalación de JDK en el Ubuntu

## Índice



## ¿Cómo instalar Java en Ubuntu desde repositorios?

### Actualiza y busca las últimas versiones

```code
sudo apt-get update
```
 <details>
 <summary><strong>Salida</strong></summary>

- sudo apt-get update
```code
Obj:1 http://packages.microsoft.com/repos/code stable InRelease
Obj:2 http://security.ubuntu.com/ubuntu jammy-security InRelease               
Obj:3 http://archive.ubuntu.com/ubuntu jammy InRelease                         
Ign:4 http://packages.linuxmint.com victoria InRelease
Obj:5 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
Obj:6 http://packages.linuxmint.com victoria Release  
Obj:7 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
Leyendo lista de paquetes... Hecho
```
</details>





### Instalamos Java

```code
sudo apt-get install default-jdk
```
 <details>
 <summary><strong>Salida</strong></summary>

- sudo apt-get install default-jdk
```code
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias... Hecho
Leyendo la información de estado... Hecho
default-jdk ya está en su versión más reciente (2:1.11-72build2).
0 actualizados, 0 nuevos se instalarán, 0 para eliminar y 211 no actualizados.
```
</details>


### Comprobar versión

```code
java --version
```
 <details>
 <summary><strong>Salida</strong></summary>

- sudo apt-get install default-jdk
```code
openjdk 11.0.20.1 2023-08-24
OpenJDK Runtime Environment (build 11.0.20.1+1-post-Ubuntu-0ubuntu122.04)
OpenJDK 64-Bit Server VM (build 11.0.20.1+1-post-Ubuntu-0ubuntu122.04, mixed mode, sharing)
```
</details>


## ¿Cómo instalar una versión específica de Java?
Instalar varias versiones de OpenJDK:
 <details>
 <summary><strong>11</strong></summary>

- sudo apt install openjdk-11-jdk
```code
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias... Hecho
Leyendo la información de estado... Hecho
openjdk-11-jdk ya está en su versión más reciente (11.0.20.1+1-0ubuntu1~22.04).
fijado openjdk-11-jdk como instalado manualmente.
0 actualizados, 0 nuevos se instalarán, 0 para eliminar y 211 no actualizados.
```
</details>

 <details>
 <summary><strong>13</strong></summary>

- sudo apt install openjdk-13-jdk
```code
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias... Hecho
Leyendo la información de estado... Hecho
E: No se ha podido localizar el paquete openjdk-13-jdk
```
</details>


 <details>
 <summary><strong>8</strong></summary>

- sudo apt install openjdk-8-jdk
```code
Se descargo correctamente
```
</details>


## Configuración de las variables de entorno
Vamos a aprender a modificar las variables de entorno

### Listar la versiones de OpenJDK instaladas
```code
ls /usr/lib/jvm
```
 <details>
 <summary><strong>Salida</strong></summary>

- ls /usr/lib/jvm
```code
default-java               java-11-openjdk-amd64     java-8-openjdk-amd64
java-1.11.0-openjdk-amd64  java-1.8.0-openjdk-amd64  openjdk-11
```
</details>


### Actualización de las variables de entorno
```code
sudo update-alternatives --config java
```
 <details>
 <summary><strong>Salida</strong></summary>

- sudo update-alternatives --config java
```code
Existen 2 opciones para la alternativa java (que provee /usr/bin/java).

  Selección   Ruta                                            Prioridad  Estado
------------------------------------------------------------
* 0            /usr/lib/jvm/java-11-openjdk-amd64/bin/java      1111      modo automático
  1            /usr/lib/jvm/java-11-openjdk-amd64/bin/java      1111      modo manual
  2            /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java   1081      modo manual

Pulse <Intro> para mantener el valor por omisión [*] o pulse un número de selección: 
```
</details>
</div>
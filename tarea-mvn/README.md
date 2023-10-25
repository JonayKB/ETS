<div align = "justify">

# Instalación de Maven en el Linux

## Índice
1. [Instalar Maven](#instalar-maven)
2. [Instalar una versión concreta](#instalar-una-versión-concreta)
3. [Establecer variables de entorno](#establecer-variables-de-entorno)
4. [Verificar instalación](#verificar-instalación)


## Instalar maven

### Actualizamos y installamos la ultima
Actualizamos
```code
sudo apt update
sudo apt install maven
mvn -version

```
 <details>
 <summary><strong>Salida</strong></summary>

- sudo apt update
```code
Busca actualizaciones
```
- sudo apt install maven
```code
No instalo nada porque ya lo estaba
```

- mvn -version
```code
Apache Maven 3.6.3
Maven home: /usr/share/maven
Java version: 11.0.20.1, vendor: Ubuntu, runtime: /usr/lib/jvm/java-11-openjdk-amd64
Default locale: es_ES, platform encoding: UTF-8
OS name: "linux", version: "5.15.0-76-generic", arch: "amd64", family: "unix"
```
</details>

## Instalar una versión concreta

### Descargar Apache Maven en /tmp
```code
wget https://www.apache.org/dist/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz -P /tmp
sudo tar xf /tmp/apache-maven-*.tar.gz -C /opt
```
 <details>
 <summary><strong>Salida</strong></summary>

Descargamos el archivo
- wget https://www.apache.org/dist/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz -P /tmp
```code
apache-maven-3.8.8- 100%[===================>]   7,91M  9,50MB/s    en 0,8s    

2023-10-25 15:20:43 (9,50 MB/s) - ‘/tmp/apache-maven-3.8.8-bin.tar.gz’ guardado [8296049/8296049]
```
Extraemos el archivo
- sudo tar xf /tmp/apache-maven-*.tar.gz -C /opt
```code

```

Creamos un enlace de maven en la ruta que pone
- sudo ln -s /opt/apache-maven-3.8.6 /opt/maven
```code

```

</details>

## Establecer variables de entorno
```code
sudo nano /etc/profile.d/maven.sh
sudo chmod +x /etc/profile.d/maven.sh
source /etc/profile.d/maven.sh
```

 <details>
 <summary><strong>Salida</strong></summary>

Creamos un archivo de configuración
- sudo nano /etc/profile.d/maven.sh
```code

```
Cambiamos los permisos del archivo
- sudo chmod +x /etc/profile.d/maven.sh
```code

```

Hacemos que cargue las variables
- source /etc/profile.d/maven.sh
```code

```
</details>

## Verificar instalación
```code
mvn --version
```

 <details>
 <summary><strong>Salida</strong></summary>


- mvn --version
```code
Maven home: /opt/maven-3.8.8
Java version: 11.0.20.1, vendor: Ubuntu, runtime: /usr/lib/jvm/java-11-openjdk-amd64
Default locale: es_ES, platform encoding: UTF-8
OS name: "linux", version: "5.15.0-76-generic", arch: "amd64", family: "unix"
```

</details>



</div>
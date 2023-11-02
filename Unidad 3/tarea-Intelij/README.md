<div align = "justify">

# Instalación de Maven en el Linux

## Índice
1. [Prerequisitos](#prerequisitos)
2. [Instalar Intellij](#instalar-intellij)
3. [Acceder a Intellij](#acceder-a-intellij)





## Prerequisitos
### Comprobar la instalación del Java
```code
java -version
```

 <details>
 <summary><strong>Salida</strong></summary>


- java -version
```code
Openjdk version "11.0.20.1" 2023-08-24
OpenJDK Runtime Environment (build 11.0.20.1+1-post-Ubuntu-0ubuntu122.04)
OpenJDK 64-Bit Server VM (build 11.0.20.1+1-post-Ubuntu-0ubuntu122.04, mixed mode, sharing)
```
</details>

### Instalar Snap
```code
sudo su
cd etc/apt/preferences.d/
rm nosnap.pref
apt install snapd
```

 <details>
 <summary><strong>Salida</strong></summary>


- rm nosnap.pref
```code
Eliminamos el archivo de Linux Mint que elimina la restriccion de snap
```

- sudo apt install snapd
```code
Se instala correctamente
```

</details>



## Instalar Intellij

```code
sudo snap install intellij-idea-community --classic
```

 <details>
 <summary><strong>Salida</strong></summary>


- sudo snap install intellij-idea-community --classic
```code
Se instala correctamente
```

</details>

## Acceder a Intellij
Para acceder vamos al inicio y buscamos en aplicaciones Intellij o dentro de la pestaña "Programación"



</div>
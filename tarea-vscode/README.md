<div align = "justify">

# Instalación de Visual Studio Code en el Linux

## Índice
1. [Prerequisitos](#prerequisitos)
2. [Instalar Visual Studio Code](#instalar-visual-studio-code)
3. [Acceder a Visual Studio Code](#acceder-a-visual-studio-code)
4. [Extensiones](#extensiones)





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



## Instalar Visual Studio Code

```code
sudo snap install --classic code
```

 <details>
 <summary><strong>Salida</strong></summary>


- sudo snap install --classic code
```code
Se instala correctamente
```

</details>

## Acceder a Visual Studio Code
Para acceder vamos al inicio y buscamos en aplicaciones Visual Studio Code o dentro de la pestaña "Programación"


## Extensiones
Dentro de las extensiones podemos encontrar dos opciones:

 <details>
 <summary><strong>Necesarias</strong></summary>


- Java Extension Pack
```code
Todos los recursos básicos y necesarios para trabajar con Java dentro de visual studio, para test, maven, debugger, ayudas con el lenguaje, etc.
```

</details>

 <details>
 <summary><strong>Opcionales</strong></summary>


- Visual Studio IntelliCode
```code
Te ayuda con tu código mediante inteligencia artificial
```

- Path Intellisense
```code
Ayuda a escribir bien las rutas de los archivos
```

- Bracket Pair Colorizer
```code
Ayuda a diferenciar los bloques del código (Ya se incluye dentro del visual studio code una version alternativa)
```

- GitLens
```code
Añade más detalles con las integraciones del visual studio code a git
```

- Prettier
```code
Formatea el código y indenta todo correctamente
```

- Color Highlight
```code
Ayuda con la visualización de los colores (rgb, arb, hexadecimal), incluye un recuadro con el color indicado
```

- Indent Rainbow
```code
Ayuda a diferenciar bloques y buena visualización del indentado
```

</details>


Para instalarlas simplemente tendremos que buscarlas en el menu de "Extensiones" del Visual Studio Code

</div>
# Configuración del Proyecto - ChuchaquiGame

Este repositorio contiene el código base del juego. Para que el proyecto compile y funcione correctamente, sigue estos pasos de configuración inicial.

## 1. Clonar el Repositorio
Debes clonar el proyecto en la raíz de tu disco principal (generalmente el disco C:).

1. Abre tu terminal o Git Bash.  
2. Navega a la raíz de tu disco (ej. `cd C:\`).  
3. Ejecuta el comando:

```bash
git clone https://github.com/AlexanderRosas/ChuchaquiGame.git
```

**Nota:** Asegúrate de que la ruta final sea `C:\ChuchaquiGame`.

## 2. Importar Modelos 3D (Archivos .obj)
Debido al tamaño de los modelos, estos se encuentran alojados en OneDrive. Debes mantener la estructura de carpetas exacta.

1. Accede al siguiente enlace: **[Modelos en OneDrive](https://epnecuador-my.sharepoint.com/:f:/g/personal/alvaro_montalvan_epn_edu_ec/IgDSUnvR6EqqQI8j6jANuX0gAZVmG-H_vRqF0VUrUyzui2E?e=xYKvWP)**
  
2. Descarga los archivos `.obj` que están dentro de cada subcarpeta.  
3. Copia cada modelo en su carpeta correspondiente en tu equipo local:

Ruta local:
```
C:\ChuchaquiGame\OpenGL\model\
```

**Importante:**  
Si en el OneDrive el archivo está en una carpeta llamada `Personaje`, en tu computadora debe ir dentro de:
```
C:\ChuchaquiGame\OpenGL\model\Personaje
```
No mezcles los archivos, cada uno debe ir en la carpeta con su mismo nombre.

## 3. Configuración de Librerías (Assimp)
Para que el ejecutable funcione en modo depuración, necesitas la librería dinámica de Assimp.

Antes debes conmpilar el priyecto para que se genere la carpeta x64 Debug.

1. Localiza tu archivo compilado `assimp-vc143-mtd.dll`.  
2. Pégalo en las siguientes rutas:

```
C:\ChuchaquiGame\x64\Debug\
C:\ChuchaquiGame\OpenGL_Stuff\Library
```

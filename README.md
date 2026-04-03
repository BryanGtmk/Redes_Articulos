## Requisitos para trabajar con LaTeX en Visual Studio Code

Para poder editar y compilar el documento LaTeX del proyecto en **Visual Studio Code**, se necesita lo siguiente:

### 1. Instalar Visual Studio Code
Descargar e instalar Visual Studio Code en el equipo.

### 2. Instalar una distribución LaTeX
Según el sistema operativo:

- **Windows:** MiKTeX  
- **macOS:** MacTeX  
- **Linux (Ubuntu/Debian):** TeX Live  

### 3. Instalar la extensión de LaTeX en VS Code
En Visual Studio Code, instalar la extensión:

- **LaTeX Workshop**

Esta extensión permite:
- Compilar archivos `.tex`
- Ver el PDF generado
- Navegar entre el código y el documento

### 4. Instalar Perl en Windows
Si se trabaja en **Windows**, se recomienda instalar también **Strawberry Perl**, ya que algunas configuraciones de compilación de LaTeX Workshop lo requieren.

### 5. Abrir el archivo principal del proyecto
El archivo principal del documento es:

```bash
documentacion/main.tex
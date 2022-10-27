## TD table export 📋

`ES`
Este es un componente custom para [TouchDesigner](https://derivative.ca/). Sirve para exportar tablas en formatos `.csv` y `.xlsx`.

### Rápida implementación 🚩

Antes de utilizar el componente `TDTableExport.tox` es necesario instalar las dependencias.
> 💡 Nota: las dependencias utilizadas son `pandas`, `openpyxl` y `pathlib`.

1. Ir a la carpeta `Dep`.

2. Hacer doble click en el archivo `dep_install.cmd`. Este archivo se encarga de verificar que [Python](https://www.python.org/) se encuentre bien instalado, actualizado e instala las dependencias.

3. Arrastrar el componente `TDTableExport.tox` al proyecto de TouchDesigner que estes trabajando.

### Comentarios y comandos 🚏

Parámetros obligatorios:

- `Table DAT`: tabla que sirve como input.

- `Save Target`: destino en donde el archivo se va a crear.

- `File Name`: nombre del archivo que se va a crear.

Elegir que tipo de archivo se quiere exportar y pulsar `Create File`.

### Importante 🚧
Hoy en día hay mucho virus dando vueltas. Por eso es importante aclarar que hay dentro del archivo `.cmd`.

El archivo ejecuta en su interior algo similar a esto:
> 💡 Nota: digo similar porque las variables `reqs` y `target` toman como variable la ruta en donde el archivo se encuentra en tu computadora. Esto depende en que lugar de tu computadora estes trabajando.

```
:: update pip
python -m pip install --user --upgrade pip

:: install from requirements file
py -3.7 -m pip install -r "{reqs}" --target="{target}"
```
Es posible constatar esto tambien abriendo el archivo `.cmd` en [Sublime Text](https://www.sublimetext.com/) o cualquier otro editor de código.

### pequeña hoja de ruta 📍

- Agregar instalación automática de las dependencias al inciar TouchDesigner.

### Créditos 💳

El workflow para trabajar con dependencias externas está basado en el tutorial [External Python Libraries](https://github.com/mir-lab/touchdesigner-summit-2019-external-python) de [MIR Lab](https://mir.works/).

👋 *Si lo usas, si tenés algún tipo de feedback o problema, hacemelo llegar por favor :)*

---

`EN`

This is a custom component for [TouchDesigner](https://derivative.ca/). It exports tables in `.csv` and `xlsx` formats.

### Quick implementation 🚩

Before using the `TDTableExport.tox` component it's necessary to install the dependencies.
> 💡 Note: the dependencies used are `pandas`, `openpyxl` and `pathlib`.

1. Go to the `Dep` folder.

2. Double click on the `dep_install.cmd` file. This file takes care of verifying that [Python](https://www.python.org/) is properly installed, updated and installs the dependencies.

3. Drag the `TDTableExport.tox` component to the TouchDesigner project you are working on.

### Comments and commands 🚏

Required parameters:

- `Table DAT`: table that serves as input.

- `Save Target`: destination where the file will be created.

- `File Name`: name of the file to be created.

Select the type of file to be exported and click `Create File`.

### Important 🚧
Nowadays there are a lot of malwares around. That's why it's important to clarify what's inside the `.cmd` file.

The code inside is something like this:
> 💡 Note: I say similar because the `reqs` and `target` variables take as variable the path where the file is located on your computer. This depends on where on your computer you are working.

```
:: update pip
python -m pip install --user --upgrade pip

:: install from requirements file
py -3.7 -m pip install -r "{reqs}" --target="{target}"
```
It's possible to check this also by opening the `.cmd` file in [Sublime Text](https://www.sublimetext.com/) or any other code editor.

### little roadmap 📍

- Add automatic installation of dependencies when starting TouchDesigner.

### Credits 💳

The workflow for working with external dependencies is based on the [External Python Libraries](https://github.com/mir-lab/touchdesigner-summit-2019-external-python) tutorial from [MIR Lab](https://mir.works/).


👋 *If you use it or if you have any feedback or problem, please let me know :)*

🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶🧶
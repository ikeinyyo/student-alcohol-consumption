# Student alcohol consumtion

## Primeros pasos

### Crear entorno de Conda

Para crear el entorno de conda usaremos este comando, indicando la versión de Python que queremos utilizar.

`conda create -n student python=3.5`

### Crear entorno desde fichero

Crear el entorno de conda desde el fichero de environment.

`conda env create -n student -f environment.yml`

### Activar entorno

Para activar el entorno de conda que hemos creado utilizamos el comando `activate`:

`source activate student`

### Exportar el entorno

Exportamos el entorno de conda a un fichero.

`conda env export > environment.yml`

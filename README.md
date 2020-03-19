# De 0 a 100 con Python y ML: Aprendizaje por Refuerzo

### Refresh Anaconda

- **Crear un entorno en anaconda**:

    - \$ conda create -n "nombre_del_entorno" python="python_version"
    
- **Activar un entorno en anaconda**:

    - \$ conda activate "nombre_del_entorno"

- **Desactivar un entorno en anaconda**:

    - ("nombre_del_entorno") \$ conda deactivate
    
- **Instalar un paquete o librería en anaconda** (debemos tener el entorno activado)

    - ("nombre_del_entorno") \$ conda install "nombre_del_paquete"
    
- **Activar un entorno de anaconda para usarlo dentro de un jupyter notebook** (debemos tener el entorno activado y ipykernel instalado)

    - ("nombre_del_entorno") \$ python -m ipykernel install --user --name "nombre_del_entorno" --display-name "Nombre en Jupyter"
    
- **Lanzar un jupyter notebook** (debemos tener el entorno activado y el paquete jupyter notebook instalado dentro)

    - ("nombre_del_entorno") \$ jupyter notebook
    
- **Exportar las librerías instaladas en el entorno a un archivo txt**

    - ("nombre_del_entorno") \$ conda export > "nombre_del_archivo".txt
    
- **Instalar las librerías desde un archivo .txt**

    - ("nombre_del_entorno") \$ conda install -r "nombre_del_archivo".txt
    
- **Ver las librerías instaladas dentro de un entorno**

    - ("nombre_del_entorno") \$ conda list
    
- **Ver todos los entornos que tengo creados en mi ordenador**

    - \$ conda env list

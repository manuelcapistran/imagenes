Generador de Estímulo Visual - Instrucciones de Instalación

Requisitos del Sistema

- Python 3.6 o superior
- pip (gestor de paquetes de Python)


Instalación de Dependencias

El programa requiere las siguientes bibliotecas de Python:
Ejecuta el siguiente comando en la terminal:

```bash
pip install numpy matplotlib
```


Bibliotecas Necesarias
1. **NumPy** - Para cálculos numéricos y manejo de arrays
   ```bash
   pip install numpy
   ```
2. **Matplotlib** - Para visualización y generación de imágenes
   ```bash
   pip install matplotlib
   ```

Verificación de la Instalación
Para verificar que las bibliotecas están correctamente instaladas, ejecuta:
```bash
python -c "import numpy; import matplotlib; print('¡Instalación exitosa!')"
```
Si no aparece ningún error, estás listo para ejecutar el programa.


Ejecución del Programa
Una vez instaladas las dependencias, ejecuta:
```bash
python estimulo_visual.py
```
se deberan generar 4 imagenes, para que se generen se debera cerrar la imagen desplegada consecutivamente hasta que se hayan generado las demas


Entorno Virtual (Opcional pero Recomendado)
Para mantener las dependencias aisladas:
```bash
# Crear entorno virtual
python -m venv venv
# Activar entorno virtual
# En Windows:
venv\Scripts\activate
# En Linux/Mac:
source venv/bin/activate
# Instalar dependencias
pip install numpy matplotlib
# Ejecutar el programa
python estimulo_visual.py
# Desactivar entorno virtual cuando termines
deactivate
```

## Versiones Probadas

- Python 3.8+
- NumPy 1.19.0+
- Matplotlib 3.3.0+


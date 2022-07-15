# Contenido
Estructura de ejemplo para crear una librería de Python.  
Instrucciones detalladas [aquí](https://packaging.python.org/en/latest/tutorials/packaging-projects/).  
  
Mientras que el repositorio oficial de librería de Python es [PyPI](https://pypi.org/), existe un repositorio para hacer pruebas llamado [TestPyPI](https://test.pypi.org/), donde aparece también alojada esta [librería de prueba](https://test.pypi.org/project/example-package-CALCULO-DIAMETRO-PROMEDIO/) (hasta que la eliminen).  
  
Para su instalación y prueba, en mi caso, he seguido los siguientes pasos desde el terminal (no me quedaban del todo claros en las guías):  
  
```
python3  
from example_package_CALCULO_DIAMETRO_PROMEDIO import example  
example.dbh_promedio(5, 6)
```
   
Algunos enlaces de interés:
- [Errores en la subida de librerías a TestPyPI](https://stackoverflow.com/questions/65414493/pypi-package-testing-403-forbidden-from-https-test-pypi-org-legacy)
- Estructura de proyectos python: [1](https://awaywithideas.com/the-optimal-python-project-structure/) [2](https://github.com/LukeTonin/my_project) [3](https://antonio-fernandez-troyano.medium.com/crear-una-libreria-python-4e841fbd154f) [4](https://tutorialesinformatica.com/programacion/como-crear-librerias-en-python/)

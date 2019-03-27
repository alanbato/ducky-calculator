# Ducky

![Ducky](./static/logo.svg)

[![Gitter](https://badges.gitter.im/ducky-calculator/community.svg)](https://gitter.im/ducky-calculator/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

> Proyecto ejemplo para enseñar las diferentes partes de contribuir al OSS.

Ducky es una calculadora que te permite realizar muchas cosas, desde operaciones aritméticas hasta cálculo.

# Uso

Solo tienes que usar una de las funciones del menú y listo!

## Funciones disponibles

* Suma
* Resta
* Raíces
* Integral definida

# Contribuir

## Requerimientos

* Python >= 3.5
* Pytest
* SymPy

## Setup

### Windows

1. En Command Prompt, ejecutar:
`pip install virtualenv`

2. Navegar a la carpeta de tu proyecto y ejecutar:
`virtualenv env`

3. Activar el script en:
`source ./env/Scripts/activate`

4. Instalar requirements
`pip install -r requirements.txt`

### Linux

Primero, se recomienda crear un ambiente virtual de la siguiente manera:
`$ python -m venv env`
y luego actiar el ambiente virtual:
`$ source env/bin/activate`

Una vez en el ambiente, hay que instalar los requerimientos
`$ pip install -r requirements.txt`

Estás listo para usar Ducky!

## Testing

Para correr las pruebas basta con estar en el directorio principal y correr:
`$ python -m pytest`

# Código de Conducta

Todos los miembros de la comunidad de Ducky deberán tratarse con mucho respeto.

# Licencia
Ver el archivo de `LICENSE`

# Proyecto de Automatizacion QA - Silvia Eliana Ruiz

## Descripcion

Proyecto de automatizacion de pruebas realizado con Python, Selenium WebDriver y Pytest.

El objetivo del proyecto es automatizar distintas pruebas funcionales de una aplicacion web.

## Tecnologias usadas

- Lenguaje: Python

- Automatización UI: Selenium WebDriver

- Framework de Testing: Pytest

- Pruebas de API: Requests

- Reportes: Pytest-html (con captura automática de screenshots ante fallos)

- Control de versiones: Git y GitHub

## Instalacion

`git clone https://github.com/silviaeliana/proyecto-final-automation-testing-silvia-eliana-ruiz.git`

## Instalacion dependencias

`pip install -r requirements.txt`

## Ejecucion de pruebas

Para ejecutar la suite completa de pruebas y generar el reporte, utilizar el siguiente comando:

`pytest --html=reports/report.html`

## Funcionamiento de las pruebas

**Test Login:** Validación de acceso exitoso y manejo de errores (escenarios negativos) mediante parametrización con archivos CSV.

**Test Inventory:** Verificación de la carga correcta de productos y navegación en la página de inventario.

**Test Cart:** Pruebas funcionales del carrito de compras que incluyen la adición y eliminación de productos, verificación de persistencia de ítems y parametrización mediante archivos JSON.

**Test API:** Suite de pruebas para endpoints públicos, validando métodos HTTP (GET, POST, DELETE) y la integridad de los datos en las respuestas JSON.

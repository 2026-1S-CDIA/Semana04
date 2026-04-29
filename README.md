# Programación II - Semana 4

## Unidad 1: Programación Orientada a Objetos en Python

Este repositorio contiene el material práctico correspondiente a la **Semana 4** de la asignatura **Programación II**.

La semana está enfocada en el diseño e implementación de clases en Python aplicando conceptos avanzados de Programación Orientada a Objetos.

## Temas abordados

- Abstracción
- Clases abstractas
- Herencia
- Polimorfismo
- Métodos especiales
- Sobrecarga de operadores
- Patrón Singleton
- Pruebas básicas con `assert`

## Archivos del repositorio

README.md  
STV_Semana4.ipynb  
ST_Semana4.ipynb  

## Descripción de los notebooks

### STV_Semana4.ipynb

Notebook obligatorio de la semana.

Contiene ejercicios guiados para trabajar en clase o sesión tutorial.  
El objetivo es que el estudiante practique paso a paso los conceptos principales de la semana.

Temas principales:

- Creación de clases abstractas con `ABC` y `abstractmethod`
- Implementación de clases hijas
- Uso de `super()`
- Aplicación de polimorfismo
- Uso de `__init__` y `__str__`
- Sobrecarga de operadores con `__add__` y `__sub__`
- Implementación básica del patrón Singleton

### ST_Semana4.ipynb

Notebook opcional de profundización.

Contiene ejercicios con mayor nivel de dificultad, orientados a integrar varios conceptos de Programación Orientada a Objetos en problemas más completos.

Ejercicios propuestos:

1. Sistema de personajes para un videojuego RPG.
2. Sistema de vehículos para una carrera futurista.

Estos ejercicios requieren aplicar diseño orientado a objetos de manera más estructurada.

## Objetivo de aprendizaje

Al finalizar las actividades de esta semana, el estudiante será capaz de:

- Diseñar clases abstractas para representar conceptos generales.
- Crear clases hijas que implementen comportamientos específicos.
- Aplicar herencia y polimorfismo en problemas prácticos.
- Utilizar métodos especiales para mejorar la representación y comportamiento de objetos.
- Sobrecargar operadores para hacer el código más expresivo.
- Implementar una configuración global utilizando el patrón Singleton.
- Validar el funcionamiento del código mediante pruebas con `assert`.

## Requisitos

Para ejecutar los notebooks se recomienda tener instalado:

- Python 3.10 o superior.
- Jupyter Notebook o JupyterLab.
- Visual Studio Code con extensión de Python, opcional.

## Librerías utilizadas

Los ejercicios utilizan principalmente librerías estándar de Python.

Librería principal:

    from abc import ABC, abstractmethod

No se requieren librerías externas para esta práctica.

## Cómo ejecutar los notebooks

1. Clonar o descargar este repositorio.
2. Abrir la carpeta en JupyterLab, Jupyter Notebook o Visual Studio Code.
3. Ejecutar primero el notebook obligatorio: `STV_Semana4.ipynb`.
4. Luego, de forma opcional, resolver el notebook de profundización: `ST_Semana4.ipynb`.

## Convenciones de entrega

El archivo obligatorio debe entregarse con el siguiente nombre:

`STV_Semana4.ipynb`

El archivo opcional debe entregarse con el siguiente nombre:

`ST_Semana4.ipynb`

## Criterios de evaluación sugeridos

| Criterio | Descripción |
|---|---|
| Abstracción | Identifica correctamente clases generales y comportamientos comunes |
| Clase abstracta | Usa `ABC` y `abstractmethod` de forma adecuada |
| Herencia | Implementa clases hijas correctamente |
| Polimorfismo | Usa un mismo método con diferentes comportamientos |
| Métodos especiales | Aplica `__init__`, `__str__`, `__add__`, `__sub__` u otros según corresponda |
| Singleton | Implementa una única instancia compartida |
| Pruebas | Incluye verificaciones con `assert` |
| Organización | Presenta código claro, ordenado y comentado |

## Recomendaciones para el estudiante

- Lea con atención cada enunciado antes de programar.
- Identifique primero las clases necesarias.
- Diferencie qué clase debe ser abstracta y cuáles deben ser concretas.
- Use nombres claros para clases, atributos y métodos.
- Evite repetir código innecesariamente.
- Compruebe cada parte del programa con ejemplos y `assert`.
- Explique brevemente las decisiones de diseño cuando sea necesario.

## Autor

Material preparado para la asignatura **Programación II**.

Docente: **José Andrés Zúñiga Cazorla**

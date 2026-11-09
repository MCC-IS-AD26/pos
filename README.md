# Proyecto - Java POS - Maven

Proyecto de mini Punto de Venta (POS) en Java con Maven.

## Diagrama de clases
[Editor en línea](https://mermaid.live/)
```mermaid
---
title: Clase
---
classDiagram
      class Clase
      Clase: -x
      Clase: -y
      Clase: +op1()
      Clase: +op2()
      Clase: +op3()
      Clase: +op4()
```
[Referencia-Mermaid](https://mermaid.js.org/syntax/classDiagram.html)

## Diagrama de clases UML con draw.io
El repositorio está configurado para crear Diagramas de clases UML con ```draw.io```. Para usarlo das doble clic sobre el archivo ```uml.class.drawio.png```. Asegúrate de agregar las formas UML en el menú de formas del lado izquierdo (opción ```+Más formas```).

## Prompts para generar los Diagramas de Clase y Secuencia mermaid

Para mejores resultados agrega primero como contexto las clases del proyecto y después aplica los prompts.

```
Genera el diagrama de clases para el código Java que te proporciono a continuación. Asegúrate de incluir todas las clases, atributos y métodos públicos y privados. El diagrama debe reflejar las relaciones entre las clases, como herencia, composición y agregación. Utiliza la sintaxis de mermaid para crear un diagrama claro y legible. Entrega el resultado en formato mermaid en un archivo clases.md
```

```
Genera el diagrama de secuencia para el código Java que te proporciono a continuación. Asegúrate de incluir todos los objetos y métodos involucrados en la secuencia. El diagrama debe reflejar el flujo de mensajes entre los objetos, incluyendo llamadas a métodos y retornos. Utiliza la sintaxis de mermaid para crear un diagrama claro y legible. Entrega el resultado en formato mermaid en un archivo secuencia.md
```

## Uso del proyecto con Maven

### Compilar
```
mvn compile
```
### Probar N tests
```
mvn test
```
### Probar 1 test
```
mvn test -Dtest="AppTest#testPOS" 
```
### Ejecutar App
```
mvn -q exec:java
```
```
java -cp target/classes miPrincipal.App
```
### Empacar App
```
mvn package
```
### Limpiar binarios
```
mvn clean
```

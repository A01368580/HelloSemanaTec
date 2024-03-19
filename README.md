# **HelloSemanaTec** 
# Roberta Giovanna González Canavati 🐈‍⬛🧋
## ITC, 6to
## *Monterrey, NL*
### Equipo - Rayados 
Repositorio para la Semana Tec 

## 2. Tipos de letra
*Italic*
**Bold**

## 3. Lista Tacos favoritos en MTY
1. Tacos Alfaro
2. Atarantados
3. Más Salsa
4. Melany's

# 4. Lista sin orden de Tacos favoritos
- Tacos de trompo
- Tacos sudados
- Gringas

## 5. Código Paint
```
from turtle import *

from freegames import vector


def line(start, end):
    """Draw line from start to end."""
    up()
    goto(start.x, start.y)
    down()
    goto(end.x, end.y)


def square(start, end):
    """Draw square from start to end."""
    up()
    goto(start.x, start.y)
    down()
    begin_fill()

    for count in range(4):
        forward(end.x - start.x)
        left(90)

    end_fill()


def circle(start, end):
    """Draw circle from start to end."""
    pass  # TODO


def rectangle(start, end):
    """Draw rectangle from start to end."""
    pass  # TODO


def triangle(start, end):
    """Draw triangle from start to end."""
    pass  # TODO
```

## 6. Regla
---
---

## 7. Link
- [Paint Freegames](https://grantjenks.com/docs/freegames/paint.html)
- [Markdown CheatSheet](https://www.markdownguide.org/cheat-sheet/)

  ## 8. Imágen
  ![Tacos Alfaro](https://img.restaurantguru.com/r234-Alfaro-Tacos-al-Carbon-dishes-2022-08.jpg)

  ## 9. Tabla
| Clase | Descripción |
| ----------- | ----------- |
| TC3004B | Planeación de Software |
| Continuación de TC3004B | Desarrollo de Software |

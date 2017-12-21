# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de JavaScript](https://platzi.com/js) de Platzi.

## Descripción del idioma

- Si la palabra termina con "ar", se lequitan esas dos letras.
- Si la palabra inicia con "Z", se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio.
- Por último, si la palabra original es un palíndromo, singuna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas.

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom('Programas') // Program
platzom('Zorro') // Zorrope
platzom('Zarpar') // Zarppe
platzom('Abecedario') // Abece-dario
platzom('sometemos') // SoMeTeMoS
```

## Créditos
- [Kevin Lozoya](https://twitter.com/LozoyaGiner)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
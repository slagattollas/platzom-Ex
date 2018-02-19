# Platzom

Platzom es un dioma inventado para el [Curso de Fundamentos de Javascript](https://platzi.com/js) de [Platzi](https://platzi.com)

## Descripcion del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o mas letras, se debe partir en dos por la mitad y unir con un guion medio
- Por ultimo, si la palabra original es un palindromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intecalando letras mayusculas y minusculas.

## Instalacion 
```
npm install platzom

```

## Uso

```
import plazom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope

```
## Creditos

- [Stefano Lagattolla](https://twitter.com/slagattollas)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
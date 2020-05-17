# Notas de CSS

## Formas de trabajar con CSS
Podemos importar CSS de 3 formas

- En linea
- En un bloque etiqueta `<style></style>`
- En un archivo separado `nombre.css`

**Ejemplos**

Estilo en Linea:
```html
<h1 style="Aqui iria tus reglas CSS"> Titulo <h1>
```
---

Estilo en Etiqueta
```html
<style>
    Aqui iria tu reglas CSS
</style>

<h1> Titulo <h1>
```
---

En un archivo separado
```html
// miarchivo.css

<link rel="stylesheet" href="miarchivo.css">
```

## Anatomia CSS (estructura CSS)
```css

<selector> {
    <propiedad> : <valor> ;
    <priedadad> : <valor> ;
}

```

ejemplo:
```css

p {
   color: red;
   background: black;
}

i {
  color:blue;
}

```

## Modelo Caja Contenedor CSS

- **margin** (margen) : exterior (1 metro)
- **border** (borde) : piel
- **padding** (relleno) : interior 
- contenido : corazón

**DIRECCIONES**
- **top**: superior
- **bottom**: inferior
- **right**: derecha
- **left**: izquierda
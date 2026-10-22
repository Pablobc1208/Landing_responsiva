## Versión con Sass (rama `sass`)

La landing se ha rehecho con **Sass (SCSS)** y se compila a CSS normal.

- **Mixins:** `up()` (media queries), `pill()`, `btn-solid()`, `btn-outline()`, `section-title()`.
- **Funciones propias:** `tone()`, `rem()`, `shade()`, `alpha()`, `sea-gradient()`.
- **Funciones nativas de Sass:** `map.get`, `map.has-key`, `math.div`, `list.nth`, `color.adjust`, `color.change`.
- **Estructura:** parciales en `scss/` (`_variables`, `_functions`, `_mixins`, `_base`, `_buttons`, `_navbar`, `_hero`, `_cards`, `_galeria`, `_footer`) y `dark.scss` para el modo oscuro.

### Compilar

```bash
npm install
npm run build    # compila scss/ a css/
npm run watch    # recompila al guardar
```

### Demo

https://pablobc1208.github.io/Landing_responsiva/

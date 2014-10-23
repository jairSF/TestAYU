## Issues & Improvements
---

- El EBM tiene únicamente un set de Media Queries que debe extenderse a los sufijos: _up_, _down_, _only_.
- Los `grid-lists` del EBM necesitan extenderse para funcionar completamente con los media queries con los mismos sufijos _up_, _down_, _only_.
- Los contenedores custom deben funcionar únicamente en `@media md-up`


## Ayu Consulting S.A.C.

Ayu Consulting Frontend Boilerplate

### Etapa de Desarrollo

Desde la consola navega hasta el directorio "stylesheets" y ejecuta: 

  	sass --watch main.scss:main.css

### Etapa de Producción

Desde la consola navega hasta el directorio "stylesheets" y ejecuta: 

  	sass --watch main.min.scss:main.min.css -t compressed

#### Consideraciones

Optimiza tu editor de texto así: 

		{
			"caret_style": "phase",
			"font_size": 14,
			"highlight_line": true,
			"line_padding_bottom": 1,
			"line_padding_top": 1,
			"margin": 2,
			"tab_size": 2
		}

__Al nombrar tus clases y id's piensa:__

> Si alguien más tomara este proyecto, sabría a qué me refiero?


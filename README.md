# Maqueta Bootstrap - Cisco Networking Academy

Trabajo de **DAW 2026 - Diseño con Bootstrap** (FP San Antonio).

Maqueta de la web de [Cisco Networking Academy](https://www.cisco.com/site/us/en/learn/training-certifications/training/netacad/index.html) hecha con [Bootstrap 5](https://getbootstrap.com/) y su sistema de grid.

## Contenido de la maqueta

| Fila | Elemento | Componente Bootstrap |
|------|----------|----------------------|
| 1 | Cabecera (menú, logo, herramientas) | `navbar` + grid de 3 columnas |
| 2 | Jumbotron | `carousel` |
| 3-8 | Damero card / imagen esquemática | `card` image-overlay + `col-12 col-md-6` |
| 9-10 | Banner de ancho completo | `container` + utilidades |
| 12 | Cuatro imágenes con detalle | `collapse` + `col-12 col-md-3` |
| 13 | Redes sociales | Iconos (Bootstrap Icons) / `accordion` en móvil |

Extras:
- `loading="lazy"` en las imágenes.
- Efecto de aparición al hacer scroll con `IntersectionObserver` (sin librerías).

## Cómo verlo

Abre `index.html` en el navegador (necesita conexión a Internet por los CDN de Bootstrap y las imágenes). Reduce el ancho de la ventana para ver el diseño responsive.

## Autor

Jose Pérez

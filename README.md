# TramitaNet — La Pape

**Trámites oficiales de México en un solo lugar**: hazlos en línea o agenda tu cita **sin gestores ni intermediarios**, con enlaces directos a los portales oficiales `.gob.mx`.

## Qué ofrece

- Directorio de trámites oficiales por categoría.
- Sección de **pagos y servicios**.
- Para cada trámite: hacerlo en línea o agendar cita, sin intermediarios.

## El sitio

- Estático, en HTML, CSS y JavaScript, sin compilación.
- Página principal en `index.html` y una página por servicio en `servicios/`.

| Ruta | Contenido |
| --- | --- |
| `index.html` | Página principal y buscador de trámites |
| `servicios/` | Páginas de cada trámite o servicio |
| `images/` | Imágenes del sitio |

## Cómo ejecutarlo

Abrir `index.html` en un navegador moderno, o servir la carpeta:

```bash
python3 -m http.server 8000
```

## Sitio en vivo

https://frankjunker87-arch.github.io/tramitanet-la-pape/

## Contribuidores

Contribución preparada en colaboración por **psehgaft**, **san985tos**, **frankjunker87-arch** y **tec-girl**.

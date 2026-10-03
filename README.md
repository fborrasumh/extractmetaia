# ExtractMetaIA

**De papers a tablas listas para meta-análisis**, con trazabilidad y confirmación humana.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Compañera de [MetaAnálisisIA](https://fborrasumh.github.io/metaanalisisia/) · Catálogo [fborrasumh/ia](https://fborrasumh.github.io/ia/) · UMH

## Qué hace

1. Define el proyecto (pregunta PICO / outcomes)
2. Elige o personaliza el **esquema de extracción**
3. Pega texto de papers (abstract, results, tablas) o carga demo
4. La IA **propone** valores; tú **aceptas, corriges o rechazas** cada celda
5. Exporta CSV / JSON listo para **MetaAnálisisIA** (columnas `study`, `yi`, `sei`, …)
6. Informe de auditoría: qué propuso la IA y qué cambió el humano

**Principio Forja:** la IA propone, el código y la persona verifican. Nada se guarda como definitivo sin confirmación.

## Privacidad

- Textos y tablas permanecen en el navegador salvo que actives una llamada a un proveedor de IA.
- La API key la introduces tú y solo se usa en tu sesión.
- El ejemplo demo funciona **sin clave**.

## Flujo con MetaAnálisisIA

```
ExtractMetaIA  →  CSV/JSON  →  MetaAnálisisIA
(extracción)      (export)     (síntesis)
```

## Autor

**Fernando Borrás Rocher**  
Universidad Miguel Hernández de Elche  
ORCID: [0000-0002-5519-4573](https://orcid.org/0000-0002-5519-4573)

## Límites

- La extracción de PDF nativo no está incluida en v0.1 (pega texto o tablas).
- Las propuestas de la IA pueden errar: la confirmación humana es obligatoria.
- No sustituye la doble extracción independiente de una revisión Cochrane formal.

## Licencia

MIT · Ver [LICENSE](LICENSE)

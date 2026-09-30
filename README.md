# UI — Generador de Reportes con Lenguaje Natural

Diseño de la interfaz de usuario (UI) para el frontend de una aplicación que permite
generar reportes sobre una base de datos a partir de consultas en **lenguaje natural**.

El usuario escribe su consulta en lenguaje cotidiano (por ejemplo, *"ventas del último
trimestre por región"*), el sistema la compila a SQL, la ejecuta y devuelve el reporte
con los datos correspondientes.

> **Estado: versión inicial.** Solo se han diseñado algunas pantallas. Faltan la mayoría
> de los flujos y estados.

---

## Alcance del repositorio

Este repositorio contiene **únicamente los diseños de la interfaz**. No incluye código de
producción, backend, conexión a base de datos ni lógica de negocio.

La implementación del frontend se realizará en otro repositorio, tomando estos archivos
como fuente de verdad para la experiencia de usuario.

---

## Estructura

Los diseños están separados por plataforma:

```
UI/
├── pc/        # Escritorio (desktop)
└── movil/     # Móvil (mobile)
```

Dentro de cada plataforma, una carpeta por pantalla:

```
pc/login/
├── code.html    # Mockup navegable en HTML + CSS
├── DESIGN.md    # Especificación del sistema de diseño de la pantalla
└── screen.png   # Vista previa renderizada
```

Las pantallas que aún no tienen ese desarrollo se guardan comprimidas en `.zip`.

### Pantañas disponibles

| Pantalla               | Escritorio | Móvil |
| ---------------------- | :---------: | :---: |
| Onboarding             | ✅         | ✅    |
| Login                  | ✅         | ✅    |
| Listado de Tenants     | ✅         | ✅    |
| CRUD usuarios — list   | ✅         | ✅    |
| CRUD usuarios — form   | ✅         | ✅    |
| CRUD planes — list     | ✅         | ✅    |
| CRUD planes — form     | ✅         | ✅    |

Cada carpeta incluye su `DESIGN.md`, que documenta colores, tipografía, espaciado,
elevación y los componentes de esa pantalla.

---

## Herramienta de diseño

Todas las interfaces fueron diseñadas con **[Stitch](https://stitch.withgoogle.com)**, la
herramienta de diseño de Google con asistencia de IA.

El proyecto original, desde donde se exportaron los archivos de este repositorio, está
disponible en:

> https://stitch.withgoogle.com/projects/15537056327534531092?pli=1

Cualquier modificación o pantalla nueva debe realizarse primero en Stitch y luego
exportarse a este repositorio, manteniendo la estructura de carpetas establecida.

---

## Sistema de diseño

Definido de forma consistente entre todas las pantallas y detallado en los archivos
`DESIGN.md`.

- **Estética:** entorno analítico de alta precisión, oscuro, entre ergonomía de
  herramientas de desarrollo y superficies técnicas de alto refinamiento.
- **Tipografías:** **Geist** para texto e interacción; **JetBrains Mono** para SQL,
  datos, claves de esquema y métricas.
- **Color:** base en azul marino profundo (`#090d16`) con acentos de cian luminoso
  (`#06b6d4`) y cobalto eléctrico (`#2563eb`).
- **Elevación:** mediante luminosidad de superficie y bordes de bajo contraste, sin
  sombras duras. Las tarjetas en estado de inferencia de AI emiten un halo cian difuso.
- **Radios:** geometría suave pero técnica (4–8 px), con Pills completamente redondeados
  para chips de estado y badges de esquema.

Cada pantalla cuenta con su propio `DESIGN.md`; al agregar una pantalla nueva se debe
mantener esta misma línea visual y documentar sus decisiones.

---

## Estado y próximos pasos

- [x] Onboarding y Login (escritorio)
- [x] Onboarding y Login (móvil)
- [x] Pantallas CRUD de usuarios y planes, y listado de tenants
- [ ] Pantalla principal de consulta en lenguaje natural (prompt, SQL generado, resultados)
- [ ] Estados de carga, error y vacío para cada pantalla
- [ ] Definir un `DESIGN.md` global con los tokens compartidos
- [ ] Completar el resto de pantallas y flujos de usuario
- [ ] Especificar el comportamiento responsive entre `pc/` y `movil/`

---

## Convenciones

- Nombres de carpeta en minúsculas, separados por guiones: `crud usuarios - list`.
- Cada pantalla debe incluir `code.html`, `DESIGN.md` y `screen.png`.
- Mantener el nombre de la pantalla y su estructura idénticos entre `pc/` y `movil/`.
- Documentar en el `DESIGN.md` los tokens propios de la pantalla, evitando duplicar lo
  que ya está definido en otras pantallas.

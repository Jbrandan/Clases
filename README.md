# Materias 2027

Presentaciones de las materias para incrustar en Moodle. Cada clase se publica en su propia carpeta y contiene todos sus recursos.

## Organización

```text
docs/
  index.html                         Página neutra, sin catálogo ni enlaces
  404.html                           Página neutra para rutas inexistentes
  taller-integrador-rol-policial/
    clase-01/
      index.html                     Presentación de la clase
      styles.css                     Diseño exclusivo de esta clase
      app.js                         Navegación y actividades de esta clase
      assets/                        Escudos y lectura PDF de esta clase
```

Para las siguientes materias, crear otra carpeta dentro de `docs`. Para las siguientes clases, crear `clase-02`, `clase-03`, etc., dentro de la materia correspondiente. Utilizar nombres en minúsculas, sin espacios ni tildes, para mantener direcciones sencillas y estables.

## Independencia entre clases

- Cada clase tiene un enlace directo y todos sus recursos en su propia carpeta.
- Los botones Anterior, Siguiente e Índice recorren únicamente las pantallas de la clase abierta.
- No hay un catálogo público ni enlaces de navegación a otras clases o materias.
- No se comparten hojas de estilo ni scripts entre clases: cambiar una no altera el diseño de las demás.
- La actualización de una clase conserva su URL mientras no se cambie el nombre de su carpeta.
- No se debe agregar navegación automática a la siguiente clase.

Esta separación es de contenido y navegación. No es una restricción de acceso: si el sitio es público, sus direcciones pueden abrirse fuera de Moodle y los archivos públicos del repositorio pueden consultarse.

## Publicación en GitHub Pages

Repositorio previsto: `materias-2027`. La estructura local está preparada; la publicación remota requiere una cuenta de GitHub conectada.

En Settings → Pages, seleccionar Deploy from a branch, rama `main`, carpeta `/docs` y guardar. Esperar a que GitHub confirme la publicación. No cambiar el nombre del repositorio o de las carpetas una vez que las direcciones se hayan incorporado al aula, salvo que también se actualicen los enlaces de Moodle.

Documentación oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Dirección de la primera clase

Ejemplo pendiente de sustituir `USUARIO` por la cuenta real:

```text
https://USUARIO.github.io/materias-2027/taller-integrador-rol-policial/clase-01/
```

## Incrustación en Moodle

```html
<iframe
  src="https://USUARIO.github.io/materias-2027/taller-integrador-rol-policial/clase-01/"
  title="Taller Integrador para la Construcción del Rol Policial · Clase 1"
  width="100%"
  height="820"
  style="border:0; border-radius:8px;"
  allow="fullscreen"
  allowfullscreen
  loading="lazy">
</iframe>
```

La dirección es ilustrativa hasta que se cree y publique el repositorio. Los permisos de Moodle deben permitir insertar iframe.

## Material de la clase 1

Síntesis del desarrollo de temas de la clase 1 aportado por el docente; el PDF original se incluye en la carpeta de esa clase. La presentación acompaña la lectura obligatoria, conserva los escudos suministrados e incluye portada, conclusión y despedida.

Para el foro se priorizó el desarrollo de temas de 2026 frente al itinerario de 2025. Se corrigió en la síntesis la fecha de adopción de la Resolución 34/169: 17 de diciembre de 1979. El PDF original no fue modificado. Las actividades son de práctica y no envían notas ni finalización a Moodle.

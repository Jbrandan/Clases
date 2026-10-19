# Clases · Materiales para Moodle

Presentaciones de las materias para incrustar en Moodle. Cada clase se publica en su propia carpeta y contiene todos sus recursos.

## Organización

```text
docs/
  index.html                         Página neutra, sin catálogo ni enlaces
  404.html                           Página neutra para rutas inexistentes
  Taller_Integrador_para_la_Construccion_del_Rol_Policial/
    Clase_01/
      index.html                     Presentación de la clase
      styles.css                     Diseño exclusivo de esta clase
      app.js                         Navegación y actividades de esta clase
      assets/                        Escudos y lectura PDF de esta clase
```

Para las siguientes materias, crear otra carpeta dentro de `docs`. Para las siguientes clases, crear `Clase_02`, `Clase_03`, etc., dentro de la materia correspondiente. Utilizar nombres sin espacios ni tildes y conservar exactamente las mayúsculas y minúsculas de las carpetas al compartir las direcciones.

## Independencia entre clases

- Cada clase tiene un enlace directo y todos sus recursos en su propia carpeta.
- Los botones Anterior, Siguiente e Índice recorren únicamente las pantallas de la clase abierta.
- No hay un catálogo público ni enlaces de navegación a otras clases o materias.
- No se comparten hojas de estilo ni scripts entre clases: cambiar una no altera el diseño de las demás.
- La actualización de una clase conserva su URL mientras no se cambie el nombre de su carpeta.
- No se debe agregar navegación automática a la siguiente clase.

Esta separación es de contenido y navegación. No es una restricción de acceso: si el sitio es público, sus direcciones pueden abrirse fuera de Moodle y los archivos públicos del repositorio pueden consultarse.

## Publicación en GitHub Pages

Repositorio previsto: `Clases`. Repositorio remoto creado por el usuario: https://github.com/Jbrandan/Clases. GitHub Pages publica la rama `main`, carpeta `/docs`.

En Settings → Pages, seleccionar Deploy from a branch, rama `main`, carpeta `/docs` y guardar. Esperar a que GitHub confirme la publicación. No cambiar el nombre del repositorio o de las carpetas una vez que las direcciones se hayan incorporado al aula, salvo que también se actualicen los enlaces de Moodle.

Documentación oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Dirección de la primera clase

Dirección de la primera clase:

```text
https://Jbrandan.github.io/Clases/Taller_Integrador_para_la_Construccion_del_Rol_Policial/Clase_01/
```

## Incrustación en Moodle

```html
<iframe
  src="https://Jbrandan.github.io/Clases/Taller_Integrador_para_la_Construccion_del_Rol_Policial/Clase_01/"
  title="Taller Integrador para la Construcción del Rol Policial · Clase 1"
  width="100%"
  height="820"
  style="border:0; border-radius:8px;"
  allow="fullscreen"
  allowfullscreen
  loading="lazy">
</iframe>
```

Las clases 01 a 30 utilizan el mismo formato, sustituyendo `Clase_01` por el número correspondiente. Los permisos de Moodle deben permitir insertar iframe.

## Material de la clase 1

Síntesis del desarrollo de temas de la clase 1 aportado por el docente; el PDF original se incluye en la carpeta de esa clase. La presentación acompaña la lectura obligatoria, conserva los escudos suministrados e incluye portada, conclusión y despedida.

Para el foro se priorizó el desarrollo de temas de 2026 frente al itinerario de 2025. Se corrigió en la síntesis la fecha de adopción de la Resolución 34/169: 17 de diciembre de 1979. El PDF original no fue modificado. Las actividades son de práctica y no envían notas ni finalización a Moodle.


## Clases 02 a 30

Cada carpeta `Clase_XX` incorpora su presentación independiente, datos de contenido, lectura HTML de los documentos originales, recursos y actividades de práctica. Los controles de navegación permanecen dentro de la clase. No hay un índice público entre clases.

Las instancias de evaluación y recuperación se presentan como orientación y repaso. Los exámenes, bancos de preguntas y entregas formales permanecen en Moodle. Las prácticas interactivas no envían ni almacenan calificaciones. Las notas y listas de revisión son temporales.

Los documentos fuente presentan diferencias de ciclo lectivo y algunas referencias cruzadas inconsistentes. Las presentaciones remiten al cronograma y condiciones del aula, y el lector de originales identifica que conserva el contenido de los archivos aportados. El informe docente de revisión y la lista completa de enlaces se entregan por separado, fuera del sitio público.

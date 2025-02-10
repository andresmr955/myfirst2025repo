Herramientas útiles para documentación con Markdown

En las clases anteriores has visto la relevancia de trabajar con Markdown y lo mucho que este lenguaje te puede ayudar para crear una gran documentación. En esta clase lo que veremos son algunos de los muchísimos recursos que puedes utilizar para poder escribir de una gran manera utilizando Markdown de la mejor manera posible. ¡Comencemos!

Documentación de Markdown

Simplemente, la mejor referencia para conocer todo lo que se puede hacer con Markdown dentro de los documentos, aquí puedes comenzar a leer mucho.
Markdown page


![Markdownlint][def]
Mi primera sugerencia es irte a la opción de Cheat Sheet, en esta sección podrás encontrar todo lo que puedes hacer, desde la sintaxis básica hasta la extendida. Lo mejor que puedes hacer comenzar a practicar aquí con esto, la verdad es que si sabes usar estas características ya estás dominando el 90% de todo el trabajo.

También considera que Markdown es compatible con algunas funciones de html como , lo que te permitiría jugar un poco más con el diseño de tu documento.

Si tienes un poco más de tiempo libre estaría fenomenal visitar la sección de Get Started en donde el sitio explica como funciona Markdown lo que es una lectura muy buena para aprender un poco más. ¡Dale un vistazo!

Diagramas Mermaid

Dejando de lado la funcionalidad básica de lo que puedes hacer con los markdown y VS Code podemos dar un paso adelante y utilizar una herramienta que te hará hacer documentos de otro nivel con los diagramas mermaid.

Estos diagramas te permiten diseñar gráficas de muchos niveles y personalizarlas con la complejidad que deseas.

Por ejemplo, gracias a un código similar al siguiente podrás representar el flujo de interacción entre diferentes ramas, muy acorde a nuestro curso ¿no?

```mermaid
gitGraph
    commit
    commit
    branch develop
    checkout develop
    commit id: "Commit en develop 1"
    commit: "COmmit en develop 2"
    checkout main
    merge develop
    commit
    commit

Al insertar el código en tu documento podrás ver el resultado luciendo como esta imagen.

[def]: img02.png
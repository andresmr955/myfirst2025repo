# DiagramasMermaid

Dejando de lado la funcionalidad básica de lo que puedes hacer con los markdown y VS Code podemos dar un paso adelante y utilizar una herramienta que te hará hacer documentos de otro nivel con los diagramas mermaid.

Estos diagramas te permiten diseñar gráficas de muchos niveles y personalizarlas con la complejidad que deseas.

Por ejemplo, gracias a un código similar al siguiente podrás representar el flujo de interacción entre diferentes ramas, muy acorde a nuestro curso ¿no?

```mermaid

gitGraph
    commit
    commit
    branch develop
    checkout develop
    commit
    commit
    checkout main
    merge develop
    commit
    commit


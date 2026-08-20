---
{"dg-publish":true,"permalink":"/bienvenido/","tags":["gardenEntry"],"dg-note-properties":{}}
---

Este es mi prototipo de Wiki-Med

```base
views:
  - type: table
    name: Tabla
    filters:
      and:
        - '!file.inFolder("99_ADJUNTOS")'
    groupBy:
      property: file.folder
      direction: ASC

```



---

# Taller de CNC

Este repositorio contiene el trabajo realizado para el Taller de Computación en la Nube (CNC).

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="linux logo"  />

</div>

## Estructura de Directorios

```
Computación_en_la_nube
│
└── CNC
    │
    └── Taller_1
        │
        ├── bisabuela
        │   └── archivo_bisabuela.txt
        │
        ├── bisabuelo
        │   └── archivo_bisabuelo.txt
        │
        ├── abuela
        │   └── archivo_abuela.txt
        │
        ├── abuelo
        │   └── archivo_abuelo.txt
        │
        ├── mamá
        │   ├── archivo_mamá.txt
        │   └── archivo_papá.txt
        │
        ├── papá
        │
        ├── hija
        │   └── archivo_hija.txt
        │
        ├── hijo
        │
        ├── nieta
        │   └── archivo_nieta.txt
        │
        └── nieto
            └── archivo_nieto.txt
```

## Información de Archivos

Cada archivo contiene la siguiente información:

- Nombre
- Apellido
- Estatura
- RH (Tipo de Sangre)
- Fecha de Nacimiento

## Moviendo Archivos

Para cumplir con el requerimiento de mover los archivos masculinos a los femeninos, se han realizado las siguientes acciones:

```bash
mv CNC/Taller_1/papá/archivo_papá.txt CNC/Taller_1/mamá/
mv CNC/Taller_1/hijo/archivo_hijo.txt CNC/Taller_1/hija/
mv CNC/Taller_1/nieto/archivo_nieto.txt CNC/Taller_1/nieta/
```

## Comando `tree`

El comando `tree` ha sido instalado y ejecutado en el directorio Taller_1 para visualizar la estructura de archivos y directorios en formato de árbol.

<div align="center">
  <img height="300" src="https://media.tenor.com/dHk-LfzHrtwAAAAi/linux-computer.gif"  />
</div>

###


Este README proporciona una descripción general del contenido y las acciones realizadas en el taller de CNC.

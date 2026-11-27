# Cadenas y Punteros — Control de acceso en la RAM

**Actividad 4 — Manipulación de cadenas y punteros en C/C++** · Laboratorio de Programación · 5.º 3.ª A-B · E.E.S.T. N.º 1 «Eduardo Ader»

Sistema básico de **control de acceso por edad** que opera directamente sobre la memoria RAM:
el puntero `int* p = &edad;` guarda la dirección de la variable y el programa usa la
**desreferenciación** (`*p`) para leer y escribir su valor, mostrando además la dirección
hexadecimal real donde vive la variable.

- Estudiante: **Alexis Maier**

## Datos institucionales

- **Institución:** E.E.S.T. N.º 1 «Eduardo Ader» — Vicente López
- **Curso:** 5.º 3.ª A-B
- **Materia:** Laboratorio de Programación (LPR)
- **Profesor:** Prof. York
- **Actividad:** 4 — Manipulación de cadenas y punteros en C/C++

## Presentación de la Actividad

Control de acceso por edad que opera directamente sobre la RAM mediante el puntero int* p = &edad, los operadores & y * y direcciones hexadecimales.

## Integrantes y roles

| Integrante | Rol / tarea asignada | Aporte individual |
|---|---|---|
| Alexis Maier | Mapeo de direcciones, desreferenciación, cuestionario de memoria e informe | [cadenas-punteros](https://github.com/alitomaier2010-netizen/cadenas-punteros) |

## Requisitos e instalación

1. **Git** instalado para clonar el repositorio.
2. **Editor de código** (VS Code con extensiones de C/C++, o Visual Studio Community).
3. **Compilador g++** (MinGW-w64 / MSYS2) agregado al `PATH` del sistema.
4. Clonar y situarse en el directorio:

```bash
git clone https://github.com/alitomaier2010-netizen/cadenas-punteros.git
cd cadenas-punteros
```

## Estructura

```
cadenaspunteros/
├── .gitignore
├── LICENSE
├── README.md
├── capturas/
│   ├── ejecucion_punteros.png     terminal con direcciones hexadecimales
│   └── esquema_ram.png            diagrama de la memoria (puntero y variable)
├── docs/
│   └── InformeProyectoCADENASPUNTEROS.pdf
└── src/
    └── main.cpp
```

## Compilar y ejecutar (PowerShell)

```
g++ src/main.cpp -o src/cadenaspunteros.exe
.\src\cadenaspunteros.exe
```

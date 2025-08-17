# Proyecto OpenGL - Triángulo Básico

Este es un proyecto de OpenGL en C++ que muestra un triángulo básico en pantalla usando GLEW y GLFW.

## Descripción

Es la práctica 0 en donde vimos:
- Inicialización de OpenGL con GLFW
- Uso de GLEW para cargar extensiones de OpenGL
- Renderizado de geometría básica

## Requisitos del Sistema

- macOS con Xcode Command Line Tools
- Homebrew
- OpenGL (incluido en macOS)
- GLFW (para manejo de ventanas)
- GLEW (para extensiones de OpenGL)

## Instalación

1. **Instalar dependencias** (si no están instaladas):
   ```bash
   make install-deps
   ```

2. **Compilar el proyecto**:
   ```bash
   make
   ```

## Uso

Para ejecutar la aplicación:
```bash
make run
```

O ejecutar directamente:
```bash
./opengl_app
```

## Comandos Disponibles

- `make` - Compilar el proyecto
- `make run` - Compilar y ejecutar el proyecto
- `make clean` - Limpiar archivos compilados
- `make install-deps` - Instalar dependencias con Homebrew
- `make help` - Mostrar ayuda con todos los comandos

## Estructura del Proyecto

```
CGIH12-master/
├── configInicial/
│   ├── Main.cpp              # Código fuente principal
│   ├── glew32.dll           # DLL de GLEW para Windows (no usado en macOS)
│   └── [archivos VS]        # Archivos de Visual Studio (no usados en macOS)
├── Makefile                 # Sistema de build para macOS
└── README.md               # Este archivo
```


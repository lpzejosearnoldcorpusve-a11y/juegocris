# Frets on Fire

Frets on Fire es un juego de habilidad musical y dedos rápidos. El objetivo del juego es tocar la guitarra con el teclado de la manera más precisa posible.

## Instalación

### 1. Instalar Miniconda

Descarga e instala Miniconda desde el sitio oficial: [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

### 2. Crear un entorno con Python 2.7

Abre una terminal (PowerShell en Windows) y ejecuta:

```bash
conda create -n fretsonfire python=2.7 -y
```

### 3. Activar el entorno

```bash
conda activate fretsonfire
```

### 4. Instalar las dependencias

Desde el directorio raíz del proyecto (donde está este README.md), ejecuta:

```bash
pip install -r requirements.txt
```

### 5. Ejecutar el juego

Cambia al directorio `src` y ejecuta el juego:

```bash
cd src
python FretsOnFire.py
```

## Requisitos del sistema

- Python 2.7
- PyGame
- PyOpenGL
- Python Imaging Library (Pillow)
- NumPy

## Notas adicionales

- Asegúrate de tener controladores de video recientes con soporte OpenGL.
- El juego requiere archivos SVG que se convierten a texturas PNG; asegúrate de que Inkscape esté instalado si necesitas actualizar gráficos.

## Licencia

Este programa es software libre; puedes redistribuirlo y/o modificarlo bajo los términos de la Licencia Pública General de GNU versión 2.
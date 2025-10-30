# Paint Game 🎨

Una aplicación de dibujo simple creada con Python Turtle, parte de la colección **Free Python Games**.

## 📋 Descripción

Este es un programa de dibujo interactivo que te permite crear formas geométricas con diferentes colores haciendo clic en la pantalla. Perfecto para crear dibujos simples y diseños geométricos.

## 🎮 Cómo Usar

### 🖱️ Dibujar Formas

1. **Primer clic**: Define el punto de inicio de la forma
2. **Segundo clic**: Define el punto final y dibuja la forma
3. La forma se dibuja automáticamente entre los dos puntos

### ⌨️ Controles de Teclado

#### Seleccionar Formas
- `L` - **Línea**: Dibuja una línea recta
- `S` - **Cuadrado**: Dibuja un cuadrado
- `C` - **Círculo**: Dibuja un círculo *(por implementar)*
- `R` - **Rectángulo**: Dibuja un rectángulo *(por implementar)*
- `T` - **Triángulo**: Dibuja un triángulo *(por implementar)*

#### Seleccionar Colores
- `K` - **Negro** (Black)
- `W` - **Blanco** (White)
- `G` - **Verde** (Green)
- `B` - **Azul** (Blue)
- `R` - **Rojo** (Red)
- `M` - **Magenta** (Magenta)

#### Otras Funciones
- `U` - **Deshacer**: Elimina el último dibujo

## 🎨 Formas Disponibles

### ✅ Implementadas
- **Línea**: Dibuja una línea recta desde el punto inicial hasta el punto final
- **Cuadrado**: Dibuja un cuadrado relleno usando la distancia horizontal como tamaño
- **Círculo**: Dibuja un circulo calculando el radio con punto inicial y punto final

### 🚧 Por Implementar (TODO)
- **Rectángulo**: Función definida pero sin implementación
- **Triángulo**: Función definida pero sin implementación

## 🔧 Requisitos

```bash
pip install freegames
```

## 🚀 Ejecución

```bash
python paint.py
```

O si tienes instalado `freegames`:

```bash
python -m freegames.paint
```

## 📦 Dependencias

- **Python 3.x**
- **turtle** (incluido en Python estándar)
- **freegames**: Librería que proporciona la clase `vector`

## 🎲 Características Técnicas

- Ventana de dibujo: 420x420 píxeles
- Sistema de estado para almacenar punto inicial y forma seleccionada
- Función de deshacer para eliminar el último trazo
- 5 colores predefinidos disponibles
- Sistema de dos clics para definir formas

## 💡 Ejemplo de Uso

```
1. Presiona 'B' para seleccionar color azul
2. Presiona 'S' para seleccionar cuadrado
3. Haz clic en la pantalla para definir el primer punto
4. Haz clic en otro lugar para completar el cuadrado
5. Presiona 'U' si quieres deshacer
```

## 🛠️ Posibles Mejoras

El código incluye funciones para círculo, rectángulo y triángulo que están marcadas con `# TODO` y pueden ser implementadas:

```python
def circle(start, end):
    # Implementar dibujo de círculo
    
def rectangle(start, end):
    # Implementar dibujo de rectángulo
    
def triangle(start, end):
    # Implementar dibujo de triángulo
```

## 📝 Estructura del Código

- **`line()`**: Dibuja líneas
- **`square()`**: Dibuja cuadrados rellenos
- **`tap()`**: Maneja los clics del mouse
- **`store()`**: Almacena valores en el estado de la aplicación
- **`state`**: Diccionario que mantiene el punto inicial y la forma seleccionada

## 📝 Créditos

Este código pertenece a **Free Python Games**, una colección de juegos simples implementados en Python para fines educativos.

🔗 [Free Python Games - GitHub](https://github.com/grantjenks/free-python-games)

## 📄 Licencia

Este código es parte de Free Python Games. Consulta la licencia original del proyecto para más información.

---

**¡Diviértete creando tus propios dibujos geométricos! 🖌️**

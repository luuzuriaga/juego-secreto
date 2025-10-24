# 🎮 Juego del Número Secreto

Un juego interactivo de adivinanza de números desarrollado con JavaScript vanilla, HTML y CSS.

## 📋 Descripción

El Juego del Número Secreto es una aplicación web donde el jugador debe adivinar un número generado aleatoriamente por la computadora. El juego proporciona pistas indicando si el número secreto es mayor o menor que el número ingresado.

![Vista previa del proyecto](./img/home.png)

## ✨ Características

- 🎯 Generación aleatoria de números del 1 al 10
- 💡 Sistema de pistas (mayor/menor)
- 🔢 Contador de intentos
- 🚫 Prevención de números repetidos en múltiples partidas
- 🔄 Función de reinicio de juego
- 📱 Interfaz responsive y moderna
- 🎨 Diseño atractivo con gradientes y efectos visuales

## 🚀 Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Google Fonts (Chakra Petch, Inter)

## 📁 Estructura del Proyecto
```
proyecto/
│
├── index.html          # Estructura principal del juego
├── style.css           # Estilos y diseño visual
├── app.js              # Lógica del juego
│
└── img/
    ├── ia.png          # Imagen de personaje
    ├── code.png        # Imagen de fondo
    └── Ruido.png       # Textura de fondo
```

## 🎮 Cómo Jugar

1. Abre el archivo `index.html` en tu navegador
2. El juego generará automáticamente un número secreto entre 1 y 10
3. Ingresa tu número en el campo de entrada
4. Haz clic en el botón "Intentar"
5. El juego te dará pistas si el número es mayor o menor
6. Continúa intentando hasta adivinar el número correcto
7. Una vez que aciertes, puedes hacer clic en "Nuevo juego" para jugar otra vez

## 💻 Instalación

1. Clona o descarga este repositorio
```bash
git clone [URL-del-repositorio]
```

2. Asegúrate de tener la carpeta `img` con las imágenes necesarias

3. Abre el archivo `index.html` en tu navegador favorito

No se requiere instalación de dependencias adicionales.

## 🔧 Funcionalidades Principales

### Generación de Números
- Utiliza `Math.random()` para generar números aleatorios
- Previene la repetición de números en partidas consecutivas
- Notifica cuando se han agotado todos los números posibles

### Validación de Intentos
- Compara el número ingresado con el número secreto
- Proporciona retroalimentación inmediata
- Cuenta la cantidad de intentos realizados

### Sistema de Reinicio
- Limpia el campo de entrada
- Genera un nuevo número secreto
- Reinicia el contador de intentos
- Habilita/deshabilita botones según el estado del juego

## 🎨 Personalización

Puedes personalizar el juego modificando las siguientes variables en `app.js`:
```javascript
let numeroMaximo = 10;  // Cambia el rango de números (por defecto: 1-10)
```

## 📝 Funciones Principales

- `asignarTextoElemento()` - Actualiza el contenido HTML de los elementos
- `verificarIntento()` - Valida el número ingresado por el usuario
- `generarNumeroSecreto()` - Genera números aleatorios sin repetir
- `condicionesIniciales()` - Configura el estado inicial del juego
- `reiniciarJuego()` - Reinicia el juego para una nueva partida
- `limpiarCaja()` - Limpia el campo de entrada

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el juego:

1. Fork el proyecto
2. Crea una rama para tu función (`git checkout -b feature/NuevaFuncion`)
3. Commit tus cambios (`git commit -m 'Agregar nueva función'`)
4. Push a la rama (`git push origin feature/NuevaFuncion`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👨‍💻 Autor

Desarrollado como proyecto de práctica de JavaScript.

## 🙏 Agradecimientos

- Diseño inspirado en interfaces modernas de gaming
- Fuentes de Google Fonts
- Comunidad de desarrolladores web

---

⭐ Si te gustó este proyecto, no olvides darle una estrella!
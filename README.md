# 🚀 Oscar Fuentes Portfolio

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-100000?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)

> Un portfolio interactivo con un juego espacial integrado que demuestra habilidades en desarrollo web creativo y gamificación.

![Portfolio Preview](https://via.placeholder.com/800x400/0a0a0a/00ff88?text=Oscar+Fuentes+Portfolio)

## ✨ Características Principales

### 🎮 **Juego Espacial Interactivo**
- **Sistema de niveles progresivos** - La dificultad aumenta con cada nivel
- **3 vidas con sistema de golpes** - Puedes recibir 3 impactos antes de perder una vida
- **Enemigos variados** - Asteroides, naves alienígenas y cometas
- **Física simulada** - Gravedad solar/lunar y colisiones realistas
- **Efectos de sonido** - Disparos, explosiones y ambiente espacial

### 🎨 **Diseño y UX**
- **100% Responsive** - Adaptado para móvil, tablet y desktop
- **Animaciones fluidas** - Transiciones suaves y efectos visuales
- **Modo inmersivo** - El juego oculta el contenido para una experiencia completa
- **Tipografía espacial** - Fuentes Orbitron y Space Grotesk

### 💼 **Sistema de Portfolio**
- **Gestión de proyectos** - Sube y administra proyectos dinámicamente
- **Visualización en modal** - Vista previa de proyectos sin salir del sitio
- **Panel de administración** - Sistema protegido para gestionar contenido
- **Almacenamiento local** - Los proyectos se guardan en el navegador

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Animaciones, gradientes, glassmorphism
- **JavaScript Vanilla** - Sin frameworks, código puro
- **Canvas API** - Renderizado del juego
- **Web Audio API** - Sistema de sonido
- **LocalStorage** - Persistencia de datos
- **JSZip** - Manejo de archivos comprimidos

## 📦 Instalación

### Opción 1: Clonar el repositorio
```bash
# Clonar el repositorio
git clone https://github.com/tunombre/portfolio.git

# Navegar al directorio
cd portfolio

# Abrir en el navegador
open index.html
```

### Opción 2: Descargar ZIP
1. Click en "Code" > "Download ZIP"
2. Descomprimir el archivo
3. Abrir `index.html` en tu navegador

### Opción 3: GitHub Pages
Visita directamente: `https://tunombre.github.io/portfolio`

## 🎯 Cómo Jugar

### Controles
- **⬆️⬇️⬅️➡️** - Mover la nave
- **Espacio** - Disparar láser
- **Shift** - Turbo boost
- **🔊** - Activar/desactivar sonido

### Objetivo
1. Elimina todos los asteroides y enemigos
2. Sobrevive 3 impactos antes de perder una vida
3. Completa niveles para aumentar tu puntuación
4. ¡Cuidado con los cometas!

## 🔐 Panel de Administración

Para acceder al panel de administración:
1. Navega a `#sudo` en la URL
2. Contraseña: `[CONFIGURAR_EN_PRODUCCIÓN]`

**Funcionalidades:**
- Subir nuevos proyectos
- Gestionar proyectos existentes
- Subir imágenes y archivos ZIP

## 📱 Responsive Design

| Dispositivo | Breakpoint | Características |
|------------|------------|-----------------|
| Móvil | < 480px | Menú hamburguesa, controles táctiles |
| Tablet | < 768px | Layout adaptado, proyectos en columna |
| Desktop | > 768px | Experiencia completa con todos los efectos |

## 🎨 Personalización

### Cambiar colores
```css
:root {
    --primary: #00ff88;    /* Verde neón */
    --secondary: #ff0088;  /* Rosa neón */
    --dark: #0a0a0a;      /* Fondo oscuro */
    --light: #fafafa;     /* Texto claro */
}
```

### Modificar el juego
- Velocidad de enemigos: Busca `this.speed` en las clases
- Cantidad de vidas: Modifica `playerLives = 3`
- Dificultad: Ajusta los límites en `spawnLevelEnemies()`

## 📊 Estructura del Proyecto

```
portfolio/
│
├── index.html          # Archivo principal
├── README.md          # Este archivo
└── assets/            # (Opcional) Imágenes y recursos
    ├── images/
    └── projects/
```

## 🚀 Deployment

### GitHub Pages
1. Sube el código a un repositorio
2. Ve a Settings > Pages
3. Selecciona la rama `main`
4. Tu sitio estará en `https://tunombre.github.io`

### Netlify
1. Arrastra la carpeta a [netlify.com](https://netlify.com)
2. ¡Listo! Deploy automático

### Vercel
```bash
npm i -g vercel
vercel
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas:

1. Fork el proyecto
2. Crea una rama (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Add: Nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📝 Roadmap

- [ ] Puntuación persistente (highscores)
- [ ] Más tipos de enemigos
- [ ] Power-ups para el jugador
- [ ] Modo multijugador local
- [ ] Temas visuales alternativos
- [ ] Integración con API backend
- [ ] Sistema de logros

## 🐛 Problemas Conocidos

- En Safari móvil, el audio puede no iniciarse automáticamente
- El rendimiento puede variar en dispositivos antiguos
- El límite de localStorage es ~5-10MB

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Autor

**Oscar Fuentes Fernandez**

- Portfolio: [En construcción]
- LinkedIn: [Tu LinkedIn]
- GitHub: [@tunombre](https://github.com/tunombre)

## 🙏 Agradecimientos

- Inspiración del diseño: Retro arcade games
- Fuentes: Google Fonts (Orbitron, Space Grotesk)
- Comunidad de desarrolladores web

---

<div align="center">

**[⬆ Volver arriba](#-oscar-fuentes-portfolio)**

Hecho con ❤️ y ☕ por Oscar Fuentes © 2024

</div>

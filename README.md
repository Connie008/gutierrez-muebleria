# Gutiérrez Mueblería - Sistema Web

## Información del Proyecto
**Cliente:** Gutiérrez Mueblería  
**Ubicación:** Calle Juárez Eje Sur 23, Tlajomulco De Zúñiga  
**Equipo:** InnovaSoft  
**Curso:** Desarrollo Web - UDG Virtual

## Estructura del Proyecto

```
gutierrez-muebleria/
├── index.html                    (Página principal - Analog)
├── catalogo.html                 (Tienda virtual con 20+ productos)
├── producto-detalle.html         (Detalle de producto con valoración)
├── quienes-somos.html           (Historia, Visión, Misión, Políticas, Ubicación)
├── contacto.html                (Formulario de contacto + Chat)
├── cotizacion.html              (Formulario de cotización)
├── preguntas-frecuentes.html    (FAQ con acordeón)
├── css/
│   └── styles.css               (Estilos compartidos - NO MODIFICAR SIN AVISAR)
├── images/                      (Imágenes del proyecto)
└── README.md                    (Este archivo)
```

## Colores del Proyecto

- **Primario:** #1976D2 (Azul confianza)
- **Secundario:** #FF9800 (Naranja cálido)
- **Acento:** #4CAF50 (Verde)
- **WhatsApp:** #25D366
- **Texto:** #333333
- **Fondo:** #FFFFFF

## Tipografía

- **Títulos:** Montserrat Bold
- **Cuerpo:** Roboto Regular
- **Tamaño base:** 16px

## Instrucciones para Trabajar

### 1. Clonar el Proyecto
Una vez que Analog suba el proyecto a GitHub:
```bash
git clone [URL-DEL-REPOSITORIO]
cd gutierrez-muebleria
```

### 2. Abrir en Visual Studio Code
```bash
code .
```

### 3. Asignación de Páginas
Cada miembro del equipo debe trabajar en su página asignada:

- **Analog:** index.html (página principal completa)
- **Miembro 2:** catalogo.html + producto-detalle.html
- **Miembro 3:** quienes-somos.html
- **Miembro 4:** contacto.html + preguntas-frecuentes.html
- **Miembro 5:** cotizacion.html

### 4. Reglas de Trabajo

#### ✅ PERMITIDO:
- Agregar contenido dentro del `<main class="main-content">`
- Usar las clases definidas en `styles.css`
- Agregar imágenes en la carpeta `images/`
- Agregar estilos específicos SOLO para tu página (dentro de un `<style>` en el HTML)

#### ❌ NO PERMITIDO:
- Modificar Header, Nav o Footer (son compartidos)
- Modificar `styles.css` sin coordinar con el equipo
- Cambiar colores o tipografía establecida
- Usar JavaScript

### 5. Clases CSS Disponibles

#### Contenedores:
- `.container` - Contenedor principal (max-width: 1200px)
- `.main-content` - Contenido principal

#### Grids:
- `.grid-2` - Grid de 2 columnas
- `.grid-3` - Grid de 3 columnas
- `.grid-4` - Grid de 4 columnas

#### Botones:
- `.btn` - Botón base
- `.btn-primary` - Botón azul
- `.btn-secondary` - Botón naranja
- `.btn-success` - Botón verde

#### Tarjetas:
- `.card` - Tarjeta con sombra

#### Formularios:
- `.form-group` - Grupo de campo de formulario

#### Títulos:
- `.page-title` - Título principal de página (36px, centrado)
- `.section-title` - Título de sección (32px, centrado)

### 6. Workflow de Git

#### Antes de empezar a trabajar:
```bash
git pull origin main
```

#### Después de hacer cambios:
```bash
git add .
git commit -m "Descripción clara de los cambios"
git push origin main
```

#### Mensajes de commit sugeridos:
- "Agregado contenido de página Quiénes Somos"
- "Completado catálogo con 20 productos"
- "Agregado formulario de contacto"
- "Corregido responsive de página principal"

### 7. Elementos Requeridos por el Profesor

Asegúrate de incluir:

- ✅ Logo oficial o diseño de logo
- ✅ Página Quiénes Somos con: Historia, Visión, Misión, Políticas de Calidad
- ✅ Ubicación física con mapa de Google Maps embebido
- ✅ Chat (diseño visual, no funcional)
- ✅ Sección de preguntas frecuentes (FAQ)
- ✅ Acceso a redes sociales (enlaces en footer)
- ✅ Slider de imágenes (CSS puro con radio buttons)
- ✅ Valoración de productos (estrellas en CSS)
- ✅ Tienda virtual con mínimo 20 productos
- ✅ Formulario de contacto
- ✅ Formulario de cotización

### 8. Testing Local

Abre cualquier archivo HTML en tu navegador para ver los cambios:
- Doble clic en el archivo HTML, O
- Click derecho > Abrir con > Navegador

### 9. Imágenes

#### Dónde conseguir imágenes:
- Tomar fotos propias de muebles (REQUERIDO por el profesor)
- Placeholder temporales: usar fondos de color sólido con texto

#### Formato recomendado:
- Formato: JPG para fotos, PNG para logos
- Tamaño máximo: 1MB por imagen
- Resolución: Máximo 1920px de ancho

#### Nombramiento:
- `logo.png`
- `hero-banner.jpg`
- `sala-moderna-01.jpg`
- `comedor-clasico-02.jpg`
- etc.

### 10. Responsive Design

El CSS ya incluye breakpoints:
- Desktop: > 1200px
- Tablet: 768px - 1199px
- Móvil: < 768px

**Prueba tu página en diferentes tamaños:**
- Usa F12 en el navegador
- Activa "Responsive Design Mode"
- Prueba en móvil, tablet y desktop

## Contacto del Equipo

- **Product Owner:** [Nombre]
- **Scrum Master:** [Nombre]
- **Development Team:**
  - Analog (index.html)
  - Cesar Martínez
  - Julieta Beltrán
  - Connie Garcirrojas
  - Jaretzy Najar

## Recursos Útiles

- [Google Fonts](https://fonts.google.com/) - Ya incluido en el proyecto
- [Google Maps Embed](https://www.google.com/maps) - Para el mapa de ubicación
- [Unsplash](https://unsplash.com/) - Fotos temporales (usar solo de prueba)

## Preguntas Frecuentes del Equipo

**P: ¿Puedo usar JavaScript?**  
R: No, el proyecto debe ser solo HTML/CSS.

**P: ¿Qué hago si necesito cambiar los estilos compartidos?**  
R: Contacta a Analog primero para coordinar.

**P: ¿Cómo hago el slider sin JavaScript?**  
R: Usa radio buttons ocultos con CSS. Hay instrucciones en cada página HTML.

**P: ¿El formulario tiene que enviar datos realmente?**  
R: No, es un prototipo NO funcional. Solo debe verse bien.

**P: ¿Dónde subo las imágenes que tome?**  
R: En la carpeta `images/` y actualiza el src en tu HTML.

## Notas Importantes

1. **Prototipo NO funcional:** Los formularios no envían datos, los botones no ejecutan acciones reales.
2. **Solo HTML/CSS:** No uses JavaScript salvo excepciones muy menores acordadas con el equipo.
3. **Commits frecuentes:** Sube tus cambios regularmente para evitar conflictos.
4. **Comunicación:** Usa WhatsApp del equipo para coordinar cambios importantes.
5. **Deadline:** [Agregar fecha de entrega]

---

**¡Éxito equipo InnovaSoft!** 🚀

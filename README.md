# ProyectoRefactor
Taller práctico de refactorización CSS para el módulo de Diseño de Interfaces Web

##  Descripción

Este proyecto es el resultado del **Taller Práctico RA2: "El Refactor"**, donde se transforma un sitio web caótico con estilos en línea y embebidos en un proyecto limpio, mantenible y profesional utilizando hojas de estilo externas.

El sitio web consiste en un **portfolio personal de 3 páginas**:
-  **Inicio** (`index.html`)
-  **Sobre mí** (`sobre.html`)
-  **Contacto** (`contacto.html`)

##  Objetivos del Proyecto

- ✅ Refactorizar código HTML eliminando estilos en línea y embebidos
- ✅ Centralizar todos los estilos en una hoja externa (`estilos.css`)
- ✅ Implementar una paleta de colores coherente
- ✅ Aplicar tipografías personalizadas de Google Fonts
- ✅ Utilizar selectores CSS eficientes (clases, IDs, etc.)
- ✅ Validar el CSS según estándares W3C
- **BONUS**: Migrar a SASS para usar variables y anidación

## Estructura del Proyecto
proyecto-refactorizado/
│
├── index.html          # Página principal
├── sobre.html          # Página sobre mí
├── contacto.html       # Página de contacto (con formulario)
│
├── css/
│   ├── estilos.css     # Hoja de estilos principal
│   └── estilos.scss    # (Opcional) Archivo SASS
│
└── README.md           # Este archivo
```

##  Diseño

### Paleta de Colores
```css
/* Color primario: #23967F */
/* Color secundario: #FFFFFF*/
/* Color terciario: #7DAF9C */
/* Color de texto: #23110F */
/* Color de footer: #E0E0E0 */

Según la psicología del color, el turquesa (color principal) transmite calma, tranquilidad y claridad mental. Es un color que combina la serenidad del azul con la armonía del verde, asociándose con la comunicación, la creatividad y el equilibrio emocional.
El blanco (color secundario) es el mejor complemento del turquesa: le da calidad al espacio y equilibra sus tonos. Perfecto para espacios respirables y diseño limpio.
El color terciario,un tono más suave y claro que refuerza la sensación de frescura, calma y accesibilidad. Complementa perfectamente al primario sin competir con él.
Y por último,el color del footer,neutro,profesional y que no entretiene y el color del texto,que es mas suave visualmente y da un toque cálido entre la paleta fria.
En conjunto,esta paleta comunica profesionalismo,creatividad,tranquilidad y accesibilidad.
```

### Tipografías
- **Encabezados**: 'Oswald'
- **Cuerpo de texto**: 'Open Sans'

## Tecnologías Utilizadas

- HTML5
- CSS3
- Google Fonts
- Flexbox
- SASS/SCSS *(opcional)*

##  Instalación y Uso

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/Pakoweb/ProyectoRefactor.git
   ```

2. **Abrir el proyecto**
   ```bash
   cd Proyecto-Refactor
   ```

3. **Visualizar**
   - Abre `index.html` en tu navegador
   - O usa Live Server en VS Code para desarrollo

### Para trabajar con SASS (Opcional)

1. Instala la extensión **Live Sass Compiler** en VS Code
2. Abre `estilos.scss`
3. Haz clic en "Watch Sass" en la barra de estado
4. Los cambios se compilarán automáticamente a `estilos.css`

## Características Implementadas

- [x] HTML limpio sin estilos en línea
- [x] CSS externo centralizado
- [x] Navegación responsive con efectos hover
- [x] Formulario de contacto estilizado
- [x] Diseño consistente en las 3 páginas
- [x] CSS validado por W3C
- [ ] Variables SASS (Bonus)


## Validación

El código CSS ha sido validado usando el [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).
<img width="982" height="891" alt="Captura de pantalla 2025-11-04 232856" src="https://github.com/user-attachments/assets/87a99837-b7a2-431d-bfa9-1aae210a28c5" />


**Resultado**: ✅ Sin errores

## Aprendizajes Clave

1. **Separación de responsabilidades**: HTML para estructura, CSS para estilos
2. **Mantenibilidad**: Un único archivo CSS facilita cambios globales
3. **Reutilización**: Las clases permiten aplicar estilos consistentes
4. **Buenas prácticas**: Código limpio, semántico y validado

## Autor

**Francisco Garcia Partida**
- GitHub: [@pakoweb](https://github.com/pakoweb)
- Módulo: Diseño de Interfaces Web 
- Curso: [2º DAW/2025/26]

## 📄 Licencia

Este proyecto es parte de un ejercicio académico del módulo DIW.

---

⭐ Si este proyecto te ha resultado útil, ¡dale una estrella en GitHub!

# 🏋️‍♂️ FitBuddy - Tu Compañero de Entrenamiento

## 📋 Descripción del Proyecto

FitBuddy es una aplicación móvil multiplataforma que conecta a usuarios y entrenadores para mejorar la experiencia del entrenamiento. La app permite registrarse, configurar un perfil, buscar compañeros de entrenamiento mediante filtros de ubicación y objetivos, crear y compartir rutinas o rutas, comunicarse a través de un chat interno y llevar un historial de entrenamientos.

**Diferencial clave:** A diferencia de otras aplicaciones deportivas, FitBuddy se centra en generar vínculos reales y motivación compartida, combinando tecnología con el aspecto social del entrenamiento.

## 🚀 Características Principales

### 👥 Para Usuarios (Trainees)
- **Emparejamiento Inteligente**: Conecta con entrenadores y compañeros según tus objetivos
- **Rutinas Personalizadas**: Accede a rutinas adaptadas a tu nivel y metas
- **Seguimiento de Progreso**: Monitorea tu rendimiento y evolución
- **Comunidad Activa**: Interactúa con otros usuarios mediante chat interno

### 👨‍🏫 Para Entrenadores
- **Gestión de Clientes**: Administra tu cartera de clientes de manera eficiente
- **Creación de Rutinas**: Diseña y comparte entrenamientos personalizados
- **Agenda Profesional**: Organiza tus sesiones y citas
- **Métricas de Desempeño**: Seguimiento del progreso de tus clientes

### ⚙️ Para Administradores
- **Gestión de Usuarios**: Control completo sobre la comunidad
- **Verificación de Entrenadores**: Aprobación de perfiles profesionales
- **Reportes y Analytics**: Métricas de uso y crecimiento de la plataforma
- **Moderación de Contenido**: Gestión de reportes y contenido inapropiado

## 🏗️ Estructura del Proyecto

```text
SITIO_APP_FITBUDDY-MASTER/
├── 📁 auth/                    # Sistema de autenticación
│   ├── 🔐 login.html          # Página de inicio de sesión
│   ├── 📝 register.html       # Página de registro
│   ├── 🎨 auth.css            # Estilos de autenticación
│   └── ⚡ auth.js             # Lógica de autenticación
├── 📁 main/                   # Página principal y recursos base
│   ├── 🏠 index.html          # Landing page principal
│   ├── 🎨 estilo.css          # Estilos principales
│   ├── ⚡ script.js           # Funcionalidades base
│   └── 📁 image/              # Recursos visuales
│       ├── heroImage.png      # Imagen principal
│       └── ...                # Otras imágenes
├── 📁 users/                  # Dashboards de usuarios
│   ├── 👤 trainee.html        # Panel de usuario Trainee
│   ├── 👤 trainee.js          # Lógica específica Trainee
│   ├── 👨‍🏫 trainer.html       # Panel de usuario Trainer
│   ├── 👨‍🏫 trainer.js         # Lógica específica Trainer
│   ├── ⚙️ admin.html          # Panel de administrador
│   ├── ⚙️ admin.js            # Lógica específica Admin
│   ├── 🎨 users.css           # Estilos comunes de usuarios
│   └── ⚡ users.js            # Funcionalidades comunes
├── 📁 docs/                   # Documentación del proyecto
│   └── 📄 TFI_Gpo_9_v2.docx  # Documento técnico completo
├── 📄 .gitignore             # Archivos ignorados por Git
└── 📄 README.md              # Este archivo

```
## 🌐 Páginas HTML Disponibles

### 1. 🏠 Página Principal (**main/index.html**)

Descripción: Landing page con presentación completa de FitBuddy.
Características:
* Diseño **responsive** y moderno con modo oscuro.
* Sección de servicios y beneficios.
* Testimonios de usuarios reales.
* Llamadas a acción para registro.
* Animaciones suaves con **AOS**.

---

### 2. 🔐 Autenticación (**auth/**)

#### Login (**login.html**)
* Inicio de sesión con **validación en tiempo real**.
* Selección de perfil (**Trainee/Trainer/Admin**).
* Recordatorio de credenciales.

#### Registro (**register.html**)
* Creación de cuenta con todos los campos necesarios.
* Validación de email y contraseña.
* Selección de rol de usuario.

---

### 3. 📊 Dashboards de Usuarios (**users/**)

#### 👤 Trainee Dashboard (**trainee.html**)
* Estadísticas personales: Entrenamientos completados, compañeros, rutinas activas.
* Entrenadores disponibles: Lista con filtros y estados.
* Mis rutinas activas: Progreso y seguimiento.
* Compañeros conectados: Comunidad de entrenamiento.
* Agenda de sesiones: Próximos entrenamientos programados.

#### 👨‍🏫 Trainer Dashboard (**trainer.html**)
* Gestión de clientes: Lista completa con estados.
* Agenda profesional: Sesiones del día y semana.
* Mis rutinas creadas: Biblioteca de entrenamientos.
* Métricas de negocio: Ingresos y crecimiento.
* Rating y reputación: Evaluación de clientes.

#### ⚙️ Admin Dashboard (**admin.html**)
* Gestión de usuarios: Control completo de la comunidad.
* Verificación de entrenadores: Aprobación de perfiles.
* Reportes y moderación: Gestión de contenido.
* Métricas de plataforma: Crecimiento y estadísticas.
* Herramientas administrativas: Backup, anuncios, mantenimiento.

## 📞 Flujo de Usuario

### 🎯 Para Nuevos Usuarios
El proceso para unirse a FitBuddy es el siguiente:
1.  **Landing Page** → Información y beneficios → Registro
2.  **Registro** → Selección de rol → Confirmación → Login
3.  **Dashboard** → Personalización → Exploración de funciones

---

### 👤 Flujo Trainee
Una vez en el sistema, el usuario Trainee puede realizar las siguientes acciones:
* **Buscar y Conectar**: Buscar Entrenadores → Filtrar → Conectar.
* **Monitorear**: Ver Rutinas Activas → Seguir Progreso.
* **Comunidad**: Encontrar Compañeros → Coordinar Entrenamientos.
* **Planificar**: Agenda → Programar Sesiones → Confirmar.

### 👨‍🏫 Flujo Trainer
Una vez en el sistema, el Entrenador puede:
* **Gestión de Clientes**: Gestionar Clientes → Comunicarse → Programar.
* **Creación de Contenido**: Crear Rutinas → Personalizar → Publicar.
* **Agenda**: Ver Agenda → Confirmar Sesiones → Actualizar.
* **Negocio**: Analizar Métricas → Optimizar Servicios.

### ⚙️ Flujo Admin
El Administrador gestiona la plataforma mediante:
* **Usuarios**: Moderar Usuarios → Verificar → Sancionar.
* **Reportes**: Revisar Reportes → Tomar Acción → Resolver.
* **Análisis**: Analizar Métricas → Generar Reportes.
* **Plataforma**: Gestionar Plataforma → Mantenimiento → Updates.

---

## 🔧 Personalización y Configuración

### Variables CSS Principales
La paleta de colores puede ser modificada ajustando estas variables:
```css
:root {
  --bg-color: #000;
  --second-bg-color: #111;
  --text-color: #fff;
  --main-color: #45ffca; /* Color principal (verde neón) */
  --gradient: linear-gradient(135deg, #45ffca 0%, #6effe0 100%);
}
```

## 🛠️ Tecnologías Utilizadas

### Frontend & Librerías
| Tecnología | Descripción |
| :--- | :--- |
| **HTML5** | Estructura semántica y moderna. |
| **CSS3** | Variables CSS, Grid, Flexbox, Animaciones. |
| **JavaScript ES6+** | Funcionalidades interactivas. |
| **Boxicons** | Librería de iconos vectoriales. |
| **AOS** | Animaciones al desplazar (**Animate On Scroll**). |

---

## Características Técnicas

* **Diseño Responsive**: *Mobile-first approach*.
* **Modo Oscuro**: Paleta oscura con acentos **verde neón** (`#45ffca`).
* **Validación en Tiempo Real**: Feedback inmediato en formularios.
* **LocalStorage**: Persistencia de datos del usuario.
* **Single Page Application (SPA)**: Navegación fluida sin recargas.

---

## 🚀 Instalación y Uso

### Prerrequisitos
* Navegador web moderno (**Chrome 90+**, Firefox 88+, Safari 14+).
* Servidor web local para desarrollo (opcional).

### Ejecución Local

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/EmmaLedesma/SITIO_APP_FITBUDDY-MASTER.git
    ```

2.  **Abre el proyecto y ejecuta un servidor local (opcional):**

    ```bash
    # Opción 1: Servidor local con Python
    python -m http.server 8000
    ```
    ```bash
    # Opción 2: Servidor local con Node.js
    npx http-server
    ```

3.  **Accede a la aplicación:**
    * Si usas un servidor, navega a: `http://localhost:8000/main/index.html`
    * O abre directamente: `main/index.html` en tu navegador.

### Flujo de Prueba
* Explora la **landing page** principal.
* Regístrate en `auth/register.html`.
* Inicia sesión en `auth/login.html`.
* Accede a tu **dashboard** según tu rol en `users/`.

## 🐛 Solución de Problemas

### Problemas Comunes
| Problema | Solución Recomendada |
| :--- | :--- |
| **Las imágenes no se cargan** | Verifica que la carpeta `main/image/` contenga todos los archivos y revisa las rutas en los archivos HTML. |
| **Los estilos no se aplican** | Confirma que los archivos CSS estén en las ubicaciones correctas y verifica las rutas relativas en los `<link>`. |
| **JavaScript no funciona** | Abre la consola del navegador (**F12**) para ver errores y verifica que todos los archivos JS estén cargados. |

### Navegadores Soportados
* ✅ Chrome 90+
* ✅ Firefox 88+
* ✅ Safari 14+
* ✅ Edge 90+

---

## 📈 Próximas Características

### 🚀 En Desarrollo
* Integración con APIs.
* Sistema de notificaciones *push*.
* Chat en tiempo real con WebSockets.

### 📅 Planificado
* Aplicación móvil nativa con **React Native o.NET**.
* Sistema de pagos integrado.
* Video llamadas para sesiones virtuales.
* *Marketplace* de entrenadores *premium*.

### 💡 Futuras Mejoras
* Gamificación con logros y recompensas.
* Integración con redes sociales.
* Modo entrenamiento *offline*.
* Planificación nutricional integrada.

---

## 🤝 Guía de Contribución

### Para Colaboradores
1.  **Fork** el proyecto.
2.  Crea una rama para tu *feature*:
    ```bash
    git checkout -b feature/nueva-funcionalidad
    ```
3.  Commit tus cambios:
    ```bash
    git commit -m 'feat: agregar nueva funcionalidad'
    ```
4.  Push a la rama:
    ```bash
    git push origin feature/nueva-funcionalidad
    ```
5.  Abre un **Pull Request**.

### Convenciones de Código
* **Commits**: Conventional commits (`feat`, `fix`, `docs`, `style`, `refactor`).
* **HTML**: Estructura semántica, atributos `alt` en imágenes.
* **CSS**: Variables CSS, **BEM methodology** para clases.
* **JS**: ES6+, funciones *arrow*, `async/await`.

---

## 📄 Licencia

Este proyecto está bajo la **Licencia MIT**. Ver el archivo `LICENSE` para más detalles.

## 📞 Soporte y Contacto

* **Repositorio**: [https://github.com/EmmaLedesma/SITIO_APP_FITBUDDY-MASTER.git](https://github.com/EmmaLedesma/SITIO_APP_FITBUDDY-MASTER.git)
* **Documentación Técnica**: `docs/TFI_Gpo_9_v2.docx`

---

<div align="center">
  <h3>¡Únete a la revolución del fitness social con FitBuddy! 🚀💪</h3>
  <p>Conectando pasión, tecnología y entrenamiento</p>
</div>

---

**🔄 Historial de Versiones**
* **v1.0.0 (Actual)**: Landing page completa, sistema de autenticación funcional, Dashboards multi-rol, diseño responsive y persistencia con `localStorage`.

¿Listo para comenzar? Abre `main/index.html` y descubre FitBuddy 🎉

## 👥 Equipo de Desarrollo

| Nombre | Rol Principal | Responsabilidades |
| :--- | :--- | :--- |
| **Fernandez, Mauricio** | Backend Developer | Lógica de servidor, API, Base de datos |
| **Rojas, Maximiliano** | UX/UI | Interfaces móviles, Experiencia de usuario |
| **Ledesma, Emmanuel** | Full Stack Developer | Integración, Funcionalidades *core*, Arquitectura |

---

<div align="center">
  <h3>¡Únete a la revolución del fitness social con FitBuddy! 🚀💪</h3>
  <p>Conectando pasión, tecnología y entrenamiento</p>
</div>

---

**🔄 Historial de Versiones**

#### v1.0.0 (Actual)
* ✅ Landing page completa.
* ✅ Sistema de autenticación funcional.
* ✅ Dashboards multi-rol.
* ✅ Diseño responsive.
* ✅ Persistencia con `localStorage`.

<br>
¿Listo para comenzar? Abre `main/index.html` y descubre FitBuddy 🎉
# Guía de Contribución

Gracias por tu interés en contribuir al repositorio **CUGDL Ciberseguridad**. Este documento te guiará paso a paso en el proceso de contribución.

---

## Tabla de Contenidos

- [Antes de Empezar](#antes-de-empezar)
- [Proceso de Contribución](#proceso-de-contribución)
- [Reglas de Estilo](#reglas-de-estilo)
- [Tipos de Contribuciones](#tipos-de-contribuciones)
- [Revisión de Pull Requests](#revisión-de-pull-requests)
- [Preguntas Frecuentes](#preguntas-frecuentes)

---

## Antes de Empezar

### Requisitos Previos

1. **Lee el [README.md](README.md)** para entender el propósito del repositorio.
2. **Familiarízate con [RULES.md](RULES.md)** para conocer qué contenido es aceptable.
3. **Revisa el [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)** para entender nuestras expectativas de comportamiento.
4. **Verifica que tu contribución sea original o que cuentes con los derechos** para compartirla.

### ¿Qué Necesitas?

- Una cuenta de GitHub.
- Conocimientos básicos de Git y GitHub.
- Editor de texto para Markdown (VS Code, Typora, Obsidian, etc.).
- Opcional: Conocimientos de la temática que vas a documentar.

---

## Proceso de Contribución

### Paso 1: Hacer Fork del Repositorio

1. Ve al repositorio principal en GitHub.
2. Haz clic en el botón **"Fork"** en la esquina superior derecha.
3. Esto creará una copia del repositorio en tu cuenta de GitHub.

### Paso 2: Clonar el Repositorio

Clona tu fork a tu máquina local:

```bash
git clone https://github.com/TU_USUARIO/cugdl-ciberseguridad.git
cd cugdl-ciberseguridad
```

### Paso 3: Configurar el Remoto Upstream (Opcional pero Recomendado)

Esto te permitirá mantener tu fork actualizado con el repositorio original:

```bash
git remote add upstream https://github.com/USUARIO_ORIGINAL/cugdl-ciberseguridad.git
git fetch upstream
```

### Paso 4: Crear una Nueva Rama

**IMPORTANTE**: Nunca trabajes directamente en la rama `main`. Crea una rama nueva para tus cambios:

```bash
git checkout -b nombre-de-tu-rama
```

**Convención de nombres de ramas:**

- `feature/nombre-funcionalidad` - Para nuevas funcionalidades o contenido.
- `fix/descripcion-correccion` - Para correcciones.
- `docs/descripcion-documentacion` - Para mejoras en documentación.

Ejemplos:

- `feature/apuntes-metasploit`
- `fix/correccion-typos-readme`
- `docs/guia-instalacion-kali`

### Paso 5: Realizar tus Cambios

1. Navega a la carpeta correspondiente según tu contribución.
2. Crea o modifica los archivos necesarios.
3. Asegúrate de seguir las [Reglas de Estilo](#reglas-de-estilo).

### Paso 6: Verificar tus Cambios

Antes de hacer commit, verifica:

- Los archivos Markdown se renderizan correctamente.
- No has incluido información sensible (IPs reales, credenciales, datos personales).
- Tu contenido cumple con las [RULES.md](RULES.md).
- Los enlaces funcionan correctamente.

### Paso 7: Hacer Commit de tus Cambios

Agrega los archivos modificados:

```bash
git add .
```

Crea un commit con un mensaje descriptivo **en español**:

```bash
git commit -m "Agregar apuntes sobre Metasploit Framework"
```

**Convenciones para mensajes de commit:**

- Usa verbos en infinitivo: "Agregar", "Modificar", "Corregir", "Eliminar".
- Sé específico y conciso.
- NO uses mayúsculas innecesarias ni signos de exclamación.
- NO uses emojis.

**Ejemplos de buenos mensajes:**

- `Agregar guía de instalación de Wireshark en Windows`
- `Corregir errores tipográficos en README principal`
- `Modificar plantilla de writeup CTF`
- `Eliminar información desactualizada de certificaciones`

**Ejemplos de malos mensajes:**

- `Update` (muy genérico)
- `Cambios varios` (no es descriptivo)
- `AGREGANDO COSAS NUEVAS!!!` (formato incorrecto)

### Paso 8: Subir tus Cambios a GitHub

```bash
git push origin nombre-de-tu-rama
```

### Paso 9: Crear un Pull Request (PR)

1. Ve a tu fork en GitHub.
2. Verás un mensaje sugiriendo crear un Pull Request. Haz clic en **"Compare & pull request"**.
3. Completa el formulario del PR:
   - **Título**: Breve descripción del cambio (en español).
   - **Descripción**: Detalla qué cambios realizaste y por qué.
   - Referencia cualquier issue relacionado (si aplica).
4. Revisa los archivos modificados para confirmar que todo está correcto.
5. Haz clic en **"Create pull request"**.

### Paso 10: Revisión y Aprobación

- Los mantenedores revisarán tu PR.
- Pueden solicitarte cambios o aclaraciones.
- Realiza los ajustes necesarios en tu rama y haz push (el PR se actualizará automáticamente).
- Una vez aprobado, tu PR será fusionado al repositorio principal.

---

## Reglas de Estilo

### Formato de Archivos

- **Todos los archivos deben estar en Markdown** (`.md`).
- Usa codificación **UTF-8**.
- Extensión de línea máxima recomendada: 120 caracteres (no obligatorio, pero ayuda a la legibilidad).

### Estructura de Documentos

Cada documento debe incluir:

1. **Título principal** (H1): `# Título del Documento`
2. **Descripción breve**: Qué cubre el documento.
3. **Tabla de contenidos** (opcional para documentos largos).
4. **Secciones claras** con encabezados jerárquicos (H2, H3, H4).
5. **Referencias y fuentes** al final del documento.

### Uso de Plantillas

Cuando sea posible, utiliza las plantillas disponibles en la carpeta `/plantillas/`:

- `plantilla-apuntes.md` - Para apuntes teóricos.
- `plantilla-laboratorio.md` - Para configuración de laboratorios.
- `plantilla-writeup.md` - Para writeups de CTFs.

### Imágenes y Recursos

- Coloca las imágenes en una subcarpeta `img/` dentro de la carpeta correspondiente.
- Usa nombres descriptivos para las imágenes: `configuracion-firewall.png`, no `imagen1.png`.
- Formato preferido: PNG o JPG (optimizadas, sin exceder 1MB por imagen).
- **NO subas PDFs pesados**. Si es necesario, enlaza a recursos externos o Google Drive.

### Enlaces

- Verifica que todos los enlaces funcionen antes de enviar el PR.
- Prefiere enlaces permanentes y oficiales.
- Para referencias internas, usa rutas relativas: `[Reglas](RULES.md)`.

### Código y Comandos

- Usa bloques de código con sintaxis resaltada:

```bash
sudo apt update && sudo apt install wireshark
```

- Indica el lenguaje o shell correspondiente: `bash`, `python`, `powershell`, etc.

### Citas y Atribuciones

- **Siempre cita tus fuentes** si el contenido no es original.
- Usa el formato:

```markdown
> Fuente: [Nombre de la Fuente](URL)
```

---

## Tipos de Contribuciones

### 1. Apuntes y Resúmenes

- Agregar apuntes sobre conceptos teóricos de ciberseguridad.
- Ubicación: `/fundamentos/`, `/blue-team/`, `/red-team-labs/`.

### 2. Laboratorios

- Guías de configuración de entornos virtuales.
- Configuraciones de herramientas en entornos controlados.
- Ubicación: `/laboratorios/`.

### 3. Writeups de CTFs

- Soluciones detalladas de desafíos de CTFs públicos.
- Ubicación: `/laboratorios/ctf/writeups/`.

### 4. Guías de Herramientas

- Tutoriales de uso de herramientas de seguridad.
- Ubicación: `/herramientas/`.

### 5. Recursos Oficiales

- Enlaces a certificaciones, documentación técnica, cursos, libros.
- Ubicación: `/recursos-oficiales/`.

### 6. Correcciones y Mejoras

- Corrección de errores tipográficos.
- Actualización de información desactualizada.
- Mejora de la estructura o formato.

---

## Revisión de Pull Requests

### ¿Qué Revisamos?

Los mantenedores revisarán:

1. **Cumplimiento de las reglas**: El contenido debe cumplir con [RULES.md](RULES.md).
2. **Calidad del contenido**: Información precisa, clara y bien estructurada.
3. **Formato y estilo**: Cumplimiento de las reglas de estilo.
4. **Seguridad**: No debe contener información sensible ni peligrosa.
5. **Ética y legalidad**: El contenido debe ser ético y legal.

### Tiempo de Revisión

- Trataremos de revisar los PRs en un plazo de 3 a 7 días.
- Si tu PR requiere cambios, tendrás 14 días para realizarlos antes de que sea cerrado.

### Comunicación

- Sé respetuoso en los comentarios del PR.
- Responde a las solicitudes de cambios de manera constructiva.
- Si tienes dudas, no dudes en preguntar.

---

## Preguntas Frecuentes

### ¿Puedo contribuir si no soy estudiante de la CUGDL?

Sí, el repositorio está abierto a contribuciones de cualquier persona que comparta conocimientos de forma ética y responsable.

### ¿Puedo subir contenido en otro idioma?

Por el momento, todo el contenido debe estar en **español**, ya que está dirigido principalmente a estudiantes hispanohablantes.

### ¿Puedo compartir exploits o vulnerabilidades?

Solo si son:

- De dominio público.
- Con fines educativos.
- Aplicables únicamente a entornos de laboratorio.
- **NO aplicables a sistemas reales sin autorización**.

### ¿Qué hago si encuentro un error en el repositorio?

Puedes:

1. Crear un issue describiendo el problema.
2. Enviar un PR con la corrección.

### ¿Cómo mantengo mi fork actualizado?

```bash
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

---

## Contacto

Si tienes dudas o necesitas ayuda, puedes:

- Abrir un issue en el repositorio.
- Contactar a los mantenedores a través de las discusiones del repositorio.

---

Gracias por contribuir al proyecto **CUGDL Ciberseguridad**. Tu esfuerzo ayuda a construir una comunidad educativa más fuerte.

# Política de Seguridad

Este documento establece las políticas y procedimientos para el reporte responsable de vulnerabilidades y el manejo de información sensible relacionada con el repositorio **CUGDL Ciberseguridad**.

---

## Tabla de Contenidos

- [Alcance de Esta Política](#alcance-de-esta-política)
- [Qué NO es Este Repositorio](#qué-no-es-este-repositorio)
- [Divulgación Responsable de Vulnerabilidades](#divulgación-responsable-de-vulnerabilidades)
- [Cómo Reportar Vulnerabilidades](#cómo-reportar-vulnerabilidades)
- [Política de No Publicación de 0-Days](#política-de-no-publicación-de-0-days)
- [Reportes sobre Sistemas Universitarios](#reportes-sobre-sistemas-universitarios)
- [Seguridad del Repositorio](#seguridad-del-repositorio)
- [Compromiso con la Comunidad](#compromiso-con-la-comunidad)

---

## Alcance de Esta Política

Esta política cubre:

1. **Seguridad del propio repositorio** (código, estructura, contenido).
2. **Contenido sensible** que pueda haber sido publicado inadvertidamente.
3. **Divulgación responsable** de vulnerabilidades relacionadas con el material educativo.
4. **Reportes de uso indebido** del contenido del repositorio.

---

## Qué NO es Este Repositorio

### Este NO es un Canal para Reportar Vulnerabilidades Reales

Este repositorio **NO debe ser utilizado** para:

- Reportar vulnerabilidades en sistemas reales de producción.
- Publicar exploits 0-day o vulnerabilidades no divulgadas.
- Compartir información sobre vulnerabilidades en sistemas de la Universidad de Guadalajara u otras instituciones.
- Divulgar detalles técnicos de vulnerabilidades activas en sistemas ampliamente utilizados.

### Uso Correcto del Repositorio

Este repositorio es **exclusivamente educativo** y debe contener:

- Contenido educativo sobre vulnerabilidades ya conocidas y parcheadas.
- Análisis de vulnerabilidades históricas con fines pedagógicos.
- Metodologías de detección y mitigación de vulnerabilidades.
- Prácticas de laboratorio en entornos controlados.

---

## Divulgación Responsable de Vulnerabilidades

### Principios de Divulgación Responsable

Si descubres una vulnerabilidad real en cualquier sistema, sigue estos principios:

1. **NO la publiques inmediatamente**.
2. **Contacta al propietario del sistema** de forma privada.
3. **Proporciona detalles técnicos suficientes** para que puedan reproducir y corregir el problema.
4. **Da tiempo razonable** para que se implemente un parche (generalmente 90 días).
5. **Coordina la divulgación pública** con el propietario del sistema.
6. Solo después de que la vulnerabilidad esté parcheada, puedes considerar publicar un análisis educativo.

### Recursos sobre Divulgación Responsable

- **CERT/CC**: [https://vuls.cert.org/confluence/display/Wiki/Vulnerability+Disclosure+Policy](https://vuls.cert.org/confluence/display/Wiki/Vulnerability+Disclosure+Policy)
- **OWASP**: [https://owasp.org/www-community/Vulnerability_Disclosure_Cheat_Sheet](https://owasp.org/www-community/Vulnerability_Disclosure_Cheat_Sheet)
- **ISO/IEC 29147**: Estándar internacional para divulgación de vulnerabilidades.

---

## Cómo Reportar Vulnerabilidades

### Vulnerabilidades en el Repositorio

Si encuentras una vulnerabilidad o problema de seguridad **en este repositorio** (no en sistemas externos), por favor:

#### Paso 1: Identifica el Problema

Determina si se trata de:

- Información sensible publicada inadvertidamente (credenciales, IPs, datos personales).
- Contenido que viola las políticas de seguridad.
- Problemas en la estructura o permisos del repositorio.
- Uso indebido del contenido por terceros.

#### Paso 2: Reporta de Forma Privada

**NO publiques el problema en issues públicos**. En su lugar:

1. **Contacta a los mantenedores directamente** a través de:

   - Correo electrónico (si está disponible).
   - Mensaje privado en GitHub.
   - Canales de comunicación privados del proyecto.

2. **Proporciona la siguiente información**:
   - Descripción detallada del problema.
   - Ubicación exacta (archivo, línea, enlace).
   - Impacto potencial del problema.
   - Sugerencias de corrección (opcional).

#### Paso 3: Espera Respuesta

- Los mantenedores revisarán el reporte en un plazo de **48 a 72 horas**.
- Se te confirmará la recepción del reporte.
- Se te informará sobre las acciones tomadas.

### Ejemplo de Reporte

```
Asunto: Reporte de Seguridad - Información Sensible en Archivo X

Descripción:
He encontrado una dirección IP real en el archivo /laboratorios/ejemplo.md línea 45.
Esto podría exponer información sensible sobre sistemas reales.

Ubicación: /laboratorios/ejemplo.md, línea 45
Impacto: Exposición de información de red interna

Sugerencia: Reemplazar con una IP del rango de documentación (192.0.2.1)
```

---

## Política de No Publicación de 0-Days

### Definición de 0-Day

Un **0-day** es una vulnerabilidad que:

- No ha sido divulgada públicamente.
- No tiene un parche disponible.
- Puede ser explotada activamente.

### Prohibición Estricta

**ESTÁ ESTRICTAMENTE PROHIBIDO** publicar en este repositorio:

- Exploits 0-day funcionales.
- Detalles técnicos de vulnerabilidades no parcheadas.
- Código de explotación para vulnerabilidades activas.
- Técnicas de evasión de sistemas de seguridad actuales sin mitigaciones conocidas.

### Consecuencias

La publicación de 0-days resultará en:

- **Eliminación inmediata** del contenido.
- **Bloqueo permanente** del usuario.
- **Reporte a las autoridades** si la gravedad lo amerita.
- Posible **responsabilidad legal** para el usuario que lo publique.

---

## Reportes sobre Sistemas Universitarios

### Sistemas de la Universidad de Guadalajara

Si descubres una vulnerabilidad en sistemas de la **Universidad de Guadalajara**:

1. **NO la publiques en este repositorio**.
2. **Repórtala a través de los canales oficiales de la universidad**:

   - Departamento de Tecnologías de Información (TI).
   - Oficina de Ciberseguridad (si existe).
   - Contacto oficial de seguridad de la universidad.

3. **Sigue el proceso interno** de la universidad para divulgación responsable.

### Información Prohibida sobre Infraestructura Universitaria

**NO publiques en este repositorio**:

- Rangos de IP de la red universitaria.
- Configuraciones internas de sistemas.
- Vulnerabilidades no parcheadas en sistemas de la universidad.
- Credenciales o accesos a sistemas universitarios.
- Topología de red interna.
- Cualquier información que pueda comprometer la seguridad de la universidad.

---

## Seguridad del Repositorio

### Prácticas de Seguridad para Colaboradores

Todos los colaboradores deben:

1. **Nunca publicar credenciales reales** (ni siquiera las propias).
2. **Anonimizar capturas de pantalla** que contengan información sensible.
3. **Usar datos ficticios** en ejemplos y demostraciones.
4. **Revisar cuidadosamente** antes de hacer commit de archivos.
5. **No subir archivos .env, claves privadas, tokens de API, etc.**

### Verificación de Contenido Sensible

Antes de publicar contenido, verifica que NO incluya:

- Contraseñas o credenciales.
- Claves privadas SSH, GPG, etc.
- Tokens de acceso o API keys.
- Direcciones IP reales de sistemas en producción.
- Información personal identificable (PII).
- Datos confidenciales de organizaciones.

### Uso del .gitignore

El archivo `.gitignore` del repositorio debe incluir:

```
# Archivos de entorno
.env
.env.local
.env.*.local

# Claves y credenciales
*.key
*.pem
*.cert
*.pfx
credentials.json
secrets.json

# Archivos de configuración sensibles
config.local.*
*-private.*
```

---

## Compromiso con la Comunidad

### Transparencia

Los mantenedores se comprometen a:

- Responder rápidamente a reportes de seguridad.
- Tomar acciones correctivas de forma oportuna.
- Comunicar los problemas resueltos a la comunidad (sin exponer detalles sensibles).
- Agradecer públicamente a los reportantes (si lo autorizan).

### Reconocimiento

Si reportas un problema de seguridad de forma responsable:

- Serás reconocido en el repositorio (si lo deseas).
- Tu contribución será valorada por la comunidad.
- Ayudarás a mantener un espacio seguro y educativo.

---

## Contacto de Seguridad

Para reportes de seguridad sensibles, contacta a:

- **Mantenedores del repositorio**: A través de mensajes privados en GitHub.
- **Canales oficiales del proyecto**: (Especificar si existen).

**Nota**: Este contacto es exclusivamente para problemas de seguridad relacionados con el repositorio. Para vulnerabilidades en sistemas externos, contacta directamente a los propietarios de esos sistemas.

---

## Recursos Adicionales

- **Guía de Divulgación Responsable**: [OWASP Vulnerability Disclosure](https://owasp.org/www-community/Vulnerability_Disclosure_Cheat_Sheet)
- **Reglas del Repositorio**: [RULES.md](RULES.md)
- **Código de Conducta**: [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

---

## Actualizaciones de Esta Política

Esta política puede ser actualizada para reflejar:

- Mejores prácticas emergentes en ciberseguridad.
- Cambios en la legislación aplicable.
- Feedback de la comunidad.
- Incidentes que requieran aclaraciones.

Los cambios significativos serán comunicados a la comunidad.

---

**Última actualización**: Diciembre 2025

**Recuerda**: La ciberseguridad es una responsabilidad compartida. Actúa siempre de forma ética, legal y responsable.

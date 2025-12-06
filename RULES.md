# Reglas del Repositorio CUGDL Ciberseguridad

Este documento establece las reglas específicas que todos los colaboradores deben seguir para mantener el repositorio como un espacio educativo, ético y legal.

---

## Tabla de Contenidos

- [Principios Fundamentales](#principios-fundamentales)
- [Contenido Permitido](#contenido-permitido)
- [Contenido NO Permitido](#contenido-no-permitido)
- [Lineamientos Éticos y Legales](#lineamientos-éticos-y-legales)
- [Reglas para Material de Red Team](#reglas-para-material-de-red-team)
- [Política de Privacidad y Anonimato](#política-de-privacidad-y-anonimato)
- [Uso de Herramientas de Seguridad](#uso-de-herramientas-de-seguridad)
- [Consecuencias del Incumplimiento](#consecuencias-del-incumplimiento)
- [Proceso de Apelación](#proceso-de-apelación)

---

## Principios Fundamentales

Este repositorio se rige por tres principios fundamentales:

1. **Educación**: Todo el contenido debe tener un propósito educativo claro.
2. **Ética**: Promover prácticas éticas y responsables en ciberseguridad.
3. **Legalidad**: Cumplir estrictamente con las leyes locales, nacionales e internacionales.

**Importante**: La violación de cualquiera de estos principios resultará en el rechazo inmediato del contenido y posibles acciones adicionales.

---

## Contenido Permitido

### Material Teórico

- Apuntes y resúmenes de conceptos de ciberseguridad.
- Explicaciones de protocolos, arquitecturas y sistemas.
- Fundamentos de criptografía, redes, sistemas operativos y programación.
- Conceptos de defensa y detección de amenazas.

### Laboratorios y Entornos Controlados

- Configuración de máquinas virtuales para práctica (VirtualBox, VMware, Docker).
- Instalación y configuración de herramientas de seguridad.
- Creación de entornos de red aislados para pruebas.
- Laboratorios de hardening y fortalecimiento de sistemas.

### Writeups Educativos

- Soluciones de CTFs públicos y plataformas educativas (HackTheBox, TryHackMe, PicoCTF, etc.).
- Análisis de desafíos de seguridad con fines educativos.
- Metodologías de resolución de problemas de seguridad.

### Guías de Herramientas

- Tutoriales de uso de herramientas de seguridad en entornos controlados.
- Mejores prácticas para el uso responsable de herramientas.
- Comparativas y análisis de herramientas de seguridad.

### Recursos Académicos

- Enlaces a certificaciones reconocidas (CEH, OSCP, Security+, etc.).
- Documentación técnica oficial.
- Libros, cursos y recursos educativos gratuitos o de acceso público.
- Normativas y estándares de seguridad (ISO 27001, NIST, OWASP, etc.).

### Buenas Prácticas

- Guías de hardening de sistemas operativos.
- Configuraciones seguras de servicios y aplicaciones.
- Políticas de seguridad y gestión de riesgos.
- Procedimientos de respuesta a incidentes.

---

## Contenido NO Permitido

### Material Ilegal o Malicioso

- Malware funcional, virus, troyanos, ransomware o cualquier código malicioso ejecutable.
- Exploits 0-day o vulnerabilidades no divulgadas públicamente.
- Herramientas diseñadas exclusivamente para actividades ilegales.
- Técnicas para evadir la ley o sistemas de seguridad en entornos reales.

### Información Sensible

- Datos personales de terceros (nombres reales, direcciones, teléfonos, correos electrónicos).
- Credenciales reales (usuarios, contraseñas, tokens, claves API).
- Direcciones IP de sistemas reales o en producción.
- Información corporativa confidencial o propietaria.
- Resultados de pruebas de penetración en sistemas reales sin autorización explícita y por escrito.

### Contenido No Ético

- Guías detalladas para atacar sistemas reales sin autorización.
- Promoción de actividades ilegales o criminales.
- Contenido que incite al fraude, robo de identidad o extorsión.
- Técnicas de ingeniería social para fines maliciosos.

### Contenido Ofensivo

- Material discriminatorio, racista, sexista u ofensivo.
- Acoso, amenazas o intimidación hacia personas o grupos.
- Contenido sexual explícito o inapropiado.
- Lenguaje vulgar u ofensivo innecesario.

### Material Desorganizado o de Baja Calidad

- Contenido sin formato, desestructurado o ilegible.
- Información incorrecta, desactualizada o sin verificar.
- Archivos binarios pesados sin justificación (ISO, OVA, etc.).
- Contenido duplicado o redundante.

---

## Lineamientos Éticos y Legales

### Uso Exclusivo en Entornos Controlados

- **Todo el material ofensivo debe ser aplicado únicamente en entornos controlados**:
  - Máquinas virtuales propias.
  - Laboratorios personales aislados.
  - Plataformas educativas legales (HackTheBox, TryHackMe, etc.).
  - Sistemas con autorización explícita y por escrito.

### Autorización Obligatoria

- **NUNCA se debe realizar ninguna prueba de seguridad en sistemas reales sin autorización previa y por escrito**.
- La autorización debe provenir del propietario legal del sistema.
- Conservar siempre evidencia de la autorización obtenida.

### Divulgación Responsable

- Si descubres una vulnerabilidad real, **NO la publiques en este repositorio**.
- Sigue un proceso de divulgación responsable:
  1. Reportar la vulnerabilidad al propietario del sistema de forma privada.
  2. Dar tiempo razonable para que se corrija (generalmente 90 días).
  3. Publicar la información solo cuando sea seguro y ético hacerlo.

### Cumplimiento Legal

- Cumplir con las leyes de México y las leyes internacionales aplicables.
- No utilizar el conocimiento adquirido para actividades ilegales.
- Respetar los derechos de autor y la propiedad intelectual.

---

## Reglas para Material de Red Team

El contenido relacionado con técnicas ofensivas (Red Team, Pentesting, Hacking Ético) debe cumplir con los siguientes requisitos:

### 1. Contexto Educativo Claro

- Cada documento debe comenzar con un **aviso de uso exclusivo educativo**.
- Explicar claramente el propósito pedagógico del contenido.

### 2. Entorno de Laboratorio

- Todas las técnicas deben ser demostradas **únicamente en entornos de laboratorio controlados**.
- Especificar claramente qué tipo de entorno se utilizó (máquina virtual, plataforma CTF, etc.).
- **No incluir instrucciones para atacar sistemas reales**.

### 3. Énfasis en la Legalidad

- Recordar constantemente la importancia de obtener autorización.
- Advertir sobre las consecuencias legales del uso indebido.

### 4. Enfoque Defensivo

- Siempre que sea posible, incluir **medidas de defensa y mitigación**.
- Explicar cómo detectar y prevenir los ataques descritos.
- Vincular el material ofensivo con conceptos de Blue Team.

### 5. Prohibiciones Específicas

- **NO publicar exploits funcionales contra vulnerabilidades actuales en sistemas ampliamente utilizados**.
- **NO incluir guías paso a paso para comprometer sistemas reales**.
- **NO compartir técnicas de evasión de sistemas de detección sin contexto defensivo**.

### Ejemplo de Aviso Requerido

Todos los documentos de Red Team deben incluir un aviso similar a este al inicio:

```markdown
---
**ADVERTENCIA DE USO EDUCATIVO**

Este contenido es exclusivamente para fines educativos y de investigación en ciberseguridad. 
Todas las técnicas descritas deben ser practicadas únicamente en entornos controlados y con 
autorización explícita. El uso no autorizado de estas técnicas en sistemas reales es ILEGAL 
y puede resultar en consecuencias legales graves.

El autor y los colaboradores de este repositorio no se responsabilizan por el uso indebido 
de esta información.
---
```

---

## Política de Privacidad y Anonimato

### Protección de Datos Personales

- **No compartir información personal** de terceros sin su consentimiento explícito.
- Si es necesario mencionar personas, usar pseudónimos o iniciales.
- Anonimizar capturas de pantalla que contengan información sensible.

### Uso de Datos en Ejemplos

Al crear ejemplos o demostraciones:

- Usar datos ficticios claramente identificables como tal.
- Direcciones IP: Usar rangos reservados para documentación (192.0.2.0/24, 198.51.100.0/24, 203.0.113.0/24).
- Dominios: Usar dominios de ejemplo (example.com, example.org).
- Nombres: Usar nombres claramente ficticios.
- Credenciales: Nunca usar credenciales reales, ni siquiera las tuyas propias.

### Protección de Infraestructura Universitaria

- **NO publicar información sensible sobre la infraestructura de la Universidad de Guadalajara**.
- **NO compartir configuraciones internas, IPs, rangos de red o vulnerabilidades de sistemas universitarios**.
- Si detectas una vulnerabilidad en sistemas de la universidad, repórtala a través de canales oficiales, **NO en este repositorio**.

---

## Uso de Herramientas de Seguridad

### Herramientas Legítimas

El repositorio puede incluir guías de herramientas legítimas de seguridad, como:

- Wireshark, tcpdump (análisis de tráfico).
- Nmap, Masscan (escaneo de redes en entornos controlados).
- Metasploit, Burp Suite (pentesting en laboratorios).
- Snort, Suricata (detección de intrusiones).
- SIEM, herramientas de análisis forense.

### Responsabilidad en el Uso

- Cada guía debe incluir **advertencias sobre el uso responsable**.
- Explicar las implicaciones legales del mal uso.
- Enfatizar que estas herramientas solo deben usarse con autorización.

### Prohibición de Herramientas Maliciosas

- **NO compartir herramientas diseñadas exclusivamente para actividades maliciosas**.
- **NO incluir tutoriales de configuración de botnets, malware o herramientas de ataque DDoS**.

---

## Consecuencias del Incumplimiento

Las violaciones de estas reglas tendrán consecuencias que pueden incluir:

### Primera Infracción (Menor)

- **Advertencia formal** al colaborador.
- **Solicitud de corrección** del contenido problemático.
- Si se corrige adecuadamente, el contenido puede ser aceptado.

### Infracciones Repetidas o Graves

- **Rechazo inmediato del Pull Request**.
- **Restricción temporal o permanente** de contribuciones futuras.
- **Bloqueo del usuario** en el repositorio.
- En casos extremos (contenido ilegal), **reporte a las autoridades correspondientes**.

### Criterios de Gravedad

**Infracciones Menores**:

- Errores de formato.
- Información desactualizada sin intención maliciosa.
- Falta de citas o referencias.

**Infracciones Graves**:

- Publicación de información sensible.
- Contenido ilegal o malicioso.
- Promoción de actividades ilegales.
- Violaciones reiteradas tras advertencias.

---

## Proceso de Apelación

Si consideras que tu contenido fue rechazado injustamente:

1. **Contacta a los mantenedores** explicando tu caso de forma respetuosa.
2. **Proporciona contexto adicional** que pueda aclarar la situación.
3. Los mantenedores revisarán el caso y emitirán una decisión final.
4. La decisión de los mantenedores es **definitiva**.

---

## Actualización de Reglas

Estas reglas pueden ser actualizadas periódicamente para reflejar:

- Cambios en la legislación.
- Nuevas mejores prácticas de la comunidad.
- Feedback de colaboradores.
- Incidentes que requieran aclaraciones.

Los colaboradores serán notificados de cambios significativos en las reglas.

---

## Recursos Adicionales

- **Código de Conducta**: [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- **Guía de Contribución**: [CONTRIBUTING.md](CONTRIBUTING.md)
- **Política de Seguridad**: [SECURITY.md](SECURITY.md)

---

## Compromiso Ético

Al contribuir a este repositorio, declaras que:

- Has leído y comprendido estas reglas.
- Te comprometes a cumplirlas en todas tus contribuciones.
- Entiendes las implicaciones legales y éticas de la ciberseguridad.
- Utilizarás el conocimiento adquirido de forma responsable y legal.

---

**Última actualización**: Diciembre 2025

**Nota Final**: Este repositorio tiene como único objetivo la educación en ciberseguridad. Cualquier uso indebido del contenido aquí compartido es responsabilidad exclusiva del usuario que lo realice. Los colaboradores y mantenedores no se hacen responsables del mal uso de la información.

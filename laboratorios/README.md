# Laboratorios

Esta carpeta contiene guías para configurar entornos de práctica, writeups de CTFs y recursos para laboratorios de ciberseguridad.

---

## Contenido

### Virtualización
Guías para configurar entornos virtualizados de práctica.

**Subcarpetas:**
- **VirtualBox**: Configuración de máquinas virtuales con VirtualBox
- **VMware**: Configuración de máquinas virtuales con VMware
- **Docker**: Contenedores para laboratorios de seguridad

**Temas incluidos:**
- Instalación y configuración de hipervisores
- Creación de redes virtuales aisladas
- Configuración de máquinas virtuales para seguridad
- Snapshots y gestión de entornos
- Distribuciones de seguridad (Kali Linux, Parrot OS, etc.)

### CTF (Capture The Flag)
Recursos relacionados con competencias CTF.

**Subcarpetas:**
- **writeups**: Soluciones detalladas de CTFs públicos
- **desafios**: Desafíos de práctica creados por la comunidad

**Plataformas cubiertas:**
- HackTheBox
- TryHackMe
- PicoCTF
- CTFtime
- OverTheWire

### Entornos de Práctica
Configuraciones de laboratorios específicos para diferentes escenarios.

**Temas incluidos:**
- Laboratorio de análisis de malware
- Laboratorio de análisis forense
- Laboratorio de red team
- Laboratorio de blue team
- Entornos vulnerable por diseño (DVWA, WebGoat, etc.)

---

## Advertencia de Seguridad

Los laboratorios de ciberseguridad deben:
- Estar completamente aislados de redes de producción
- Ejecutarse en entornos virtualizados
- No contener datos reales o sensibles
- Tener snapshots para restauración rápida
- Estar desconectados de Internet cuando sea necesario

---

## Cómo Contribuir

Si deseas agregar contenido a esta sección:

1. Para writeups de CTF:
   - Usa la plantilla `/plantillas/plantilla-writeup.md`
   - Asegúrate de que el CTF sea público y resuelto
   - Incluye capturas de pantalla relevantes (sin información sensible)

2. Para guías de laboratorio:
   - Usa la plantilla `/plantillas/plantilla-laboratorio.md`
   - Proporciona instrucciones paso a paso claras
   - Incluye requisitos del sistema
   - Añade troubleshooting común

3. Envía un Pull Request siguiendo la guía de [CONTRIBUTING.md](../CONTRIBUTING.md)

---

## Recursos de Laboratorios

### Máquinas Virtuales Vulnerables
- [VulnHub](https://www.vulnhub.com/)
- [HackTheBox Retired Machines](https://www.hackthebox.com/)
- [DVWA (Damn Vulnerable Web Application)](https://github.com/digininja/DVWA)
- [Metasploitable](https://sourceforge.net/projects/metasploitable/)
- [OWASP WebGoat](https://owasp.org/www-project-webgoat/)

### Distribuciones de Seguridad
- [Kali Linux](https://www.kali.org/)
- [Parrot Security OS](https://www.parrotsec.org/)
- [BlackArch Linux](https://blackarch.org/)
- [SANS SIFT Workstation](https://www.sans.org/tools/sift-workstation/)

---

**Última actualización**: Diciembre 2025

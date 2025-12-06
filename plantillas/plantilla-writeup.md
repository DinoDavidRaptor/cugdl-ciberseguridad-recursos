# [Nombre del Desafío] - Writeup

> **Plataforma**: [HackTheBox/TryHackMe/PicoCTF/etc.]  
> **Máquina**: [Nombre de la máquina]  
> **Dificultad**: [Easy/Medium/Hard/Insane]  
> **Sistema Operativo**: [Linux/Windows/Other]  
> **Fecha de resolución**: [Fecha]  
> **Autor del writeup**: [Tu nombre]

---

## ADVERTENCIA

Este writeup es para fines educativos únicamente. Solo documenta máquinas retiradas o desafíos públicos. Respetar las políticas de la plataforma sobre no publicar writeups de máquinas activas.

---

## Tabla de Contenidos

- [Información de la Máquina](#información-de-la-máquina)
- [Resumen Ejecutivo](#resumen-ejecutivo)
- [Reconocimiento](#reconocimiento)
- [Enumeración](#enumeración)
- [Explotación](#explotación)
- [Post-Explotación](#post-explotación)
- [Banderas](#banderas)
- [Lecciones Aprendidas](#lecciones-aprendidas)
- [Mitigaciones](#mitigaciones)
- [Herramientas Utilizadas](#herramientas-utilizadas)
- [Referencias](#referencias)

---

## Información de la Máquina

- **Nombre**: [Nombre de la máquina]
- **IP**: [IP de la máquina] (ejemplo: 10.10.10.XX)
- **Plataforma**: [HackTheBox/TryHackMe/etc.]
- **Nivel**: [Easy/Medium/Hard]
- **Sistema Operativo**: [Linux/Windows]
- **Puntos**: [X puntos]
- **Fecha de retirada**: [Fecha]

---

## Resumen Ejecutivo

Breve resumen de cómo se comprometió la máquina, vulnerabilidades encontradas y ruta de explotación.

**Vector de ataque inicial**: [Descripción breve]  
**Vulnerabilidades explotadas**:

- [Vulnerabilidad 1]
- [Vulnerabilidad 2]

**Ruta de escalada**: [Descripción breve de cómo se obtuvo root/administrator]

---

## Reconocimiento

### Escaneo de Puertos

```bash
# Escaneo rápido de puertos
nmap -p- --min-rate 10000 10.10.10.XX -oN nmap/allports

# Escaneo detallado de servicios
nmap -p [puertos encontrados] -sCV 10.10.10.XX -oN nmap/targeted
```

**Resultados del escaneo:**

```
PORT      STATE SERVICE     VERSION
[puerto]  open  [servicio]  [versión]
[puerto]  open  [servicio]  [versión]
```

**Análisis:**  
Descripción de los puertos abiertos y servicios interesantes encontrados.

---

## Enumeración

### Enumeración del Servicio 1: [Nombre del servicio]

Describe el proceso de enumeración del primer servicio.

```bash
# Comandos de enumeración
comando1
comando2
```

**Hallazgos:**

- [Hallazgo 1]
- [Hallazgo 2]

![Captura de pantalla de enumeración](img/enumeracion-1.png)

### Enumeración del Servicio 2: [Nombre del servicio]

Describe el proceso de enumeración del segundo servicio.

```bash
# Comandos de enumeración
```

**Hallazgos:**

- [Hallazgo 1]
- [Hallazgo 2]

---

## Explotación

### Acceso Inicial

Describe cómo se obtuvo el acceso inicial al sistema.

**Vulnerabilidad explotada**: [CVE o descripción]

```bash
# Comandos o exploit utilizado
exploit --parameter value
```

**Resultado:**  
Describe qué acceso se obtuvo (shell como qué usuario, etc.)

![Captura de pantalla de explotación](img/exploit-1.png)

### User Flag

```bash
# Comandos para obtener la flag de usuario
cat /home/user/user.txt
```

**Flag**: `[Redactada o mostrar si es un CTF público completado]`

---

## Post-Explotación

### Enumeración del Sistema

```bash
# Enumeración básica del sistema
id
whoami
uname -a
```

**Hallazgos importantes:**

- [Información relevante 1]
- [Información relevante 2]

### Escalada de Privilegios

Describe el proceso de escalada de privilegios.

**Vector de escalada**: [Descripción]

```bash
# Comandos utilizados para escalar privilegios
comando1
comando2
```

![Captura de pantalla de escalada](img/privesc-1.png)

### Root/Administrator Flag

```bash
# Comandos para obtener la flag de root
cat /root/root.txt
```

**Flag**: `[Redactada o mostrar si es un CTF público completado]`

---

## Banderas

| Usuario | Flag               |
| ------- | ------------------ |
| user    | [flag o redactada] |
| root    | [flag o redactada] |

---

## Lecciones Aprendidas

### Conceptos Clave

1. **[Concepto 1]**: Explicación de lo aprendido
2. **[Concepto 2]**: Explicación de lo aprendido
3. **[Concepto 3]**: Explicación de lo aprendido

### Técnicas Aplicadas

- [Técnica 1]: Descripción
- [Técnica 2]: Descripción
- [Técnica 3]: Descripción

### Puntos de Aprendizaje

- [Lección 1]
- [Lección 2]
- [Lección 3]

---

## Mitigaciones

Medidas de defensa que habrían prevenido o dificultado la explotación:

1. **[Mitigación 1]**: Descripción de la medida de seguridad
2. **[Mitigación 2]**: Descripción de la medida de seguridad
3. **[Mitigación 3]**: Descripción de la medida de seguridad

---

## Herramientas Utilizadas

- **Nmap**: Escaneo de puertos y servicios
- **[Herramienta 2]**: [Descripción de uso]
- **[Herramienta 3]**: [Descripción de uso]
- **[Herramienta 4]**: [Descripción de uso]

---

## Referencias

- [CVE relacionado](URL) (si aplica)
- [Documentación del exploit](URL)
- [Artículo relacionado](URL)
- [Documentación de herramienta](URL)

---

**Fecha de publicación**: [Fecha]  
**Autor**: [Tu nombre o usuario]

---

> **Nota**: Este writeup es parte del repositorio educativo CUGDL Ciberseguridad. Solo se publican writeups de máquinas retiradas o desafíos públicos completados. Para más información, consulta [RULES.md](../../RULES.md).

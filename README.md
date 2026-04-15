![Logo Institucional](https://github.com/JonatanBogadoUNLZ/PPS-Jonatan-Bogado/blob/9952aac097aca83a1aadfc26679fc7ec57369d82/LOGO%20AZUL%20HORIZONTAL%20-%20fondo%20transparente.png)

# UNLZ — Facultad de Ingeniería 
## Ingeniería Mecatrónica — README + estructura estándar

---

# Robot escalador para poda de árboles

**Tipo:** PF 
**Año:** [2026] — **Cuatrimestre:** 1C 

**Carrera:** Ingeniería Mecatrónica  
**Materia / Curso:** PROYECTO_FINAL_MECATRONICA 
**Docente / Cátedra:** Ezequiel Blanca, Cristian Lukaszewicz, Juan Szombach  
**Autor/es:** SANCHEZ, Matias — Legajo  · VENIERI, Gabriel— Legajo

---

## Introducción / Objetivo

La idea surge de la necesidad de poder hacer poda de árboles de forma segura, principalmente, ya que consideramos que puede ser un trabajo riesgoso ya que se desarrolla en la altura y no siempre con los elementos de seguridad mínimnos y necesarios

**Problema a resolver:**  
Este proyecto busca eliminar la necesidad de tener que usar una persona para trabajar en la altura, con todo lo que esto conlleva en terminos de seguridad.

**Objetivo general:**  
Ofrecer una solución automatizada y autónoma donde solo con colocar el robot en la base y ordenarle una acción mediante una interfaz gráfica, el mismo procederá a escalar el árbol y verificar si encuentra ramas que podar, si detecta alguna simplemente la cortara, si no encuentra ramas procederá a rotar alrededor del tronco hasta que verifique que en una vuelta completa no encontró ramas a una determinada altura, acto seguido seguirá escalando y repetirá el procedimiento anterior.

**Objetivos específicos (opcional):**
- Distinguir rama de otros elementos y de esta manera proceder a podar  de forma segura
- Escalado y poda autónoma
- Lograr que se le pueda indicar al robot una altura determinada como límite de escalada (poda parcial)
- Lograr que el robot pueda determinar el límite de escalado de forma automática en función del grosor del tronco conforme va subiendo.
- Sistema de seguridad que en caso de desprendimiento del robot del tronco que permita una parada súbita de la motosierra

---

## Índice
- [Brief](#brief)
- [Descripción técnica](#descripción-técnica)
- [Arquitectura del sistema](#arquitectura-del-sistema)
- [Instrucciones de uso](#instrucciones-de-uso)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Listado de componentes](#listado-de-componentes)
- [Esquemáticos / Planos](#esquemáticos--planos)
- [Fotos / Videos](#fotos--videos)
- [Estructura del repositorio](#estructura-del-repositorio)
- [Autor](#autor)
- [Licencia](#licencia)

---

## Brief

**One-liner (1 frase):**  
Podar arboles y acceder a zonas dificiles sin la necesidad de una persona que este trabajando en altura.

**Elevator pitch (30 segundos):**  
Este proyecto **[ROBOT PODADOR]** (tipo **[PF]**, **[2026] [1C]**) resuelve **[LA PODA]** mediante **[UN ROBOT AUTONOMO]**.  
Está orientado a **[PUBLICO EN GENERAL]** y permite **[REDUCIR EL RIESGO DEL TRABAJO EN ALTURAA]**.  
Se implementa con **[tecnologías clave]** y se valida mediante **[pruebas/mediciones/demo]**.

### Problema
- **Contexto:** [laboratorio / industria / hogar / aula / etc.]
- **Dolor principal:** [qué falla / qué es lento / qué es costoso / qué es riesgoso]
- **Impacto:** [tiempo, costo, errores, seguridad, calidad]

### Solución propuesta
- **Qué hace (features):**
  - [Funcionalidad 1]
  - [Funcionalidad 2]
  - [Funcionalidad 3]
- **Cómo lo hace (alto nivel):** [sensor → control → actuador → visualización]
- **Valor diferencial:** [por qué es mejor / distinto]

### Alcance
**Incluye:**
- [X]
- [Y]

**No incluye (por ahora):**
- [A]
- [B]

### Estado del proyecto
- **Madurez:** [idea / prototipo / MVP / validado]
- **Qué funciona hoy:** [lista corta]
- **Próximos pasos:** [lista corta]

### Demo rápida
- **Video / GIF:** [link o ruta en MULTIMEDIA]
- **Instrucciones express (2 minutos):**
  1) [Paso 1]
  2) [Paso 2]
  3) [Paso 3]

---

## Descripción técnica
[Explicación técnica del funcionamiento, decisiones de diseño y consideraciones.]

---

## Arquitectura del sistema

**Entradas (sensores / señales):**
- [Sensor 1]
- [Sensor 2]

**Procesamiento / Control:**
- [Microcontrolador / PC / algoritmo / lógica]

**Salidas (actuadores / señales):**
- [Actuador 1]
- [Actuador 2]

**Interfaz (si aplica):**
- [Pantalla / dashboard / app / web]

> (Opcional) Insertar diagrama:
![Diagrama de bloques](PLANOS/diagrama_bloques.png)

---

## Instrucciones de uso

### Requisitos previos
- [Software / IDE]
- [Drivers / librerías]
- [Hardware mínimo]

### Instalación / Puesta en marcha
1) [Clonar / descargar]
2) [Instalar dependencias]
3) [Cargar firmware / ejecutar]
4) [Validar funcionamiento]

### Uso
- **Modo normal:** [cómo se usa]
- **Calibración (si aplica):** [pasos]
- **Notas:** [cuidados, recomendaciones]

### Troubleshooting (opcional)
- **Problema:** [X] → **Solución:** [Y]
- **Problema:** [X] → **Solución:** [Y]

---

## Tecnologías utilizadas
- **Robótica / Control:** [Arduino / ESP32 / Raspberry / etc.]
- **Electrónica:** [sensores / drivers / etc.]
- **Programación:** [C/C++ / Python / etc.]
- **Plataformas / Tools:** [ROS / OpenCV / etc.]
- **IA (si aplica):** [modelo / técnica]

---

## Listado de componentes

| Componente | Cantidad | Modelo / Especificación | Función |
|---|---:|---|---|
| [Componente 1] | [1] | [Modelo] | [Función] |
| [Componente 2] | [2] | [Modelo] | [Función] |
| [Componente 3] | [1] | [Modelo] | [Función] |

---

## Esquemáticos / Planos
- [Plano/Esquemático 1] → `PLANOS/[archivo]`
- [Plano/Esquemático 2] → `PLANOS/[archivo]`

---

## Fotos / Videos
- Foto 1 → `MULTIMEDIA/[archivo]`
- Foto 2 → `MULTIMEDIA/[archivo]`
- Video demo → `MULTIMEDIA/[archivo]` o [link]

---

## Estructura del repositorio
- `CODIGO/` — Código fuente del proyecto.
- `MULTIMEDIA/` — Imágenes y videos.
- `PLANOS/` — Esquemáticos y diagramas.
- `DATASHEET/` — Hojas de datos y especificaciones.
- `INFORMES/` — Informes, Gantt, manuales, PDFs.

---

## Autor
**SANCHEZ, Matias Alejandro** — [Legajo], VENIERI, Mario Gabriel -   
Contacto (opcional): matyas-99@hotmail.com / gabry_getage@hotmail.com

---

## Licencia
[Definir según la cátedra: MIT / uso académico / etc.]

---

## About (descripción corta del repositorio)

Usar este texto (o similar) en el campo **About** de GitHub:

**PF — [Proyecto] — FI-UNLZ — 2026 1C — Sanchez, Veneri**


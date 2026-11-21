# Laboratorio No. 0X: [Título de la Práctica]

**Universidad Nacional de Colombia — Sede Bogotá**  
**Asignatura:** Robótica (2026-II)  
**Laboratorio:** LabSIR (Laboratorio de Sistemas Inteligentes y Robótica)  
**Equipo:** [Nombre del Equipo / Grupo] — [Integrante 1], [Integrante 2]

Para observar el resultado final del laboratorio y su implementación en el robot real, visite el siguiente enlace: [LabSIR UNAL](https://www.youtube.com/...)

---

## 1. Cuadro Comparativo

Los robots industriales **[Robot Principal del Laboratorio]**, fabricado por [Fabricante 1], y **[Robot de Comparación]**, fabricado por [Fabricante 2], son manipuladores [configuración mecánica] de [N] grados de libertad...

### Características técnicas generales

| Característica | [Robot Principal] | [Robot de Comparación] |
|---|---|---|
| Fabricante | | |
| Modelo | | |
| Tipo de robot | | |
| Configuración mecánica | | |
| Grados de libertad (GDL) | | |
| Carga útil máxima | | |
| Alcance horizontal máximo | | |
| Repetibilidad de posicionamiento | | |
| Peso aproximado del manipulador | | |
| Sistema de accionamiento | | |
| Controlador | | |
| Lenguaje de programación | | |
| Interfaz de programación | | |
| Simulador asociado | | |
| Aplicaciones típicas | | |

### Velocidades articulares máximas

| Articulación | [Robot Principal] | [Robot de Comparación] |
|---|---|---|
| Eje 1 | | |
| Eje 2 | | |
| Eje 3 | | |
| Eje 4 | | |
| Eje 5 | | |
| Eje 6 | | |

### Rangos de movimiento articular

| Articulación | [Robot Principal] | [Robot de Comparación] |
|---|---|---|
| Eje 1 | | |
| Eje 2 | | |
| Eje 3 | | |
| Eje 4 | | |
| Eje 5 | | |
| Eje 6 | | |

### Sistemas de control y programación

| Característica | [Robot Principal] | [Robot de Comparación] |
|---|---|---|
| Controlador | | |
| Lenguaje nativo | | |
| Movimiento articular | | |
| Movimiento lineal | | |
| Simulación y programación offline | | |

---

## 2. Configuraciones Home y Cinemática

### Configuración Home 1 – Posición inicial
Descripción de la postura de referencia ($0^\circ$ en todas las articulaciones o postura de reposo del fabricante) y su utilidad para calibración e inspección.

![Configuración Home 1](images/Home1.png)

### Configuración Home 2 – Posición de trabajo / transporte
Descripción de la segunda postura de referencia y su validación en simulación frente al manipulador físico.

![Configuración Home 2](images/Home2.png)

### Comparación de las posiciones articulares

| Articulación | Home 1 | Home 2 |
|:---:|:---:|:---:|
| $q_1$ | $0^\circ$ | |
| $q_2$ | $0^\circ$ | |
| $q_3$ | $0^\circ$ | |
| $q_4$ | $0^\circ$ | |
| $q_5$ | $0^\circ$ | |
| $q_6$ | $0^\circ$ | |

---

## 3. Procedimiento de Operación y Tipos de Movimiento

### 3.1. Preparación y encendido seguro
1. Verificar que el espacio de trabajo esté despejado.
2. Energizar el sistema de potencia y el controlador.
3. Verificar ausencia de alarmas y liberar paradas de emergencia.
4. Habilitar actuadores/servomotores en modo manual o remoto.

### 3.2. Sistemas de coordenadas y modos de movimiento
* **Movimiento Articular (Joint):** Control independiente de cada articulación ($q_1 \dots q_n$).
* **Movimiento Cartesiano / Tarea (Task):** Desplazamiento y orientación del TCP respecto a los ejes $X, Y, Z$.

---

## 4. Niveles de Velocidad y Parámetros de Control

| Nivel / Modo | Identificador | Descripción | Aplicación |
|---|:---:|---|---|
| **Bajo / Precisión** | | | Aproximación fina y calibración |
| **Medio** | | | Desplazamientos de prueba |
| **Alto** | | | Ejecución de trayectorias nominales |

---

## 5. Arquitectura de Software y Comunicación con el Robot

### 5.1. Descripción del entorno y control mediante código
Explicación de las librerías empleadas (Python, MATLAB, ROS, API del simulador), definición de marcos de referencia (`Frame`), herramienta (`TCP`) y generación de trayectorias.

### 5.2. Flujo de comunicación (Offline vs. Online)
Descripción del protocolo de enlace (USB/Serial, Ethernet TCP/IP, tópicos/servicios) entre el computador y el controlador físico.

![Diagrama de Comunicación](images/Diagrama_Comunicaciones.png)

---

## 6. Comparativa de Herramientas de Simulación y Control

| Característica | [Herramienta 1] | [Herramienta 2] |
|---|---|---|
| **Compatibilidad** | | |
| **Lenguajes / API** | | |
| **Ventajas** | | |
| **Limitaciones** | | |

### Consideraciones del equipo
Análisis crítico de la experiencia práctica: dificultades encontradas, diferencias entre la simulación y el robot real, y lecciones aprendidas.

---

## 7. Diagrama de Flujo del Algoritmo

![Diagrama de flujo](images/Diagrama_Flujo.png)

---

### Referencias

1. [Fabricante]. *Manual de especificaciones y operación del manipulador*.
2. [Documentación de software / librería utilizada].

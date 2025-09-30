# 🖥️ Simulador de Arquitectura x86

Este proyecto consiste en el desarrollo de un **simulador interactivo** de una arquitectura de computadora tipo **x86**.  
El objetivo principal es ilustrar de forma didáctica el funcionamiento de los componentes clave de un sistema computacional, permitiendo a los estudiantes **cargar, ejecutar y visualizar código ensamblador x86** de manera sencilla.

El simulador se desarrollará en **JavaScript** usando **Google Apps Script** sobre Google Sheets, aprovechando la hoja de cálculo como interfaz visual para observar los cambios en cada componente.

---

## 🚀 Características Principales

- **Cargar y ejecutar código ensamblador x86** paso a paso.
- **Visualización interactiva** de los principales componentes:
  - CPU (Unidad de Control, ALU y Registros).
  - Memoria Física, Memoria Caché y Memoria Virtual.
  - Unidad de Entrada/Salida (I/O).
  - Pipeline de instrucciones.
- **Simulación de políticas internas:**
  - Políticas de reemplazo de caché (ej. LRU).
  - Manejo de riesgos (*hazards*) en el pipeline.
- **Arquitectura de Von Neumann**: unifica instrucciones y datos en una sola memoria.
- *(Opcional)* Traducción de fragmentos de código en C a ensamblador x86.

---

## 📑 Hojas del Simulador

El simulador utiliza múltiples hojas de Google Sheets para organizar y representar cada aspecto de la arquitectura:

- **Programa:** Para ingresar el código ensamblador x86 que se ejecutará.  
- **Procesos:** Visualización de los procesos en ejecución.  
- **Bitácora:** Registro de los eventos e instrucciones ejecutadas.  
- **Cambio:** Seguimiento de cambios en memoria y estados de ejecución.  
- **MemoriaFisica:** Representación gráfica de la memoria física.  
- **MemoriaVirtual:** Estado de la memoria virtual.  
- **Grafico MV:** Visualización gráfica de la relación entre memoria física y virtual.  
- **Bloqueo:** Muestra los bloqueos o *hazards* en el pipeline.  
- **Pipeline:** Representación del flujo de instrucciones a través de las etapas del pipeline.  
- **Consola:** Permite la interacción directa con el simulador y muestra mensajes al usuario.  
- **Memoria y Registros:** Panel que muestra el estado de los registros y las secciones de memoria relevantes.  

---

## 🛠️ Tecnologías Utilizadas

- [Google Apps Script (JavaScript)](https://developers.google.com/apps-script) – para la lógica y simulación.
- [Google Sheets](https://www.google.com/sheets/about/) – para la interfaz visual del simulador.
- [GitHub](https://github.com/) – para el **control de versiones** y trabajo colaborativo.
- **GitHub Projects/Issues** – para el **seguimiento de tareas** y organización del flujo de trabajo.

---

## 📖 Cómo Usar el Simulador

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Leandro0210/ProyectoArqui.git

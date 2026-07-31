# 🧮 Calculadora de Salario por Hora y Día (CGT)

Una aplicación web ligera, interactiva y totalmente *responsive* diseñada para calcular de forma precisa la tarifa por hora y las ganancias brutas y netas de una jornada laboral diaria, adaptándose a contratos a tiempo parcial o completo.

---

## 🚀 ¿Qué se puede hacer con esta aplicación?

Esta calculadora permite a cualquier trabajador/a simular y comprobar fácilmente cuánto gana en una jornada de trabajo en función de sus condiciones contractuales y las características del día trabajado.

### 📌 Características y Funcionalidades Principales

* **Ajuste por jornada contractual:**
  * Define el **Salario Bruto Anual Base** para una jornada de 40 horas.
  * Permite especificar las **Horas Semanales de tu Contrato** (ej. 20h, 24.5h, 32h, 40h) para calcular de forma proporcional el salario ajustado y el precio de la hora ordinaria.

* **Cálculo de Jornada por Horas y Minutos:**
  * Entradas independientes para **horas y minutos trabajados en el día** (ej. 6 horas y 45 minutos) con conversión decimal automática para un cálculo exacto.

* **Gestión de Pluses y Complementos:**
  * **Antigüedad:** Selección de tramos de antigüedad acumulada (5, 10, 15, 20, 25, 30+ años) con su correspondiente plus mensual.
  * **Plus de Transporte:** Opción para incluir el plus diario de transporte.
  * **Plus Nocturnidad:** Cálculo del importe según el número de horas trabajadas en horario nocturno.
  * **Turno de Domingo / Día Festivo:** Aplicación de pluses específicos por jornada de domingo o día festivo.

* **Tipos de Horas Trabajadas:**
  * Selección excluyente entre **Hora Ordinaria**, **Hora Extraordinaria** o **Hora Complementaria**, ajustando la tarifa automáticamente.

* **Desglose de Retención IRPF (Bruto vs. Neto):**
  * Campo configurable para introducir el porcentaje de retención de **IRPF**.
  * Desglose final detallado con el **Total Bruto del día**, el importe descontado por IRPF y el **Total Neto a percibir**.

* **Diseño Responsive Móvil & Web:**
  * Adaptado a todo tipo de pantallas (móviles, tablets y PC).
  * Evita zooms indeseados en teclados móviles y cuenta con controles táctiles optimizados.

---

## 🛠️ Tecnologías utilizadas

* **HTML5:** Estructura semántica de la aplicación.
* **CSS3:** Estilos visuales con *Glassmorphism*, diseño responsive (*Media Queries*) y adaptación a móviles.
* **JavaScript (Vanilla JS):** Lógica de cálculo financiero y gestión dinámica del DOM sin librerías externas.

---

## 📂 Cómo ejecutar el proyecto

No requiere instalación, servidor web ni dependencias externas.

1. Clona o descarga este repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)

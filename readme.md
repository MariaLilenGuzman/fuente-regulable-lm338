# ⚡ Fuente regulable con LM338K
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Project Status](https://img.shields.io/badge/Status-En%20desarrollo-blue)

Proyecto de fuente de alimentación variable usando una fuente ATX reciclada y un regulador de voltaje **LM338K**. Diseñada para uso en laboratorio o proyectos electrónicos caseros, permite obtener salidas fijas y una salida ajustable con medición digital.

---

## ✅ Características

- 🔌 **Salidas fijas**: 3.3V, 5V y 12V (proporcionadas por la fuente ATX).
- 🎛️ **Salida variable**: ajustable con LM338K mediante potenciómetro.
- 📟 **Medición digital**: voltímetro y amperímetro para la salida variable.
- 🔧 Basada en componentes fáciles de conseguir y bajo costo.

---

## 📷 Vista previa

> *(Agregar aquí una imagen real o render del prototipo armado)*

```
Ruta sugerida: /images/vista_previa.png
```

---

## 📐 Diagrama de bloques

imagen agregar

---
## 📋 Lista de materiales

Ver archivo en: `/materiales/lista_componentes.xlsx`

Incluye:

- Fuente ATX reciclada
- LM338K con disipador
- Potenciómetro 5K
- Voltímetro/amperímetro digital
- Placa perforada o PCB
- Caja estanca exterior
- Fusibles de automotor
- Terminales Faston hembra 6.3 mm (para conexión de los fusibles)
- Conectores banana macho y hembra (rojo y negro)
- Capacitores electrolíticos y cerámicos (para filtrado de la salida regulada)
---

## 📎 Documentación técnica

- Esquema eléctrico: `docs/esquema_electrico.pdf`
- Diagrama de bloques: `docs/diagrama_bloques.png`
- Fotos del armado: `docs/fotos_armado/`

---

## 🛠️ Proceso de construcción

Este proyecto fue desarrollado reutilizando una fuente ATX de PC como base. Se extrajeron los 3.3V, 5V y 12V directamente desde el cableado original, mientras que la salida variable se implementó usando un regulador LM338K montado sobre un disipador de calor.

Se usaron fusibles de automotor para proteger cada salida, conectados mediante terminales Faston hembra de 6.3 mm. Las conexiones se realizaron en una placa perforada, organizada dentro de una caja reciclada. La medición de tensión y corriente de la salida variable se logra con un módulo digital de voltímetro/amperímetro.

> *(Podés expandir esto con detalles sobre el montaje, pruebas, errores, mejoras, etc.)*

---

## 🧠 Cómo usar

1. Conectar la fuente ATX al módulo de salidas.
2. Ajustar el potenciómetro para modificar el voltaje variable.
3. Usar la medición digital para ver los valores en tiempo real.
4. No exceder los límites de corriente del LM338K (hasta 5A con disipación adecuada).

---

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**. Podés usarlo, modificarlo y compartirlo libremente dando crédito al autor.

Ver archivo: [`LICENSE`](./LICENSE)

---

## 🙋‍♀️ Autora

Proyecto desarrollado por **María Lilen Guzmán**.

- Portfolio: *(link opcional)*
- Contacto: *(email opcional)*


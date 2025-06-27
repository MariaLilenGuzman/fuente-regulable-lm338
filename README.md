# 🔋 Fuente de Alimentación Regulable ATX con LM338K

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Project Status](https://img.shields.io/badge/Status-En%20desarrollo-blue)

Proyecto de fuente de alimentación variable usando una fuente ATX reciclada y un regulador de voltaje **LM338K**. Diseñada para uso en laboratorio o proyectos electrónicos caseros, permite obtener salidas fijas y una salida ajustable con medición digital.

![](https://via.placeholder.com/800x400?text=Imagen+Principal+del+Proyecto)

> **Nota:** Este proyecto está bajo la licencia MIT. Ver el archivo [LICENSE](./LICENSE) para más información.
## 📋 Características Principales

- **Salidas fijas:** 
  - +3.3V (hasta 20A*)
  - +5V (hasta 25A*)
  - +12V (hasta 15A*)
  - (*Depende de la fuente ATX utilizada)
  
- **Salida variable regulada:**
  - Rango: 1.2V - 30V
  - Corriente máxima: 5A
  - Regulador: LM338K (TO-3)
  
- **Sistema de medición:**
  - Voltímetro digital: 0-30V ±0.1V
  - Amperímetro digital: 0-5A ±0.01A
  - Pantalla LCD o LED dual

## ⚠️ Advertencias de Seguridad

¡Alto voltaje! La fuente ATX contiene condensadores que mantienen carga
Usar siempre:
  - Guantes aislantes
  - Gafas de protección
  - Herramientas con aislamiento
  - Nunca trabajar con la fuente conectada a la red eléctrica

## 📦 Componentes Clave

| Componente | Especificación |
|------------|----------------|
| Regulador | LM338K (TO-3) |
| Fuente ATX | Estándar (500W recomendado) |
| Medición | Módulo Voltímetro/Ampérimetro Digital |
| Disipador | Módulo disipador aluminio 100x50x25mm |
| Conectores | Terminales tornillo 5mm |
| Protección | Fusibles reseteables PTC |

## ⚡ Diagrama de Bloques

```mermaid
graph LR
A[Fuente ATX] --> B[Salidas Fijas 3.3V/5V/12V]
A --> C[Regulador LM338K]
C --> D[Medición V/A Digital]
D --> E[Salida Variable]


# ⚡ Fuente regulable con LM338K

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



---

## 📋 Lista de materiales

Ver archivo en: `/materiales/lista_componentes.xlsx`

Incluye:

- Fuente ATX reciclada
- LM338K con disipador
- Potenciómetro 5K
- Voltímetro/amperímetro digital
- Borneras
- Placa perforada o PCB
- Caja o carcasa
- Fusibles de automotor
- Terminales Faston hembra 6.3 mm (para conexión de los fusibles)

---

## 📎 Documentación técnica

- Esquema eléctrico: `docs/esquema_electrico.pdf`
- Diagrama de bloques: `docs/diagrama_bloques.png`
- Fotos del armado: `docs/fotos_armado/`


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



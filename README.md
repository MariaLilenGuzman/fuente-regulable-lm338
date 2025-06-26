# 🔋 Fuente de Alimentación Regulable ATX con LM338K

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Project Status](https://img.shields.io/badge/Status-En%20desarrollo-blue)

Conversión de fuente ATX de computadora a banco de alimentación profesional con salidas fijas y variable, incluyendo sistema de medición digital de voltaje y corriente.

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

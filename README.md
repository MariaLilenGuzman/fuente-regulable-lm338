# ⚡ Fuente regulable con LM338K
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Project Status](https://img.shields.io/badge/Status-En%20desarrollo-blue)

Proyecto de fuente de alimentación variable usando una fuente ATX reciclada y un regulador de voltaje **LM338K**. Diseñada para uso en laboratorio o proyectos electrónicos caseros, permite obtener salidas fijas y una salida ajustable con medición digital.

---
## Índice

- [Características](#características)
- [Proceso de construcción](#proceso-de-construcción)
- [Lista de materiales](#lista-de-materiales)
- [Documentación técnica](#documentación-técnica)
- [Licencia](#licencia)
- [Autora](#autora)

---

## Características

- 🔌 **Salidas fijas**: 3.3V, 5V y 12V (proporcionadas por la fuente ATX).
- 🎛️ **Salida variable**: ajustable con LM338K mediante potenciómetro.
- 📟 **Medición digital**: voltímetro y amperímetro para la salida variable.
- 🧲 Incluye conector **Molex** para alimentar periféricos como discos duros SATA.
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

1. Se utiliza una fuente de PC ATX genérica de 500 W como base para el proyecto.

2. Se extrae la fuente de su carcasa metálica original para instalarla en una caja estanca de plástico. Esto se hace para evitar riesgos eléctricos asociados a la carcasa metálica y asegurar un aislamiento seguro.

3. Se corta el conector ATX de 24 pines, ya que no se utilizará en esta configuración.
4. Se contaron cuántos cables de cada color (rojo, amarillo, naranja y negro) iban a utilizarse en el proyecto, y se desoldaron los que sobraban. Esta decisión se tomó para mantener el interior más ordenado y facilitar las conexiones.
Los cables de control y señal, como PS-ON y Power Good, se mantuvieron conectados ya que son necesarios para el funcionamiento básico de la fuente, aunque su uso específico se explicará más adelante.

5. Para obtener las salidas de voltaje estándar de 3.3 V, 5 V y 12 V:
   - Se sueldan entre sí dos cables naranjas (3.3 V) a una terminal Faston hembra de 6.3 mm.
   - Se sueldan tres cables rojos (5 V) y tres cables amarillos (12 V), cada conjunto a su respectiva terminal Faston hembra de 6.3 mm.

6. Como no se planea usar múltiples salidas simultáneamente, se prepararon dos pares de tres cables negros para la conexión a tierra, terminados en conectores banana hembra.

7. Se instalan fusibles de automotor para proteger cada salida: 3 A para 3.3 V, 3 A para 5 V, y 5 A para 12 V.

8. Se conserva el ventilador original de la fuente (extracción) y se agrega un segundo ventilador para ingreso de aire. Este ventilador es de 12 V y consume 0.7 W. 

9. Como no se disponía de más cables amarillos, el ventilador se alimenta mediante una derivación desde el conector Molex de la fuente, utilizando su línea de 12 V y GND. Esto se debe a que, antes de decidir agregar el ventilador adicional, se habían desoldado algunos cables amarillos pensando que no serían necesarios. Si no se hubieran retirado, no habría hecho falta esta derivación. Esta opción sigue siendo segura debido al bajo consumo del ventilador.

10. Se deja disponible el conector Molex original para alimentar dispositivos como discos duros SATA de 3.5". Esta salida es útil para pruebas, alimentación auxiliar o recuperación de datos sin necesidad de carcasa externa.

11. Finalmente, se monta el circuito regulable con LM338K sobre un disipador de calor, y se conecta a la salida variable. Se agrega un voltímetro/amperímetro digital para monitorear esta salida.

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


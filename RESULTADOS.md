# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 5 correctas de 41 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre
+Nombre
 Disco duro SATA3 1TB
 Memoria RAM DDR4 8GB
 Disco SSD 1 TB
```

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+Nombre | Precio
 Disco duro SATA3 1TB | 86.99
 Memoria RAM DDR4 8GB | 120.00
 Disco SSD 1 TB | 150.99
```

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio_eur | precio_usd
+Nombre | Precio (€) | Precio ($)
 Disco duro SATA3 1TB | 86.99 | 86.99
 Memoria RAM DDR4 8GB | 120.00 | 120.00
 Disco SSD 1 TB | 150.99 | 150.99
```

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nom del producte | euros | dòlars
+Nombre | Precio (€) | Precio ($)
 Disco duro SATA3 1TB | 86.99 | 95.69
 Memoria RAM DDR4 8GB | 120.00 | 132.00
 Disco SSD 1 TB | 150.99 | 166.09
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+Producto | precio
 DISCO DURO SATA3 1TB | 86.99
 MEMORIA RAM DDR4 8GB | 120.00
 DISCO SSD 1 TB | 150.99
```

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+Producto | precio
 disco duro sata3 1tb | 86.99
 memoria ram ddr4 8gb | 120.00
 disco ssd 1 tb | 150.99
```

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | iniciales
+Nombre | Initial
 Asus | AS
 Lenovo | LE
 Hewlett-Packard | HE
```

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+Nombre | Precio redeado
 Disco duro SATA3 1TB | 87.00
 Memoria RAM DDR4 8GB | 120.00
 Disco SSD 1 TB | 151.00
```

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio truncado
+Nombre | Precio truncado
 Disco duro SATA3 1TB | 86.00
 Memoria RAM DDR4 8GB | 120.00
 Disco SSD 1 TB | 150.00
```

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 11: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-codigo_fabricante
-1.00
+Código del fabricante
+6.00
+7.00
+8.00
+9.00
+10.00
+11.00
+3.00
 1.00
 2.00
-2.00
-3.00
-3.00
+5.00
 4.00
-5.00
-6.00
-6.00
-7.00
```

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 12: Incorrecto
```diff
--- 
+++ 
@@ -1,8 +1,12 @@
-codigo_fabricante
+Código del fabricante
+6.00
+7.00
+8.00
+9.00
+10.00
+11.00
+3.00
 1.00
 2.00
-3.00
+5.00
 4.00
-5.00
-6.00
-7.00
```

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY,codigo_fabricante

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre
+Nombre del fabricante (↑)
 Asus
 Crucial
 Gigabyte
```

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 14: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre
+Nombre del fabricante (↓)
 Xiaomi
 Seagate
 Samsung
```

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+Producto | Precio
 Disco duro SATA3 1TB | 86.99
 Disco SSD 1 TB | 150.99
 GeForce GTX 1050Ti | 185.00
```

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.22 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio
+Producto mas económico | precio
 Impresora HP Deskjet 3720 | 59.99
```

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio
+Producto mas caro | precio
 GeForce GTX 1080 Xtreme | 755.00
```

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre
+Productos Código 2
 Portátil Yoga 520
 Portátil Ideapd 320
```

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio | nombre del fabricante
+Producto | Precio | Nombre fabricante
 Disco duro SATA3 1TB | 86.99 | Seagate
 Memoria RAM DDR4 8GB | 120.00 | Crucial
 Disco SSD 1 TB | 150.99 | Samsung
```

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio | nombre del fabricante
+Producto | Precio | Fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate
+Disco SSD 1 TB | 150.99 | Samsung
+GeForce GTX 1050Ti | 185.00 | Gigabyte
+GeForce GTX 1080 Xtreme | 755.00 | Crucial
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Memoria RAM DDR4 8GB | 120.00 | Crucial
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
-Memoria RAM DDR4 8GB | 120.00 | Crucial
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-GeForce GTX 1050Ti | 185.00 | Gigabyte
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Portátil Ideapd 320 | 444.00 | Lenovo
 Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Disco SSD 1 TB | 150.99 | Samsung
-Disco duro SATA3 1TB | 86.99 | Seagate
```

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-codigo | nombre | codigo fabricante | nombre fabricante
+Código Producto | Nombre Producto | Código Fabricante | Nombre Fabricante
 1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
 2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
 3.00 | Disco SSD 1 TB | 4.00 | Samsung
```

⏱ Tiempo: 0.25 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio | fabricant
+Producto | Precio | Fabricante
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
```

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 25: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio | fabricante
+Producto | Precio | Fabricante
 GeForce GTX 1080 Xtreme | 755.00 | Crucial
```

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 26: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | precio
+Producto | Precio
 Portátil Yoga 520 | 559.00
 Portátil Ideapd 320 | 444.00
```

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 27: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,6 @@
-nombre | precio
+Producto | Precio
 GeForce GTX 1080 Xtreme | 755.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 245.99
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 28: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio | fabricante
+Producto | Precio | Fabricante
 Disco duro SATA3 1TB | 86.99 | Seagate
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 29: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio | fabricante
+Producto | Precio | Fabricante
 Disco duro SATA3 1TB | 86.99 | Seagate
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ❌ Query 30: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | precio | fabricante
+Producto | Precio | Fabricante
 Disco duro SATA3 1TB | 86.99 | Seagate
 GeForce GTX 1050Ti | 185.00 | Gigabyte
```

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 31: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | precio | fabricante
+Producto | Precio | nombre
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
 Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 32: Incorrecto
```diff
--- 
+++ 
@@ -1,8 +1,8 @@
-nombre | precio | fabricante
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Monitor 27 LED Full HD | 245.99 | Asus
-Monitor 24 LED Full HD | 202.00 | Asus
-GeForce GTX 1050Ti | 185.00 | Gigabyte
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+nombre | precio
+GeForce GTX 1050Ti | 185.00
+GeForce GTX 1080 Xtreme | 755.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 245.99
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
+Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 33: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-codigo | nombre
+Codigo | Fabricante
 1.00 | Asus
 2.00 | Lenovo
 3.00 | Hewlett-Packard
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 34: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-fabricante | producto
+Fabricante | Producto
 Asus | Monitor 27 LED Full HD
 Asus | Monitor 24 LED Full HD
 Lenovo | Portátil Ideapd 320
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 35: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-fabricante
+Fabricante
 Huawei
 Xiaomi
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 36: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 37: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 38: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre
-Portátil Yoga 520
+Producto | Precio
+Portátil Yoga 520 | 559.00
```

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 39: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre
-Impresora HP Deskjet 3720
+Producto | Precio
+Portátil Ideapd 320 | 444.00
```

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 40: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,4 @@
-codigo | nombre | precio | codigo_fabricante
-5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
-8.00 | Portátil Yoga 520 | 559.00 | 2.00
+Producto
+GeForce GTX 1080 Xtreme
+Portátil Yoga 520
+Portátil Ideapd 320
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 41: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-codigo | nombre | precio | codigo_fabricante
-7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+Average (€)
+224.00
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

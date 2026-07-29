# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 0 correctas de 42 queries

## ❌ Query 1: Error
- **Descripción**: 'NoneType' object is not iterable


## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-Disco duro SATA3 1TB | 86.99
-Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 150.99
-GeForce GTX 1050Ti | 185.00
-GeForce GTX 1080 Xtreme | 755.00
-Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.99
-Portátil Yoga 520 | 559.00
-Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00
+nombre
+Disco duro SATA3 1TB
+Memoria RAM DDR4 8GB
+Disco SSD 1 TB
+GeForce GTX 1050Ti
+GeForce GTX 1080 Xtreme
+Monitor 24 LED Full HD
+Monitor 27 LED Full HD
+Portátil Yoga 520
+Portátil Ideapd 320
+Impresora HP Deskjet 3720
+Impresora HP Laserjet Pro M26nw
```

⏱ Tiempo: 0.44 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 3: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-codigo | nombre | precio | codigo_fabricante
-1.00 | Disco duro SATA3 1TB | 86.99 | 5.00
-2.00 | Memoria RAM DDR4 8GB | 120.00 | 6.00
-3.00 | Disco SSD 1 TB | 150.99 | 4.00
-4.00 | GeForce GTX 1050Ti | 185.00 | 7.00
-5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
-6.00 | Monitor 24 LED Full HD | 202.00 | 1.00
-7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
-8.00 | Portátil Yoga 520 | 559.00 | 2.00
-9.00 | Portátil Ideapd 320 | 444.00 | 2.00
-10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
-11.00 | Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
+nombre | precio
+Disco duro SATA3 1TB | 86.99
+Memoria RAM DDR4 8GB | 120.00
+Disco SSD 1 TB | 150.99
+GeForce GTX 1050Ti | 185.00
+GeForce GTX 1080 Xtreme | 755.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 245.99
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
+Impresora HP Deskjet 3720 | 59.99
+Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio_eur | precio_usd
-Disco duro SATA3 1TB | 86.99 | 86.99
-Memoria RAM DDR4 8GB | 120.00 | 120.00
-Disco SSD 1 TB | 150.99 | 150.99
-GeForce GTX 1050Ti | 185.00 | 185.00
-GeForce GTX 1080 Xtreme | 755.00 | 755.00
-Monitor 24 LED Full HD | 202.00 | 202.00
-Monitor 27 LED Full HD | 245.99 | 245.99
-Portátil Yoga 520 | 559.00 | 559.00
-Portátil Ideapd 320 | 444.00 | 444.00
-Impresora HP Deskjet 3720 | 59.99 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00 | 180.00
+codigo | nombre | precio | codigo_fabricante
+1.00 | Disco duro SATA3 1TB | 86.99 | 5.00
+2.00 | Memoria RAM DDR4 8GB | 120.00 | 6.00
+3.00 | Disco SSD 1 TB | 150.99 | 4.00
+4.00 | GeForce GTX 1050Ti | 185.00 | 7.00
+5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
+6.00 | Monitor 24 LED Full HD | 202.00 | 1.00
+7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
+11.00 | Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nom del producte | euros | dòlars
-Disco duro SATA3 1TB | 86.99 | 95.69
-Memoria RAM DDR4 8GB | 120.00 | 132.00
-Disco SSD 1 TB | 150.99 | 166.09
-GeForce GTX 1050Ti | 185.00 | 203.50
-GeForce GTX 1080 Xtreme | 755.00 | 830.50
-Monitor 24 LED Full HD | 202.00 | 222.20
-Monitor 27 LED Full HD | 245.99 | 270.59
-Portátil Yoga 520 | 559.00 | 614.90
-Portátil Ideapd 320 | 444.00 | 488.40
-Impresora HP Deskjet 3720 | 59.99 | 65.99
-Impresora HP Laserjet Pro M26nw | 180.00 | 198.00
+nombre | precio | (producto.precio * 1)
+Disco duro SATA3 1TB | 86.99 | 86.99
+Memoria RAM DDR4 8GB | 120.00 | 120.00
+Disco SSD 1 TB | 150.99 | 150.99
+GeForce GTX 1050Ti | 185.00 | 185.00
+GeForce GTX 1080 Xtreme | 755.00 | 755.00
+Monitor 24 LED Full HD | 202.00 | 202.00
+Monitor 27 LED Full HD | 245.99 | 245.99
+Portátil Yoga 520 | 559.00 | 559.00
+Portátil Ideapd 320 | 444.00 | 444.00
+Impresora HP Deskjet 3720 | 59.99 | 59.99
+Impresora HP Laserjet Pro M26nw | 180.00 | 180.00
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-DISCO DURO SATA3 1TB | 86.99
-MEMORIA RAM DDR4 8GB | 120.00
-DISCO SSD 1 TB | 150.99
-GEFORCE GTX 1050TI | 185.00
-GEFORCE GTX 1080 XTREME | 755.00
-MONITOR 24 LED FULL HD | 202.00
-MONITOR 27 LED FULL HD | 245.99
-PORTÁTIL YOGA 520 | 559.00
-PORTÁTIL IDEAPD 320 | 444.00
-IMPRESORA HP DESKJET 3720 | 59.99
-IMPRESORA HP LASERJET PRO M26NW | 180.00
+Nombre | Precio (€) | Precio ($)
+Disco duro SATA3 1TB | 86.99 | 95.69
+Memoria RAM DDR4 8GB | 120.00 | 132.00
+Disco SSD 1 TB | 150.99 | 166.09
+GeForce GTX 1050Ti | 185.00 | 203.50
+GeForce GTX 1080 Xtreme | 755.00 | 830.50
+Monitor 24 LED Full HD | 202.00 | 222.20
+Monitor 27 LED Full HD | 245.99 | 270.59
+Portátil Yoga 520 | 559.00 | 614.90
+Portátil Ideapd 320 | 444.00 | 488.40
+Impresora HP Deskjet 3720 | 59.99 | 65.99
+Impresora HP Laserjet Pro M26nw | 180.00 | 198.00
```

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-disco duro sata3 1tb | 86.99
-memoria ram ddr4 8gb | 120.00
-disco ssd 1 tb | 150.99
-geforce gtx 1050ti | 185.00
-geforce gtx 1080 xtreme | 755.00
-monitor 24 led full hd | 202.00
-monitor 27 led full hd | 245.99
-portátil yoga 520 | 559.00
-portátil ideapd 320 | 444.00
-impresora hp deskjet 3720 | 59.99
-impresora hp laserjet pro m26nw | 180.00
+Producto | precio
+DISCO DURO SATA3 1TB | 86.99
+MEMORIA RAM DDR4 8GB | 120.00
+DISCO SSD 1 TB | 150.99
+GEFORCE GTX 1050TI | 185.00
+GEFORCE GTX 1080 XTREME | 755.00
+MONITOR 24 LED FULL HD | 202.00
+MONITOR 27 LED FULL HD | 245.99
+PORTÁTIL YOGA 520 | 559.00
+PORTÁTIL IDEAPD 320 | 444.00
+IMPRESORA HP DESKJET 3720 | 59.99
+IMPRESORA HP LASERJET PRO M26NW | 180.00
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,12 @@
-nombre | iniciales
-Asus | AS
-Lenovo | LE
-Hewlett-Packard | HE
-Samsung | SA
-Seagate | SE
-Crucial | CR
-Gigabyte | GI
-Huawei | HU
-Xiaomi | XI
+Producto | precio
+disco duro sata3 1tb | 86.99
+memoria ram ddr4 8gb | 120.00
+disco ssd 1 tb | 150.99
+geforce gtx 1050ti | 185.00
+geforce gtx 1080 xtreme | 755.00
+monitor 24 led full hd | 202.00
+monitor 27 led full hd | 245.99
+portátil yoga 520 | 559.00
+portátil ideapd 320 | 444.00
+impresora hp deskjet 3720 | 59.99
+impresora hp laserjet pro m26nw | 180.00
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,10 @@
-nombre | precio
-Disco duro SATA3 1TB | 87.00
-Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 151.00
-GeForce GTX 1050Ti | 185.00
-GeForce GTX 1080 Xtreme | 755.00
-Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 246.00
-Portátil Yoga 520 | 559.00
-Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 60.00
-Impresora HP Laserjet Pro M26nw | 180.00
+Nombre | Initial
+Asus | AS
+Lenovo | LE
+Hewlett-Packard | HE
+Samsung | SA
+Seagate | SE
+Crucial | CR
+Gigabyte | GI
+Huawei | HU
+Xiaomi | XI
```

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio truncado
-Disco duro SATA3 1TB | 86.00
+Nombre | Precio redeado
+Disco duro SATA3 1TB | 87.00
 Memoria RAM DDR4 8GB | 120.00
-Disco SSD 1 TB | 150.00
+Disco SSD 1 TB | 151.00
 GeForce GTX 1050Ti | 185.00
 GeForce GTX 1080 Xtreme | 755.00
 Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.00
+Monitor 27 LED Full HD | 246.00
 Portátil Yoga 520 | 559.00
 Portátil Ideapd 320 | 444.00
-Impresora HP Deskjet 3720 | 59.00
+Impresora HP Deskjet 3720 | 60.00
 Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 11: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-codigo_fabricante
-1.00
-1.00
-2.00
-2.00
-3.00
-3.00
-4.00
-5.00
-6.00
-6.00
-7.00
+Nombre | Precio truncado
+Disco duro SATA3 1TB | 86.00
+Memoria RAM DDR4 8GB | 120.00
+Disco SSD 1 TB | 150.00
+GeForce GTX 1050Ti | 185.00
+GeForce GTX 1080 Xtreme | 755.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 245.00
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
+Impresora HP Deskjet 3720 | 59.00
+Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.41 ms
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

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,12 @@
-nombre
-Asus
-Crucial
-Gigabyte
-Hewlett-Packard
-Huawei
-Lenovo
-Samsung
-Seagate
-Xiaomi
+Código del fabricante
+6.00
+7.00
+8.00
+9.00
+10.00
+11.00
+3.00
+1.00
+2.00
+5.00
+4.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY,codigo_fabricante

---

## ❌ Query 14: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
-nombre
+Nombre del fabricante (↑)
+Asus
+Crucial
+Gigabyte
+Hewlett-Packard
+Huawei
+Lenovo
+Samsung
+Seagate
 Xiaomi
-Seagate
-Samsung
-Lenovo
-Huawei
-Hewlett-Packard
-Gigabyte
-Crucial
-Asus
```

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,10 @@
-nombre | precio
-Disco duro SATA3 1TB | 86.99
-Disco SSD 1 TB | 150.99
-GeForce GTX 1050Ti | 185.00
-GeForce GTX 1080 Xtreme | 755.00
-Impresora HP Deskjet 3720 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00
-Memoria RAM DDR4 8GB | 120.00
-Monitor 24 LED Full HD | 202.00
-Monitor 27 LED Full HD | 245.99
-Portátil Ideapd 320 | 444.00
-Portátil Yoga 520 | 559.00
+Nombre del fabricante (↓)
+Xiaomi
+Seagate
+Samsung
+Lenovo
+Huawei
+Hewlett-Packard
+Gigabyte
+Crucial
+Asus
```

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 16: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,12 @@
-codigo | nombre
-1.00 | Asus
-2.00 | Lenovo
-3.00 | Hewlett-Packard
-4.00 | Samsung
-5.00 | Seagate
+Producto | Precio
+Disco duro SATA3 1TB | 86.99
+Disco SSD 1 TB | 150.99
+GeForce GTX 1050Ti | 185.00
+GeForce GTX 1080 Xtreme | 755.00
+Impresora HP Deskjet 3720 | 59.99
+Impresora HP Laserjet Pro M26nw | 180.00
+Memoria RAM DDR4 8GB | 120.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 245.99
+Portátil Ideapd 320 | 444.00
+Portátil Yoga 520 | 559.00
```

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 17: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,6 @@
 codigo | nombre
+1.00 | Asus
+2.00 | Lenovo
+3.00 | Hewlett-Packard
 4.00 | Samsung
 5.00 | Seagate
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,3 @@
-nombre | precio
-Impresora HP Deskjet 3720 | 59.99
+codigo | nombre
+4.00 | Samsung
+5.00 | Seagate
```

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio
-GeForce GTX 1080 Xtreme | 755.00
+Producto mas económico | precio
+Impresora HP Deskjet 3720 | 59.99
```

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,2 @@
-nombre
-Portátil Yoga 520
-Portátil Ideapd 320
+Producto mas caro | precio
+GeForce GTX 1080 Xtreme | 755.00
```

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,3 @@
-nombre | precio | nombre del fabricante
-Disco duro SATA3 1TB | 86.99 | Seagate
-Memoria RAM DDR4 8GB | 120.00 | Crucial
-Disco SSD 1 TB | 150.99 | Samsung
-GeForce GTX 1050Ti | 185.00 | Gigabyte
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-Monitor 24 LED Full HD | 202.00 | Asus
-Monitor 27 LED Full HD | 245.99 | Asus
-Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Productos Código 2
+Portátil Yoga 520
+Portátil Ideapd 320
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio | nombre del fabricante
+Producto | Precio | Nombre fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate
+Memoria RAM DDR4 8GB | 120.00 | Crucial
+Disco SSD 1 TB | 150.99 | Samsung
+GeForce GTX 1050Ti | 185.00 | Gigabyte
+GeForce GTX 1080 Xtreme | 755.00 | Crucial
 Monitor 24 LED Full HD | 202.00 | Asus
 Monitor 27 LED Full HD | 245.99 | Asus
-Memoria RAM DDR4 8GB | 120.00 | Crucial
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-GeForce GTX 1050Ti | 185.00 | Gigabyte
+Portátil Yoga 520 | 559.00 | Lenovo
+Portátil Ideapd 320 | 444.00 | Lenovo
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
 Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
-Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Disco SSD 1 TB | 150.99 | Samsung
-Disco duro SATA3 1TB | 86.99 | Seagate
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-codigo | nombre | codigo fabricante | nombre fabricante
-1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
-2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
-3.00 | Disco SSD 1 TB | 4.00 | Samsung
-4.00 | GeForce GTX 1050Ti | 7.00 | Gigabyte
-5.00 | GeForce GTX 1080 Xtreme | 6.00 | Crucial
-6.00 | Monitor 24 LED Full HD | 1.00 | Asus
-7.00 | Monitor 27 LED Full HD | 1.00 | Asus
-8.00 | Portátil Yoga 520 | 2.00 | Lenovo
-9.00 | Portátil Ideapd 320 | 2.00 | Lenovo
-10.00 | Impresora HP Deskjet 3720 | 3.00 | Hewlett-Packard
-11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Hewlett-Packard
+Producto | Precio | Fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate
+Disco SSD 1 TB | 150.99 | Samsung
+GeForce GTX 1050Ti | 185.00 | Gigabyte
+GeForce GTX 1080 Xtreme | 755.00 | Crucial
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Memoria RAM DDR4 8GB | 120.00 | Crucial
+Monitor 24 LED Full HD | 202.00 | Asus
+Monitor 27 LED Full HD | 245.99 | Asus
+Portátil Ideapd 320 | 444.00 | Lenovo
+Portátil Yoga 520 | 559.00 | Lenovo
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,12 @@
-nombre | precio | fabricant
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
+Código Producto | Nombre Producto | Código Fabricante | Nombre Fabricante
+1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
+2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
+3.00 | Disco SSD 1 TB | 4.00 | Samsung
+4.00 | GeForce GTX 1050Ti | 7.00 | Gigabyte
+5.00 | GeForce GTX 1080 Xtreme | 6.00 | Crucial
+6.00 | Monitor 24 LED Full HD | 1.00 | Asus
+7.00 | Monitor 27 LED Full HD | 1.00 | Asus
+8.00 | Portátil Yoga 520 | 2.00 | Lenovo
+9.00 | Portátil Ideapd 320 | 2.00 | Lenovo
+10.00 | Impresora HP Deskjet 3720 | 3.00 | Hewlett-Packard
+11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Hewlett-Packard
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 25: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio | fabricante
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
+Producto | Precio | Fabricante
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 26: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,2 @@
-nombre | precio
-Portátil Yoga 520 | 559.00
-Portátil Ideapd 320 | 444.00
+Producto | Precio | Fabricante
+GeForce GTX 1080 Xtreme | 755.00 | Crucial
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 27: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,3 @@
-nombre | precio
-GeForce GTX 1080 Xtreme | 755.00
+Producto | Precio
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 28: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,6 @@
-nombre | precio | fabricante
-Disco duro SATA3 1TB | 86.99 | Seagate
-Monitor 24 LED Full HD | 202.00 | Asus
-Monitor 27 LED Full HD | 245.99 | Asus
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Producto | Precio
+GeForce GTX 1080 Xtreme | 755.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 245.99
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
```

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

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

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 30: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,6 @@
-nombre | precio | fabricante
+Producto | Precio | Fabricante
 Disco duro SATA3 1TB | 86.99 | Seagate
-GeForce GTX 1050Ti | 185.00 | Gigabyte
+Monitor 24 LED Full HD | 202.00 | Asus
+Monitor 27 LED Full HD | 245.99 | Asus
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ❌ Query 31: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | precio | fabricante
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+Producto | Precio | Fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate
+GeForce GTX 1050Ti | 185.00 | Gigabyte
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 32: Incorrecto
```diff
--- 
+++ 
@@ -1,8 +1,3 @@
-nombre | precio | fabricante
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Monitor 27 LED Full HD | 245.99 | Asus
-Monitor 24 LED Full HD | 202.00 | Asus
-GeForce GTX 1050Ti | 185.00 | Gigabyte
+Producto | Precio | nombre
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
 Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 33: Incorrecto
```diff
--- 
+++ 
@@ -1,8 +1,8 @@
-codigo | nombre
-1.00 | Asus
-2.00 | Lenovo
-3.00 | Hewlett-Packard
-4.00 | Samsung
-5.00 | Seagate
-6.00 | Crucial
-7.00 | Gigabyte
+nombre | precio
+GeForce GTX 1050Ti | 185.00
+GeForce GTX 1080 Xtreme | 755.00
+Monitor 24 LED Full HD | 202.00
+Monitor 27 LED Full HD | 245.99
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
+Impresora HP Laserjet Pro M26nw | 180.00
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 34: Incorrecto
```diff
--- 
+++ 
@@ -1,14 +1,8 @@
-fabricante | producto
-Asus | Monitor 27 LED Full HD
-Asus | Monitor 24 LED Full HD
-Lenovo | Portátil Ideapd 320
-Lenovo | Portátil Yoga 520
-Hewlett-Packard | Impresora HP Laserjet Pro M26nw
-Hewlett-Packard | Impresora HP Deskjet 3720
-Samsung | Disco SSD 1 TB
-Seagate | Disco duro SATA3 1TB
-Crucial | GeForce GTX 1080 Xtreme
-Crucial | Memoria RAM DDR4 8GB
-Gigabyte | GeForce GTX 1050Ti
-Huawei | NULL
-Xiaomi | NULL
+Codigo | Fabricante
+1.00 | Asus
+2.00 | Lenovo
+3.00 | Hewlett-Packard
+4.00 | Samsung
+5.00 | Seagate
+6.00 | Crucial
+7.00 | Gigabyte
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 35: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,14 @@
-fabricante
-Huawei
-Xiaomi
+Fabricante | Producto
+Asus | Monitor 27 LED Full HD
+Asus | Monitor 24 LED Full HD
+Lenovo | Portátil Ideapd 320
+Lenovo | Portátil Yoga 520
+Hewlett-Packard | Impresora HP Laserjet Pro M26nw
+Hewlett-Packard | Impresora HP Deskjet 3720
+Samsung | Disco SSD 1 TB
+Seagate | Disco duro SATA3 1TB
+Crucial | GeForce GTX 1080 Xtreme
+Crucial | Memoria RAM DDR4 8GB
+Gigabyte | GeForce GTX 1050Ti
+Huawei | NULL
+Xiaomi | NULL
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 36: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-codigo | nombre | precio | codigo_fabricante
-8.00 | Portátil Yoga 520 | 559.00 | 2.00
-9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+Fabricante
+Huawei
+Xiaomi
```

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 37: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,3 @@
 codigo | nombre | precio | codigo_fabricante
 8.00 | Portátil Yoga 520 | 559.00 | 2.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
```

⏱ Tiempo: 0.36 ms
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
+codigo | nombre | precio | codigo_fabricante
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 39: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre
-Impresora HP Deskjet 3720
+Producto | Precio
+Portátil Yoga 520 | 559.00
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 40: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,2 @@
-codigo | nombre | precio | codigo_fabricante
-5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
-8.00 | Portátil Yoga 520 | 559.00 | 2.00
+Producto | Precio
+Portátil Ideapd 320 | 444.00
```

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 41: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,4 @@
-codigo | nombre | precio | codigo_fabricante
-7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+Producto
+GeForce GTX 1080 Xtreme
+Portátil Yoga 520
+Portátil Ideapd 320
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 42: Error
- **Descripción**: [Errno 2] No such file or directory: 'src/expected_results/query_42.out'


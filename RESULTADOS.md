# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 24 correctas de 26 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.44 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.50 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY, PRIMARY,id_asignatura,id_curso_escolar

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,5 +1,4 @@
 nombre
-Informática
 Matemáticas
 Economía y Empresa
 Educación
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_departamento, id_profesor

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-grau | tipo | total_creditos
+grau | tipus | total_creditos
 Grado en Ingeniería Informática (Plan 2015) | básica | 72.00
 Grado en Ingeniería Informática (Plan 2015) | obligatoria | 54.00
 Grado en Ingeniería Informática (Plan 2015) | optativa | 180.00
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ✅ Query 23: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_curso_escolar, PRIMARY

---

## ✅ Query 24: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY, id_profesor

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY, id_profesor

---

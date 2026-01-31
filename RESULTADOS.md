# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 16 correctas de 18 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.46 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, id_profesor,id_grado, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
 nombre
+Agronomía
+Biología y Geología
+Derecho
+Economía y Empresa
+Educación
+Filología
 Informática
 Matemáticas
-Economía y Empresa
-Educación
-Agronomía
 Química y Física
-Filología
-Derecho
-Biología y Geología
```

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento, id_profesor, id_asignatura

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Error
- **Descripción**: 'NoneType' object is not iterable


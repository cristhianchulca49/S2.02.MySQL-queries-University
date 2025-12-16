# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 0 correctas de 11 queries

## ❌ Query 1: Error
- **Descripción**: 'NoneType' object is not iterable


## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,13 @@
-nombre | apellido1 | apellido2
-Pedro | Heller | Pagac
-Ismael | Strosin | Turcotte
+apellido1 | apellido2 | nombre
+Domínguez | Guerrero | Antonio
+Gea | Ruiz | Sonia
+Gutiérrez | López | Juan
+Heller | Pagac | Pedro
+Herman | Pacocha | Daniel
+Hernández | Martínez | Irene
+Herzog | Tremblay | Ramón
+Koss | Bayer | José
+Lakin | Yundt | Inma
+Saez | Vega | Juan
+Sánchez | Pérez | Salvador
+Strosin | Turcotte | Ismael
```

⏱ Tiempo: 0.42 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 3: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-id | nombre | apellido1 | apellido2 | fecha_nacimiento
-7.00 | Ismael | Strosin | Turcotte | 1999-05-24
-22.00 | Antonio | Domínguez | Guerrero | 1999-02-11
+nombre | apellido1 | apellido2
+Pedro | Heller | Pagac
+Ismael | Strosin | Turcotte
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | apellido1 | apellido2 | nif
-Antonio | Fahey | Considine | 10485008K
-Guillermo | Ruecker | Upton | 85869555K
+id | nombre | apellido1 | apellido2 | fecha_nacimiento
+7.00 | Ismael | Strosin | Turcotte | 1999-05-24
+22.00 | Antonio | Domínguez | Guerrero | 1999-02-11
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,7 +1,3 @@
-id | nombre | cuatrimestre | curso | id_grado
-72.00 | Bases moleculares del desarrollo vegetal | 1.00 | 3.00 | 7.00
-73.00 | Fisiología animal | 1.00 | 3.00 | 7.00
-74.00 | Metabolismo y biosíntesis de biomoléculas | 1.00 | 3.00 | 7.00
-75.00 | Operaciones de separación | 1.00 | 3.00 | 7.00
-76.00 | Patología molecular de plantas | 1.00 | 3.00 | 7.00
-77.00 | Técnicas instrumentales básicas | 1.00 | 3.00 | 7.00
+nombre | apellido1 | apellido2 | nif
+Antonio | Fahey | Considine | 10485008K
+Guillermo | Ruecker | Upton | 85869555K
```

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,7 @@
-apellido1 | apellido2 | nombre | departamento
-Fahey | Considine | Antonio | Economía y Empresa
-Hamill | Kozey | Manolo | Informática
-Kohler | Schoen | Alejandro | Matemáticas
-Lemke | Rutherford | Cristina | Economía y Empresa
-Monahan | Murray | Micaela | Agronomía
-Ramirez | Gea | Zoe | Informática
-Ruecker | Upton | Guillermo | Educación
-Schmidt | Fisher | David | Matemáticas
-Schowalter | Muller | Francesca | Química y Física
-Spencer | Lakin | Esther | Educación
-Stiedemann | Morissette | Alfredo | Química y Física
-Streich | Hirthe | Carmen | Educación
+id | nombre | cuatrimestre | curso | id_grado
+72.00 | Bases moleculares del desarrollo vegetal | 1.00 | 3.00 | 7.00
+73.00 | Fisiología animal | 1.00 | 3.00 | 7.00
+74.00 | Metabolismo y biosíntesis de biomoléculas | 1.00 | 3.00 | 7.00
+75.00 | Operaciones de separación | 1.00 | 3.00 | 7.00
+76.00 | Patología molecular de plantas | 1.00 | 3.00 | 7.00
+77.00 | Técnicas instrumentales básicas | 1.00 | 3.00 | 7.00
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,13 @@
-nombre | anyo_inicio | anyo_fin
-Álgegra lineal y matemática discreta | 2014.00 | 2015.00
-Cálculo | 2014.00 | 2015.00
-Física para informática | 2014.00 | 2015.00
+apellido1 | apellido2 | nombre | nombre
+Fahey | Considine | Antonio | Economía y Empresa
+Hamill | Kozey | Manolo | Informática
+Kohler | Schoen | Alejandro | Matemáticas
+Lemke | Rutherford | Cristina | Economía y Empresa
+Monahan | Murray | Micaela | Agronomía
+Ramirez | Gea | Zoe | Informática
+Ruecker | Upton | Guillermo | Educación
+Schmidt | Fisher | David | Matemáticas
+Schowalter | Muller | Francesca | Química y Física
+Spencer | Lakin | Esther | Educación
+Stiedemann | Morissette | Alfredo | Química y Física
+Streich | Hirthe | Carmen | Educación
```

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,4 @@
-nombre
-Informática
+nombre | anyo_inicio | anyo_fin
+Álgegra lineal y matemática discreta | 2014.00 | 2015.00
+Cálculo | 2014.00 | 2015.00
+Física para informática | 2014.00 | 2015.00
```

⏱ Tiempo: 0.58 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,2 @@
-nombre | apellido1 | apellido2
-Inma | Lakin | Yundt
-Irene | Hernández | Martínez
-Sonia | Gea | Ruiz
+nombre
+Informática
```

⏱ Tiempo: 0.43 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY, PRIMARY,id_departamento

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,4 @@
-departamento | apellido1 | apellido2 | nombre
-Agronomía | Monahan | Murray | Micaela
-Economía y Empresa | Fahey | Considine | Antonio
-Economía y Empresa | Lemke | Rutherford | Cristina
-Educación | Ruecker | Upton | Guillermo
-Educación | Spencer | Lakin | Esther
-Educación | Streich | Hirthe | Carmen
-Informática | Hamill | Kozey | Manolo
-Informática | Ramirez | Gea | Zoe
-Matemáticas | Kohler | Schoen | Alejandro
-Matemáticas | Schmidt | Fisher | David
-Química y Física | Schowalter | Muller | Francesca
-Química y Física | Stiedemann | Morissette | Alfredo
+nombre | apellido1 | apellido2
+Inma | Lakin | Yundt
+Irene | Hernández | Martínez
+Sonia | Gea | Ruiz
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ❌ Query 11: Error
- **Descripción**: 'NoneType' object is not iterable


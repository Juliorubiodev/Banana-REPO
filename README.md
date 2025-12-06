# 🍌 Banana Leaf Disease Detection System (Cordana, Sigatoka & Pestalotiopsis)

Sistema inteligente para **detectar enfermedades en hojas de banano** a partir de imágenes, clasificando entre **Cordana**, **Sigatoka** y **Pestalotiopsis**.  
Proyecto desarrollado y vendido a una **granja productora de banano** en **Santa Marta, Magdalena, Colombia**.

**Autor:** Julio Rubio Montaño  
**Estado:** Entregado / Producción (On-field support)

---

## 🎯 Objetivo
Automatizar la identificación de enfermedades en hojas de banano para apoyar decisiones rápidas en campo, reduciendo el diagnóstico manual y mejorando el control del cultivo.

---

## ✅ Funcionalidades
- Registro e inicio de sesión de usuarios (seguridad por autenticación).
- Carga de imágenes para análisis.
- Detección/clasificación de enfermedad: Cordana / Sigatoka / Pestalotiopsis.
- Historial de detecciones (consultar resultados previos).

---

## 🧩 Requerimientos No Funcionales
- **Seguridad:** solo usuarios autenticados pueden acceder.
- **Rendimiento:** respuesta rápida en el análisis.
- **Disponibilidad:** orientado a operación continua.
- **Extensibilidad:** fácil de ampliar (nuevas clases/modelos).

---

## 🗂️ Estructura del proyecto (referencia)
> Nota: si tienes dataset grande, lo ideal es **NO subirlo al repo** (o usar Git LFS).

```bash
.
├─ banana-gpu.ipynb
├─ requirements.txt              # (si existe)
├─ train/                        # (opcional / dataset)
├─ test/                         # (opcional / dataset)
├─ val/                          # (opcional / dataset)
└─ ...

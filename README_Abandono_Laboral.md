
# 📊 Proyecto: Análisis Estadístico del Abandono Laboral

## 👥 Equipo y Roles
- **Director del Proyecto:** Mateo Beltramone  
- **Ingeniero de Datos:** Gonzalo Ezequiel Luna  
- **Científica de Datos:** Paola Navarro  
- **Revisor Ético:** Mateo Beltramo  

---

## 🎯 Objetivo
Realizar un estudio estadístico sobre los factores que influyen en el abandono de entornos laborales, con énfasis en:  
- Limpieza y preparación de datos.  
- Análisis exploratorio con visualizaciones claras.  
- Identificación de patrones e insights relevantes.  
- Revisión ética para evitar sesgos en las conclusiones.  

---

## 🛠️ Herramientas
- **Google Colab:** para análisis y visualización.  
- **GitHub:** control de versiones, issues, proyectos y documentación.  

---

## 🔄 Flujo de trabajo (Sprint 1)
### Gonzalo (Ingeniero de Datos)
- Unificar columnas de sexo y estado civil.  
- Controlar unidades de las variables.  
- Eliminar variables innecesarias: `empleado`, `nivel_laboral`, `mayor_de_edad`, `conciliación`, `años_con_manager_actual`, las dos de `departamentos`, y `puesto`.  

### Paola (Científica de Datos) & Mateo Beltramone (Director)
- Generar gráficos exploratorios (histogramas, barras, boxplots, correlaciones).  
- Redactar explicaciones asociadas a cada visualización.  

### Mateo Beltramo (Revisor Ético)
- Revisar resultados preliminares con enfoque en variables sensibles (`sexo`, `edad`, `estado_civil`).  
- Identificar sesgos potenciales y documentar limitaciones del dataset.  

---

## 📁 Estructura de archivos
```
├── data/
│   └── abandono_laboral_limpio.csv   # Dataset limpio (producido por Gonzalo)
├── notebooks/
│   └── EDA_Abandono_Laboral.ipynb    # Notebook para análisis exploratorio (Paola)
├── README.md                         # Este documento
```

---

## ✅ Checklist ético (para cada sprint)
- [ ] Verificar que variables sensibles se utilicen solo para análisis legítimos.  
- [ ] Reportar **tasas (%)** y no solo conteos absolutos.  
- [ ] No inferir causalidad a partir de correlaciones.  
- [ ] Documentar limitaciones del dataset (nulos, cobertura, sesgos de muestreo).  

---

## 🚀 Próximos pasos
1. **Semana 1**  
   - Dataset limpio (Gonzalo).  
   - Primer EDA y gráficos provisionales (Paola + Mateo).  
   - Revisión ética inicial (Mateo Br.).  

2. **Semana 2**  
   - Ajustar visualizaciones con más detalle.  
   - Formular hipótesis de análisis.  
   - Consolidar hallazgos en un informe preliminar.  

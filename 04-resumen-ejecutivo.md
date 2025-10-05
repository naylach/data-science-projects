# RESUMEN EJECUTIVO - ANÁLISIS AVANZADO DE RECOMPRA

## **RESULTADOS PRINCIPALES**

### **Múltiples Targets de Predicción**
- **3 días**: 19.6% de usuarios recompran (ROC AUC: 0.797) 
- **7 días**: 50.9% de usuarios recompran (ROC AUC: 0.792) 
- **14 días**: 73.9% de usuarios recompran (ROC AUC: 0.807) 
- **30 días**: 100.0% de usuarios recompran (ROC AUC: N/A) - no predecible

### **Productos Estratégicos (Mayor Tasa de Reorden)**
1. **Raw Veggie Wrappers** (Deli): 94.1% tasa de reorden
2. **Serenity Ultimate Extrema Overnight Pads** (Personal Care): 93.1%
3. **Orange Energy Shots** (Beverages): 92.3%
4. **Chocolate Love Bar** (Snacks): 92.1%
5. **Soy Powder Infant Formula** (Babies): 91.4%



## **IDENTIFICACIÓN DE OPORTUNIDADES**

### **Oportunidad 1: Mejorar la retención aprovechando la capacidad predictiva**
Los modelos que usamos logran predecir con casi 80% de precisión quiénes van a recomprar dentro de 3 a 14 días.
Sin embargo, solo el 20% recompra en 3 días y el 50% en 7 días. Sabemos con bastante certeza quiénes tienen alta chance de volver a comprar, pero no estamos usando esa información para actuar a tiempo. Si intervenimos rápido (por ejemplo, con recordatorios u ofertas personalizadas), podemos aumentar significativamente la retención temprana.  

### **Oportunidad 2: Potenciar los productos que más fidelizan**
Encontramos 5 productos con más del 90% de tasa de recompra, como Raw Veggie Wrappers o Serenity Pads. Son productos “estrella” que los clientes vuelven a comprar casi siempre, pero representan una parte muy chica del catálogo.Si entendemos qué los hace tan exitosos (precio, calidad, categoría, packaging, etc.), podemos replicar ese patrón en otros productos y aumentar la fidelización general.  

### **Oportunidad 3: Reajustar estrategias por departamento**
Departamentos como Pets, Dairy Eggs y Beverages tienen un rendimiento promedio de recompra superior al 50%, mientras otros (como Deli) tienen algunos productos buenos pero promedios bajos. Estamos invirtiendo esfuerzos en áreas con menor retorno y no priorizando los departamentos más consistentes. Reasignando recursos hacia los departamentos con mejor desempeño promedio, podemos optimizar marketing e inventario para mejorar las ventas recurrentes.  


## 🚀 **PROPUESTAS DE ACCIÓN**

### **Acción 1 (para Oportunidad 1): Activar campañas automáticas para usuarios con alta probabilidad de recompra**
Implementar un sistema que detecte a los usuarios con más de 70% de probabilidad de recompra (según el modelo) y les envíe una oferta o recordatorio personalizado dentro de las 48 horas posteriores a su última compra.  
Beneficio: Aprovechamos la precisión del modelo para intervenir justo a tiempo, antes de que el usuario se desconecte.  

### **Acción 2 (para Oportunidad 2): Escalar el modelo de los “productos estrella”**
Analizar qué tienen en común los 5 productos con mayor fidelidad y usar esa información para diseñar promociones de cross-selling alrededor de ellos y replicar sus características en otros productos del catálogo.  
Beneficio: Aumentamos la recompra y maximizamos el aprendizaje de los casos de éxito reales.  

### **Acción 3 (para Oportunidad 3): Reenfocar inversión en los departamentos más rentables**
Reorientar presupuesto y esfuerzos de marketing hacia los departamentos con mejor rendimiento promedio de recompra, y reducir inversión en los que dependen de pocos productos estrella.    
Beneficio: Mejor uso del presupuesto y mayor impacto en ventas recurrentes. Ejemplo: mover 10% del presupuesto de Deli hacia Beverages durante un mes y medir resultados  

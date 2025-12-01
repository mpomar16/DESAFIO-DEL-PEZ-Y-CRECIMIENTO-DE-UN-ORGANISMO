# 📘 Métodos Numéricos: Euler, Heun y Solución Exacta  
Ejercicios resueltos en Excel

Este repositorio contiene el desarrollo completo de dos problemas de crecimiento modelados con ecuaciones diferenciales.  
Para cada ejercicio se incluye:

- Solución exacta (analítica)  
- Métodos numéricos: **Euler** y **Heun**
- Comparación de resultados y errores relativos %

---

# 🧪 1. Crecimiento de un Organismo

### Resultados finales (t = 400 días)

| Método | Resultado | Error relativo % |
|--------|-----------|------------------|
| Exacto | 299.32565 | – |
| Euler | 299.67733 | 0.11756 % |
| Heun  | 299.12878 | 0.06579 % |

# 🐟 2. Crecimiento de un Pez (Modelo de von Bertalanffy)

### Resultados en t = 10 días

| Método | Resultado | Error relativo % |
|--------|-----------|------------------|
| Exacto | 15.58432 | – |
| Euler | 15.62226 | 0.2434 % |
| Heun | 15.54536 | 0.2500 % |

---

# 📄 Conclusiones

- Los métodos de Euler y Heun aproximan correctamente las soluciones exactas.  
- Heun tiende a ser más estable gracias al uso de la pendiente promedio.  
- Euler es más sencillo, pero puede acumular más error según la EDO.  

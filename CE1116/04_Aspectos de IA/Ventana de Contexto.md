---
Fecha de creación: 2026-03-17 15:41
tags:
  - ia
Topic:
  - Aspectos de IA
---


## 📚 Idea/Concepto 

Es la máxima cantidad de tokens que un modelo IA puede procesar en una sola operación. Es un límite que depende de cada modelo. La ventana incluye el prompt del sistema, los documentos adjuntos, el historial y la respuesta generada por el modelo. Cada token adicional que se quiera requiere de un cálculo de relación con todos los tokens precedentes usando el mecanismo de atención.
## 📌 Puntos Claves (Opcional)
- Todo lo que queda fuera de la ventana de contexto es "olvidado"
- La relación entre tokens es de complejidad O(n²)
- No depende de la cantidad de parámetros

## 🔗 Connections
- [[Mecanismo de Atención]]
- [[Alucinaciones]]

## 💡 Personal Insight (Opcional)
- Es clave porque sirve para que nosotros entendamos el rendimiento de las IAs. Siento que ayuda a entender mejor el funcionamiento de un modelo IA.
## 🧾 Recursos (Opcional)
- NotebookLM
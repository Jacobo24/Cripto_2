# Cripto_2: Rainbow Tables Implementation

[Repositorio en GitHub](https://github.com/Jacobo24/Cripto_2)

Este proyecto implementa y analiza **Rainbow Tables** para la recuperación de contraseñas a partir de hashes MD5.

---

## Contenido del repositorio

- `rainbow_tables.ipynb`  
  Notebook interactivo con:
  1. **Teoría Criptográfica Preliminar**: Merkle–Damgård, funciones de reducción, colisiones, trade-off espacio–tiempo.  
  2. **Implementación práctica**:  
     - Funciones modulares (`md5_hash`, `reduction`, `generate_chain`, `generate_table`, `search_hash`).  
     - Pruebas unitarias en Jupyter.  
     - Experimentos de rendimiento con gráficos.  
     - Ejemplo práctico paso a paso.  
  3. **Análisis Crítico y Propuestas de Mejora**: cuantificación de colisiones, comparación de tasas de éxito, uso de salt, extensiones GPU/FPGA.

- `README.md`  
  Guía de uso e instalación.

---

## Requisitos

- Python 3.8 o superior  
- Paquetes Python:
  ```bash
  pip install pandas matplotlib

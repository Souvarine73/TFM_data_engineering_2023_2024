# 🚀 TFM Data Engineering 2023/2024

Bienvenido al repositorio del **Trabajo de Fin de Máster (TFM)** en **Ingeniería de Datos** para el curso **2023/2024**.  
Este proyecto se centra en la **generación**, **procesamiento** y **análisis de datos** mediante una arquitectura de lago de datos con las capas **Bronze**, **Silver** y **Gold**.

---

## 💂️ Estructura del Proyecto

```
📦 TFM_data_engineering_2023_2024
🔹 bronze_customers.ipynb              # Ingestión de datos brutos de clientes (Capa Bronze)
🔹 bronze_transactions.ipynb           # Ingestión de datos brutos de transacciones (Capa Bronze)
🔹 silver_customers_transactions.ipynb # Limpieza y transformación de datos (Capa Silver)
🔹 gold_customers_transactions.ipynb   # Enriquecimiento y consolidación de datos (Capa Gold)
🔹 customers_transactions_generation.ipynb # Generación de datos sintéticos para pruebas
🔹 unit_test_customers.ipynb           # Pruebas unitarias para validación de datos
```

---

## ⚙️ Requisitos

- **Python 3.x** 👉 [Descargar](https://www.python.org/downloads/)
- **Jupyter Notebook** 👉 [Instalar](https://jupyter.org/install)

### 🚩 Configuración del Entorno

```bash
# 1️⃣ Crea un entorno virtual
python3 -m venv venv

# 2️⃣ Activa el entorno virtual
# En Linux/Mac:
source venv/bin/activate
# En Windows:
venv\Scripts\activate

# 3️⃣ Instala las dependencias
pip install -r requirements.txt
```

---

## 🚀 Ejecución del Proyecto

1️⃣ **Generación de Datos**  
   Ejecuta `customers_transactions_generation.ipynb` para crear datos sintéticos de prueba.

2️⃣ **Ingestión de Datos (Capa Bronze)**  
   - `bronze_customers.ipynb`: Ingesta de datos de clientes.  
   - `bronze_transactions.ipynb`: Ingesta de datos de transacciones.

3️⃣ **Transformación de Datos (Capa Silver)**  
   Limpieza y procesamiento en `silver_customers_transactions.ipynb`.

4️⃣ **Enriquecimiento de Datos (Capa Gold)**  
   Consolidación de datos en `gold_customers_transactions.ipynb`.

5️⃣ **Pruebas Unitarias**  
   Valida la calidad de los datos en `unit_test_customers.ipynb`.

---

## 🧪 Pruebas

Para asegurar la integridad de los datos:

```bash
# Ejecuta pruebas unitarias
jupyter notebook unit_test_customers.ipynb
```

---

## 🧱 Contribuciones

¡Las contribuciones son bienvenidas! 🎉  
Si deseas mejorar este proyecto:

- **Fork** del repositorio 📤
- Crea una **rama** para tu funcionalidad 🚀
- Envía un **Pull Request** 🔄

---

## 📄 Licencia

Este proyecto está bajo la **Licencia MIT**. Consulta el archivo `LICENSE` para más información.

---

**Hecho con ❤️ para el TFM de Ingeniería de Datos.**



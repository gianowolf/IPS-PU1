# IPS - Practica con utilitario

Este repositorio contiene la resolución de ejercicios relacionados con señales y sistemas discretos, implementados en **Python** y organizados con **Quarto**. Puedes ejecutar los notebooks localmente o visualizar el informe en línea.

---

## **Requisitos previos**

Asegúrate de tener instalado lo siguiente:

- **Python** (>=3.8)
- **Quarto** (>=1.6)
- Un editor de texto como **VSCode** con la extensión **Jupyter**
- **pip** para gestionar las dependencias de Python

---

## **1. Clonar el repositorio**

Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/gianowolf/IPS-PU1.git
cd IPS-PU1
```

---

## **2. Crear el entorno virtual**

Crea un entorno virtual y activa el entorno:

```bash
# Crear entorno virtual
python3 -m venv venv

# Activar el entorno
# En Linux/Mac
source venv/bin/activate
# En Windows
venv\Scripts\activate
```

---

## **3. Instalar dependencias**

Instala las dependencias necesarias:

```bash
pip install -r requirements.txt
```

---

## **4. Ejecutar los notebooks localmente**

### **En VSCode:**

1. Abre el repositorio en **VSCode**.
2. Instala la extensión **Jupyter** para ejecutar notebooks.
3. Navega a la carpeta `notebooks/ejercicio1` o `notebooks/ejercicio2`.
4. Abre cualquier archivo `.ipynb` y ejecuta las celdas.

### **Desde Quarto:**

Si prefieres usar Quarto para renderizar los notebooks como un sitio web:

1. Renderiza el proyecto localmente:

   ```bash
   quarto render
   ```

2. Previsualiza el sitio:

   ```bash
   quarto preview
   ```

3. Abre el navegador en [http://localhost:4200](http://localhost:4200) para ver el sitio completo.

---

## **5. Ejecutar los notebooks en línea**

Si no quieres configurarlo localmente, puedes ejecutar los notebooks en línea con **Binder**:

[![Abrir en Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gianowolf/IPS-PU1/HEAD?labpath=index.qmd)

---

## **Estructura del proyecto**

```bash
.
├── index.qmd              # Página principal del proyecto
├── about.qmd              # Información adicional
├── notebooks/             # Contiene los ejercicios resueltos
│   ├── ejercicio1/        # Ejercicio 1: Señales y Sistemas
│   │   ├── 01_x_input.qmd
│   │   ├── 02_h_system.qmd
│   │   ├── 03_h_systems_num.qmd
│   │   ├── 04_y_output.qmd
│   │   └── data/          # Archivos CSV y audio
│   ├── ejercicio2/        # Ejercicio 2: Respuesta Impulsional del Canal
│   │   ├── 01_h_system.qmd
│   │   └── data/          # Archivos CSV y audio
├── requirements.txt       # Dependencias Python
├── _quarto.yml            # Configuración de Quarto
├── styles.css             # Estilos CSS personalizados
├── README.md              # Este archivo
└── venv/                  # Entorno virtual de Python
```

---

## **6. Recursos adicionales**

- **Quarto Documentation**: [https://quarto.org/](https://quarto.org/)
- **Jupyter Notebooks**: [https://jupyter.org/](https://jupyter.org/)
- **Binder**: [https://mybinder.org/](https://mybinder.org/)
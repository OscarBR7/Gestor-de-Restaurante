# Sistema de Facturación para Restaurante

**Sistema de Facturación - Restaurante** es una aplicación de escritorio desarrollada en **Python** utilizando la librería **Tkinter**, diseñada para facilitar el registro de pedidos, cálculo de totales, generación de recibos y administración de costos dentro de un entorno gráfico intuitivo.

---

## Funcionalidades principales

- Selección de **comidas, bebidas y postres** mediante casillas de verificación.  
- Cálculo automático de subtotales, impuestos y total general.  
- **Calculadora integrada** en la interfaz.  
- Generación de **recibos personalizados** con número de orden y fecha/hora.  
- Opción de **guardar el recibo** en un archivo `.txt`.  
- Función de **reset** para limpiar todos los campos y comenzar un nuevo pedido.  
- Interfaz completamente gráfica y personalizable desarrollada con **Tkinter**.

---

## Tecnologías utilizadas

| Tecnología | Descripción |
|-------------|-------------|
| **Python 3.x** | Lenguaje principal del proyecto. |
| **Tkinter** | Librería estándar para interfaces gráficas en Python. |
| **Datetime** | Generación automática de fecha y hora en los recibos. |
| **Random** | Creación de identificadores únicos de recibos. |

---


## Instalación y ejecución

### Clonar el repositorio
```bash
git clone https://github.com/OscarBR7/Gestor-de-Restaurante.git
cd RestauranteApp
```

### Crear y activar entorno virtual
```bash
python -m venv venv
.env\Scriptsctivate   # En Windows
source venv/bin/activate  # En Linux/Mac
```

### Ejecutar el programa
```bash
python mi_restaurante.py
```

---

## Interfaz de usuario

- **Panel izquierdo:** categorías de productos (comidas, bebidas, postres).  
- **Panel derecho:** área de recibo, botones de acción y calculadora.  
- **Panel inferior:** muestra los costos desglosados (subtotal, impuestos, total).

---

## Autor

Oscar Briones  

# 🧮 Operaciones Matriciales con TensorFlow.js

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)  
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-3.18.0-orange)  
![Web](https://img.shields.io/badge/Plataforma-Web-brightgreen)

Aplicación web que realiza suma y multiplicación de matrices usando TensorFlow.js con matrices generadas aleatoriamente.

## 🌟 Características

- 🎲 **Generación aleatoria de matrices** (valores entre 1-20)
- ➕ **Suma de matrices**
- ✖️ **Multiplicación de matrices**
- 🖥️ **Interfaz web interactiva**
- ⚡ **Procesamiento en el cliente** (no se necesita servidor)

## 📦 Clonar el proyecto

```bash
git clone https://github.com/Alexis217/OperacionesMatricesTensorflow.git
```

## 🚀 Inicio Rápido

1. **Con la extension Live Server** de Visual Studio Code
2. **Abre** el archivo en cualquier navegador moderno
3. **Si no la tienes instalada** busca en VS Code en la sección "Extensions" y instala "Live Server"
4. **No requiere instalación de tenserflow** - TensorFlow.js se carga desde un CDN

## 🛠️ Cómo Usar

1. Establece las dimensiones de las matrices usando los campos de entrada
2. Haz clic en **"Generar Matrices Aleatorias"** para crear las matrices
3. Realiza operaciones:
   - Haz clic en **"Sumar Matrices"** para la suma
   - Haz clic en **"Multiplicar Matrices"** para la multiplicación

## 📊 Detalles Técnicos

- Usa `tf.randomUniform()` para generar matrices
- Operaciones matriciales:
  - Suma: `tf.add()`
  - Multiplicación: `tf.matMul()`
- Gestión automática de memoria con `dispose()`

## 🌐 Compatibilidad

Funciona en todos los navegadores modernos:

- Chrome ✔️
- Firefox ✔️
- Edge ✔️
- Safari ✔️

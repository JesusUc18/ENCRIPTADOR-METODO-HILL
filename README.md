# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Maestro: Jorge Javier Pedroza Romero
## Alumno: Jesús Omar Uc Domínguez
## Actividad #21 Cifrado Hill

---

# 🔐 Encriptador con Método Hill (2×2)

Proyecto desarrollado para la materia **Fundamentos de Álgebra**, donde se implementa el **Cifrado Hill 2×2** completamente en **HTML, CSS y JavaScript**, permitiendo **encriptar y desencriptar** mensajes usando una matriz clave ingresada por el usuario.

Este programa transforma texto a números (A=0…Z=25), aplica multiplicación matricial módulo 26 y muestra cada paso de forma visual.

---

## 📌 Características

- Encriptación usando **Cifrado Hill 2×2**.
- Desencriptación automática usando la **matriz inversa módulo 26**.
- Límite de **30 caracteres** para el mensaje.
- Visualización en tiempo real de la **matriz del mensaje**.
- Interfaz moderna, animada y responsive.
- Validación de:
  - Entrada vacía
  - Matriz clave inválida
  - Determinante = 0 (no invertible)
  - Longitud impar en desencriptado

---

## 🧮 Cómo funciona el cifrado Hill

1. Convierte cada letra en un número del 0 al 25.
2. Agrupa el mensaje en pares → vectores 2×1.
3. Multiplica cada vector por la matriz clave 2×2.
4. Aplica módulo 26.
5. Convierte los resultados a letras.

Para desencriptar:

1. Se calcula el **determinante**.
2. Se halla su **inverso multiplicativo mod 26**.
3. Se obtiene la **matriz inversa mod 26**.
4. Se multiplica por los pares del mensaje encriptado.
5. Se convierte de nuevo a texto.

---

## 📁 Estructura del proyecto

```
📦 Encriptador-Método-Hill
 ├── index.html     # Interfaz principal
 ├── script.js      # Lógica del cifrado/desencriptado Hill
 └── style.css      # Estilos y animaciones
```

---

## 🚀 Cómo usar

### 1. Encriptar
1. Escribe un mensaje (solo letras A-Z).
2. Ingresa una matriz clave 2×2 válida.
3. Da clic en **Encriptar**.
4. El resultado aparece en la caja inferior.

### 2. Desencriptar
1. Pega el mensaje encriptado.
2. Usa la misma matriz clave.
3. Da clic en **Desencriptar**.
4. Obtendrás el texto original.

---

## 🧷 Ejemplo rápido

Mensaje:
HOLA

Matriz clave:
```
[ 3  3 ]
[ 2  5 ]
```
Encriptado:
LFDP

---

## 🎨 Tecnologías utilizadas

- HTML5  
- CSS3  
- JavaScript  

---



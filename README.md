# Proyecto de Katas - FizzBuzz y Tamagotchi

Este repositorio contiene dos soluciones de katas en Java: **FizzBuzz** y **Tamagotchi**. Las soluciones están documentadas y listas para ser ejecutadas.

## Descripción de los Katas

### **1. FizzBuzz**
Este ejercicio imprime los números del 1 al 100 con las siguientes reglas:
- Si el número es divisible por 3, imprime "Fizz".
- Si el número es divisible por 5, imprime "Buzz".
- Si el número es divisible por ambos, imprime "FizzBuzz".
- Si el número no es divisible por 3 ni por 5, imprime el número mismo.

**Instrucciones para ejecutar FizzBuzz:**
1. Ejecuta el archivo `FizzBuzz.java`.
2. Verás los números del 1 al 100 impresos en consola, siguiendo las reglas mencionadas.

### **2. Tamagotchi**
Este ejercicio simula el comportamiento de un Tamagotchi. El Tamagotchi tiene tres atributos: hambre, energía y humor, cada uno con un valor inicial de `4`. Los métodos disponibles son:
- **jugar**: Jugar aumenta el hambre y el humor, y reduce la energía.
- **comer**: Comer reduce el hambre y la energía.
- **dormir**: Dormir aumenta la energía.

El Tamagotchi responde con diferentes emociones según el estado de estos atributos:
- `:-)` cuando el humor es superior a 8.
- `(-_-)` cuando la energía es inferior a 3.
- `(-_-) zZZ` cuando la energía es 0 o se le ordena dormir.
- `ఠ_ఠ` cuando el humor es inferior a 2.
- `:-|` en cualquier otro caso.

**Instrucciones para ejecutar Tamagotchi:**
1. Ejecuta el archivo `Tamagotchi.java`.
2. Llama a los métodos `jugar()`, `comer()` y `dormir()` para observar cómo el Tamagotchi responde a cada acción.

## Instrucciones para Clonar el Repositorio

1. Abre Eclipse.
2. Ve a **File** > **Import** > **Git** > **Projects from Git**.
3. Selecciona **Clone URI** y pega la URL de este repositorio.
4. Sigue los pasos para importar el proyecto a Eclipse.

## Licencia

Este proyecto es de uso académico y no tiene fines comerciales.

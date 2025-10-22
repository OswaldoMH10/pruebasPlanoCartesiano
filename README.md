# Pruebas - Plano Cartesiano Interactivo

## 1. Prueba Unitaria: Validación de Coordenadas

**Descripción:** 
En el apartado de dibujar triángulo se pueden ingresar tres coordenadas para que se dibuje un triángulo, se hará la prueba con diferentes parámetros, ya sea que el separador sea un punto y coma (;), se utilicen letras y números enteros y decimales.

**Cubrimiento:**
- Coordenadas con números enteros y decimales
- Formatos incorrectos (caracteres no numéricos, separadores inválidos)

**Resultado esperado:**
El sistema debe aceptar coordenadas válidas y rechazar las inválidas con mensajes de error apropiados.

## 2. Prueba de Integración: Dibujar una figura completa y que se registren las coordenadas

**Descripción:** 
Se dibujará una figura geométrica irregular (pentágono) utilizando el Snap en ON, una vez dibujado se revisará que se registren las coordenadas en el lateral derecho.

**Flujo probado:**
1. Ingreso de 5 coordenadas con ayuda del mouse
2. Verificación de que los puntos se agregaron a la lista
3. Visualización de que la figura se renderizó en el canvas

**Resultado esperado:** 
El pentágono debe aparecer correctamente en el plano cartesiano y los puntos deben listarse en el lateral correspondiente.

## 3. Prueba de Rendimiento: Múltiples puntos simultáneos alrededor del plano

**Descripción:** 
Se dibujará diferentes puntos alrededor del plano tratado de hacer varios trazos que llenen la pantalla verificando que no se trabe el programa.

**Escenario probado:**
- Dibujo de mútiples puntos con coordenadas aleatorias
- Verificación de que todos los trazos se rendericen sin retrasos

**Resultado esperado:** 
El sistema debe mantener un rendimiento aceptable y mostrar todos los puntos y trazos sin errores de renderizado.

## Métricas de Calidad

- **Tiempo de respuesta:** Sin retrasos de rendereizado
- **Estabilidad:** Sin crashes con entradas válidas

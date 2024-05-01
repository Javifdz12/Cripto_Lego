# Cripto_Lego

El cifrado César es uno de los métodos de cifrado más antiguos y simples conocidos, y forma parte de la categoría de cifrados de sustitución monoalfabética. En este tipo de cifrado, cada letra del texto original (llamado texto plano) es sustituida por otra letra que se encuentra un número determinado de posiciones más adelante en el alfabeto. Este número de posiciones se conoce como el "desplazamiento" o "clave". El cifrado César debe su nombre a Julio César, quien, según documentan algunas fuentes históricas, lo usaba para comunicarse con sus generales sin el riesgo de que sus mensajes fueran fácilmente comprendidos en caso de interceptación.

En la práctica que aquí describimos, se utiliza una técnica creativa e interactiva para aplicar el cifrado César mediante el uso de imágenes de piezas de LEGO de diferentes colores. Cada color representa un desplazamiento específico en el alfabeto. Por ejemplo, una pieza roja podría representar un desplazamiento de tres posiciones (A->D, B->E, C->F...), similar al uso original del cifrado por César, mientras que una pieza azul podría representar cinco posiciones (A->F, B->G, C->H...). Este método no solo hace que el aprendizaje del cifrado sea más visual y práctico, sino que también permite una fácil personalización del cifrado y descifrado, ya que los usuarios pueden elegir combinaciones de colores para crear distintos niveles de complejidad en sus mensajes codificados.

## Pasos a seguir:

1. Asignar un valor a cada color.
2. Crear función para en primer lugar extraer colores predominantes de una imagen utilizando Opencv y en segundo lugar sumar los valores asociados a cada uno de los colores identificados para definir desplazamiento.
3. Crear función que utilice cifrado césar para cifrar mensajes.
4. Crear función para descifrar mensaje cifrados con el cifrado césar.
5. Configurar interfaz de usuario interactiva con gradio para que usuario pueda:
   - Elegir entre 2 modos (cifrar y descifrar).
   - Cargar imágenes.
   - Escribir mensajes
     
   Todo esto para que la interfaz muestre el mensaje cifrado o descifrado (utilizando cifrado césar) en función del modo, a partir del desplazamiento determinado por los colores de la imagen.

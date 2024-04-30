# Cripto_Lego

En la siguiente práctica se utilizan imágenes de piezas lego de distintos colores para cifrar y descifrar mensajes mediante cifrado césar.

El cifrado César es un tipo de cifrado por sustitución en el que cada letra del texto plano es reemplazada por otra que se encuentra un número fijo de posiciones adelante en el alfabeto. Nombrado por Julio César, quien utilizaba este método para enviar mensajes codificados a sus generales.
Considerando un desplazamiento de 3 posiciones, la A será la D, la B será la E, la C será la F... Por tanto el mensaje 'hola' será 'krod'.

## Pasos a seguir:

1. Asignar un valor a cada color.
2. Crear función para en primer lugar extraer colores predominantes de una imagen utilizando Opencv y en segundo lugar sumar los valores asociados a cada uno de los colores identificados para definir desplazamiento.
3. Crear función que utilice cifrado césar para cifrar mensajes.
4. Crear función para descifrar mensaje cifrados con el cifrado césar.
5. Configurar interfaz de usuario interactiva con gradio para que usuario pueda:
   - Elegir entre 2 modos (cifrar y descifrar).
   - Cargar imágenes.
   - Escribir mensajes
     
   Todo esto para que la interfaz muestre el mensaje cifrado o descifrado (utilizando cifrado césar) en función del modo, a partir del desplazamiento determinado por los coleres de la imagen.

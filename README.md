# Challenge-ONE-Sprint-01
Construcción de un encriptador de texto con Javascript

<a href="https://aristobulo99.github.io/Challenge-ONE-Sprint-01/">Visualiza mi repositorio</a>

El problema para este reto fue el desarrollo de una página de encriptación y desencriptación de texto.
Las "llaves" de encriptación que utilizaremos son las siguientes:

La letra "e" es convertida para "enter"
La letra "i" es convertida para "imes"
La letra "a" es convertida para "ai"
La letra "o" es convertida para "ober"
La letra "u" es convertida para "ufat"

Para realizar esto se utilizó un ciclo for que permita recorre posición por posición la frase que se desea encriptar y mediante condiciones se busca la letra que se desea convertir y se concatena la frase encriptada

Para la desencripción se procedió con un primer ciclo que recorra un arreglo que contiene la frases de las letras encriptadas ["enter", "imes", "ai", "ober", "ufat"]
Posteriormente se realiza un ciclo dentro del primer ciclo que recorre la frase encriptado ejemplo: "hoberlai". Luego por posición se realiza la concatenación de una frase de la longitud de tamaño de la frase seleccionada del primer ciclo es decir:

  ciclo 1 frase "enter" longitud de 5
      ciclo 2 concatenacion de longitud 5 "h"+"o"+"b"+"e"+"r" 

Posteriormente con una condición preguntamos si la frase concatenada es igual a la frase posicionada del arreglo si esto se cumple la letra se concatena a una variable que contiene el texto
Si la frase concatenada no se cumple la letra de la posición en la que este del ciclo 2 se asigna a una variable que contiene el texto concatenado

Para finalizar al terminar el ciclo 2 se actualiza la frase con la nueva frase.
Bajo a esta premisa se realiza el proceso de encripcion y desencripcion, además las herramientas utilizadas para esto fue HTML, CSS y JavaScript. Para la utilización del sitio solo es necesario ingresar la frase sin letras mayúsculas y acentos
 

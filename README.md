# Sintetizador de Tonos Puros

Aplicación web interactiva para generar tonos puros, visualizar su forma de onda en el dominio del tiempo y construir señales complejas mediante la suma de sinusoides.

## Funcionalidades

- Generación de tonos puros (sinusoides) con frecuencia e amplitud ajustables
- Reproducción de audio en tiempo real directamente en el navegador
- Visualización de la forma de onda A(t) vs t de cada tono individualmente
- Composición de una señal compleja sumando los tonos seleccionados
- Visualización de la señal resultante superpuesta a las componentes individuales
- Añadir y eliminar tonos dinámicamente

## Uso

1. Abre `index.html` en cualquier navegador moderno
2. Ajusta la frecuencia (20–2000 Hz) y la amplitud de cada tono con los sliders
3. Pulsa ▶ para escuchar un tono individual
4. Marca el checkbox de los tonos que quieras incluir en la señal compleja
5. Pulsa "Reproducir señal compleja" para escuchar la suma

## Tecnología

HTML, CSS y JavaScript puro. Sin dependencias ni instalación necesaria. Utiliza la Web Audio API del navegador para la síntesis y reproducción de audio.

## Concepto

Cualquier señal periódica puede descomponerse en suma de sinusoides (teorema de Fourier). Esta herramienta ilustra el proceso inverso: partir de sinusoides simples y construir formas de onda complejas por superposición.

---
date: '2018-06-14'
title: "Visualizando... la Liga (estadísticas individuales)"
tags: ["futbol", "dataviz"]
---

Recordemos que **[en la primera parte de "Visualizando… la Liga"](/posts/20180524_vis_laliga)** mostrábamos por equipos la relación partidos-goles a favor, aprovechando el ejemplo para insertar imágenes en un gráfico de R.  

![](https://78.media.tumblr.com/83c7f152d79e0a19d87b5b896c80b934/tumblr_inline_p96l71knmR1qemyzq_1280.png)

## En esta nueva entrega, nos centraremos en las estadísticas individuales de los jugadores.  

Para la visualización, se usará R y los paquetes `ggplot2`, y `ggrepel`. Además de representar la nube de puntos, se mostrarán
los nombres de los 10 jugadores (alguno más en caso de empate) con mejor relación
entre la estadística seleccionada y el número de partidos jugados, y que además
hayan disputado un mínimo de 5 partidos.

## **Goles**

![](https://78.media.tumblr.com/9951cf1ce6bc01a4d448deb57243b248/tumblr_inline_pa61exJbb01qemyzq_1280.png)

Messi destaca claramente como pichichi de la competición, seguido por Cristiano Ronaldo y Luis Suárez.

Entre los jugadores con muchos goles y pocos partidos, destacan Bakambu (que salió del Villarreal en el mercado invernal con destino a China) y Sanabria (lesionado entre las jornadas 14 y 31).

-------

## **Asistencias**

![](https://78.media.tumblr.com/c798f93642e5c788e6f57b0965635773/tumblr_inline_pa61jgBORE1qemyzq_1280.png)

El triple empate a asistencias se produce entre los barcelonistas Luis Suárez y Messi y el jugador del Villarreal Pablo Fornals. Entre los más asistentes destaca la presencia de un defensa: José Ángel, lateral del Eibar.

-------

## **Tiros**

![](https://78.media.tumblr.com/7bdc6890d5ef64d31a25e1ddc930cd49/tumblr_inline_pa61jlHzaM1qemyzq_1280.png)

Los más tiradores de la Liga son, en su mayoría, delanteros centro con gran instinto goleador.

-------

## **Tiros a puerta**

![](https://78.media.tumblr.com/97935354ca321860f6fdf84048a490ba/tumblr_inline_pa61jppLgc1qemyzq_1280.png)

Pero si analizamos la efectividad de los tiros, vemos que desaparecen del top 10 jugadores como Calleri, Rodrigo, Willian José y Raúl García para dar entrada a Griezmann, Stuani, Ben Yedder y Coutinho.

-------

## **Balones robados**

![](https://78.media.tumblr.com/efeb3c9b922915d43ffb2274e5ab36af/tumblr_inline_pa61jvv4j21qemyzq_1280.png)

En esta categoría destacan los mediocentros defensivos y laterales, liderados por Saúl Ñíguez y Luisinho.

-------

## **Faltas recibidas**

![](https://78.media.tumblr.com/9787e79243ccab874738050e12490756/tumblr_inline_pa61obdKRx1qemyzq_1280.png)

Entre los jugadores con más técnica y regate sorprende la presencia de Casemiro y Manu García, dos centrocampistas de corte defensivo que saben esconder muy bien el balón.

-------

## **Faltas cometidas**

![](https://78.media.tumblr.com/aea60bd305e1ae5cab7b9bc5854cdafe/tumblr_inline_pa61oetR9v1qemyzq_1280.png)

Entre los más faltones de la Liga se alternan atacantes y defensores, sorprendiendo especialmente el contraste de edades: Rodri y Adrián Diéguez nacieron en 1996, y Peñaranda en 1997, mientras que cinco jugadores del top 10 son ya treintañeros: Iturra (33), Stuani (31), Rául García (31), Víctor Sánchez (30), Pina (30).

-------

## **Centros precisos**

![](https://78.media.tumblr.com/21524e24a963a6ed8170f13381eed77f/tumblr_inline_pa61oqo7Xo1qemyzq_1280.png)

Un centro preciso se define como aquel que llega dentro del área a un compañero. Los jugadores destacados en esta categoría son especialistas a balón parado que, además, no tienen mucha competencia en sus equipos: Granell, Parejo, Kroos, Lucas Pérez…

------- 

## **Tiros bloqueados**

![](https://78.media.tumblr.com/98483d5912888450cf49ff593679630d/tumblr_inline_pa61ovULKI1qemyzq_1280.png)

Acabamos esta sección con tiros bloqueados, protagonizada por valerosos defensas centrales que se interponen entre su portería y un delantero.

-------
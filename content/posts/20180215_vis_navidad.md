+++
title = "Visualizando... la lotería de Navidad"
description = ""
tags = ["visualizando"]
date = "2018-02-15"
+++

Bienvenidos a la primera publicación de este blog. En la sección “Visualizando... ”, analizaremos gráficamente algún contenido interesante, buscando comunicar de forma clara y concisa. Comenzaremos esta sección con una interpretación de la lotería de Navidad de 2017.

![image](https://78.media.tumblr.com/92dc5054897ebe4ecf4a5064c788ff74/tumblr_inline_pah2bmZBSi1qemyzq_1280.jpg)

**Fuente de los datos**: Para empezar, obtener los datos de números premiados suponía un pequeño reto, ya que el [listado oficial](https://www.loteriasyapuestas.es/f/loterias/documentos/Loter%C3%ADa%20Nacional/listas%20de%20premios/SM_LISTAOFICIAL.A2017.S102.pdf) deja mucho que desear desde el punto de vista analítico. Tras una búsqueda por la web, [esta lista de pedreas](http://www.laloterianavidad.com/pedrea/completa.html) parecía ser la más útil para el proyecto. Tras pasar fugazmente por Excel para dar un formato amigable a los datos, llegamos a `R`, donde se han realizado todos los gráficos con la ayuda de `ggplot2`. Del análisis se han excluido los reintegros, ya que no aparecen en la lista original.

En primer lugar, analicemos la distribución de los premios, así como la cuantía de los mismos. Se observan todos los números premiados, entre los que destacan el gordo (71198), el segundo premio (51244), el tercero (06914), y los premios cuartos (13378-61207) y quintos (00580-03278-05431-18065-22253-24982-37872-58808). El diámetro de los puntos es proporcional al premio recibido.  

![image](https://78.media.tumblr.com/7342c5ce6ec4939952573977f15b580e/tumblr_inline_pah2bmDZqc1qemyzq_1280.png)

Observemos ahora la distribución del número de premios en función de la terminación del número.  

![image](https://78.media.tumblr.com/89d68f7f6b2a6b0568fad5ccc65e0b19/tumblr_inline_pah2bn2HNL1qemyzq_1280.png)

Y si en vez del número de premios nos fijamos en el **dinero ganado por terminación**, podemos observar lo siguiente:  

![image](https://78.media.tumblr.com/7a4975cc4db5894a8a51b5ce01973209/tumblr_inline_pah2bnt5EK1qemyzq_1280.png)

El primer premio hace que el número 8 tenga el protagonismo, mientras que el número 4 es el segundo más destacado debido al segundo y tercer premio, ambos con esta misma terminación.

Imaginemos ahora que un excéntrico millonario gastase todos sus ahorros en comprar un décimo de cada número que tenga una determinada terminación. En ese caso, su fortuna se vería reducida (de media) en más de 1.900.000€.  

![image](https://78.media.tumblr.com/f04b31202a6437eea5bb98c3cd82e60f/tumblr_inline_pah2boOCfL1qemyzq_1280.png)

“**La lotería es el impuesto de los necios**”, y pese a ello seguiremos picando, año tras año. A la vista está que no seremos ricos, pero al menos... tendremos salud.
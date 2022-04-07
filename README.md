# DE_challenge

.-  Este repositorio contiene el resultado final con la solución para el challenge de DataEngineer. Traido desde la rama dev luego del desarrollo.

.- Además cuenta con jupyter nootebook que contiene la solución en lenguaje Python y con los pasos requeridos para obtener la información solicitada. 

.- Finalmente cuenta con el archivo .zip utilizado para desarrollar el challenge.



# Exploración de la data

.- Tras observación y análisis de la data ( no incluido en la solución ) se determinó lo siguiente:
  - La data no contiene la estructura descrita en la documentación disponible en el sitio de Tweeter:
     * screen_name --> nombre del usuario que emite el tweet ( campo que permite obtener directamente el nombre del ususario y así omitir inferir dicho valor ).
     * retweet_status --> información que permite obtener toda la data respecto a un tweet cuando este es un retweet.
     * tag entities --> tampoco se encontraba el tag que hacer referencia a los entities de un tweet, desde donde es posible obtener el Hashtag object para extraer los hashtag utilizados en un tweet y así evitar el paso de inferir, que fue necesario para desarrollar la solución.

# LDM-Tarea-XPath-AngelLuis

Reto 1
/bibliotecaTecnica/recurso selecciona todos los nodos recurso bajo la raíz
[categoria='CSS' and disponible='true'] filtra recursos donde la categoría es CSS y disponible es true
/titulo/string() extrae el texto del elemento título

Reto 2

/bibliotecaTecnica/recurso selecciona todos los recursos
[not(@formato!="PDF")] niega que el formato sea diferente de PDF
/@id/string() extrae el valor del atributo id

Reto 3

/bibliotecaTecnica/recurso[anio > 2015] selecciona recursos con año mayor a 2015
/autor[1] de esos recursos, toma solo el primer elemento autor
/string()  extrae el texto del autor

Reto 4

/bibliotecaTecnica/recurso selecciona todos los recursos
[(categoria='XPath' or categoria='XSLT') and nivel=5] filtra la categoría XPath O XSLT, Y nivel igual a 5
/titulo/string() extrae el título

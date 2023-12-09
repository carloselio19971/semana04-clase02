## SELECTORES SIMPLES

1. Selector de Etiqueta (Recomendado para estilos generales)
2. Selector de Clase (recomendado para usarlo para estilos)
3. Selector de Id (No se recomienda trabajar con estilos, mayormente para javascripts)
4. Selector Universal (aplica para todos los elementos, tiene un uso particular)

## Selecotres compuestos
1. Selector de Descendencia  (aplican a un elementos o  elementos descientes abajo no necesarimenta hijos directos) (Se aplica todos los hijos) y tambien a sus descendiente nietos
2. Selector hijo Directo (Seleciona al elementos o los elemnsos hijos seguidso directamente del padre, a un solo nivel de profundidiadas )
3. Selector de Hermano Siguiente o Adjacente  seleciona al elementos que eal mismo nivel y siguiente (solo a uno)  aplica al elemento que esta al mismo nivel y siguiente al hermano
4. Selecciona Hermanos siguientes Adjacentes (seleciona al elementos que el mismo nivel y siguiente)
5. Selector de anidamiento  
alt +~ (colita de chancho)

## BOX MODEL

1.  El Box Model hace referencia a como se representa el contenido una pagina web, mediante >el uso de cajas rectangulares
1.1 Box-Content (Hacer referencia a la parte interior del box  model, en donde va el contenido)
1.2 Box-Padding (Hace referencia al espacio entre el context-box y el border-box , en otras palabras el espacio entre el contenido y el border de nueva box model)
1.3 Border-Box (Hace referencia a la linea que rodea el contendido de mi box model)
1.4 Marging-Box (Es el espacio que se encuentra afuera del borde de la caja,>representa la distancia con otras cajas o elementos)
1.5 Margin-Negativo Con el margin negativo podemos hacer que elemento se fue mueva hacia fuera de la pantalla de navegador por lo un parte se ocultara
1.6 Colpasado-Margen-Vertical Cuando existe colapsado de margenes verticales, el mayor valor del margen aboserbe al menor.
1.7 Centrado Perfecto Margin: el margin 0 auto nos permite centrar de manera perfecta un elemento de bloque
1.8 El selector universal permite dar estilos a todos los elementos html, su uso particar es para dar la propiedad box-sizing: border-box , para que cuando usemos margin, padding no se vea afectado el tamaño del contenedor.
1.9 El shorthand nos permite dar propiedades de padding en sentido de las manecillas del reloj , (top, left, bottom , right)
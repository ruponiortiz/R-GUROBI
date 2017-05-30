# R-GUROBI
MATERIAL UTIL PARA UTILIZAR TODO EL PODER DE R JUNTO A GUROBI

Dentro de esta carpeta quedaran tutoriales y enlaces de interes para poder utilizar R junto a Gurobi.

Desde Diciembre-2016 está disponible la librería "ompr" (autor @dirkschumacher).
Esta les servirá para escribir PPLs y resolverlos con los solvers disponibles("glpk","symphony","cplex").
(link con instrucciones de uso: https://github.com/dirkschumacher/ompr) 
NOTA: "glpk" funciona pésimo y es solo para problemas lineales.

Si dentro de los solvers libres, ninguno se ajusta a darle respuesta a su problema en particular, dentro del mercado se encuentran disponibles solvers más "potentes" en el sentido de resolver el problema siguiendo algun algoritmo más especializado.


De tenerlo disponible, pueden utilizar Gurobi(link de descarga: http://www.gurobi.com/downloads/download-center).
Para instalarl las librerias necesarias, las instrucciones estan aca: https://www.gurobi.com/documentation/7.0/quickstart_mac/r_installing_the_r_package.html

De momento es necesario instalar un plugin especial para poder usarlo y sus restricciones con R >= R 3.2.1 y Gurobi 6.5.0.
link de instrucciones: https://github.com/ggsdc/ROI.plugin.gurobi

NOTA: cuando no funciona alguna librería, funcion, etc... es posible que existan incompatibilidades entre las versiones de algunas librerías, por lo cual es importante revizar cual es la versión que tienen instalada.

Difundan, compartan y hagan ciencia!

#sciencebitch


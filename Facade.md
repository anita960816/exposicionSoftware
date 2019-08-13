
# Patrones de diseño estructural: Facade
Es un patrón de uso común cuya función es simplificar la comunicación entre una clase y otra clase compleja u otro subsistema de clases.  
  
Suponga que la clase cliente quiere utilizar a la clase objetivo para determinadas operaciones, pero la clase destino es muy compleja, por lo que se crea  un facade (fachada) que simplifique la interfaz de la clase destino adaptándola y simplificándola para un uso concreto.  
  
Además Facade permite el desacoplamiento entre clientes y sistemas complejos y subsitemas, permitiendo crear una interfaz de uso de varios sistemas para un fin concreto mediante una única interfaz.  
  
## Problema y contexto

Se dispone de un sistema complejo que, al ser muy flexible, requiere de la configuración de muchos parámetros para conseguir un fin concreto. Por otro lado, el sistema cliente pretende utilizar parte de la funcionalidad que el primer sistema ofrece pero muchas de las operaciones de configuración son siempre las mismas.  
  
Otro problema que trata de solucionar este patrón es el uso de varias interfaces de subsistemas mediante un único punto de acceso.

## Cuándo es útil usarla?

-   El sistema cliente tiene que acceder a parte de la funcionalidad de un sistema complejo.
-   Hay tareas o configuraciones muy frecuentes y es conveniente simplificar el código de uso.
-   Se necesita hacer que una librería sea más legible.
-   El sistemas clientes tienen que acceder a varias APIs y se quiere simplificar dicho acceso.

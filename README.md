# Proyecto-Computacion-Tolerante-Fallas

# Página web
El programa principal que será subido a Docker es una página web, esta página web es para el equipo universitario de Rugby de la UdeG dicha pagina ayuda al administrador (entrenador) a llevar un cierto control de los jugadores y sus reacciones a los entrenamientos ya que por medio de esta pagina con ayuda de cuestionarios que los atletas contestan antes y después de una sesión el entrenador puede saber cómo están físicamente. 


![image](https://github.com/HSamuelGomezC/Proyecto-Computacion-Tolerante-Fallas/assets/106403018/495bc19c-6960-4abd-9873-080e1e908a9c)

Esta seria la vista principal de la página.

![image](https://github.com/HSamuelGomezC/Proyecto-Computacion-Tolerante-Fallas/assets/106403018/0eb57819-aad4-4dfe-81da-124d41cbc605)

Aquí tenemos lo que seria un formulario para registro que es la parte una parte importante que de este proyecto ya que este formulario tiene implementado un localstorage esto nos ayuda a que si el usuario que se va a registrar por alguna circunstancia no logra enviar el formulario este se guarde con los datos que dejo ya escritos, cabe resaltar que esto será hasta que se de en el botón de enviar, luego de esto esa información ya no estar almacenada en el localstorage.

# Localstorage

localStorage es una propiedad que acceden al objeto Storage y tienen la función de almacenar datos de manera local, localStorage almacena la información de forma indefinida o hasta que se decida limpiar los datos del navegador.

¿Cómo lo usamos en el formulario de registro?
-	Para almacenar los datos usamos una función llamada “setItem(key, value)”
•	Key seria la clave única o el campo.
•	Value sería el valor que se le esta pasando a ese campo

![image](https://github.com/HSamuelGomezC/Proyecto-Computacion-Tolerante-Fallas/assets/106403018/55532109-4fff-416d-9fca-bb1c229e79b2)

 
Esto pasara cada que la siguiente función se active:

# clase03-2bim

## 25 Junio 2025

- Para empezar, al entrar al agregar numero telefonico para un estudiante:

<img width="446" alt="Screenshot 2025-06-25 at 8 07 56 am" src="https://github.com/user-attachments/assets/c7678af3-f5d4-4589-9766-46948dd7e8f2" />


entramos al formulario redirigido esperado de NumeroTelefonicoEstudianteForm, de aqui partimos para todo ya que
apenas entramos, hacemos una solicitud GET para la vista def crear_numero_telefonico_estudiante que recibe como parametros
a request que seria de tipo GET al principio y id del estudiante al que le agregaremos como tal y entraremos a un condicional 
en el que en cualquiera de los casos de la respuesta GET O POST, se creara un formulario con ayuda del form, pero se
creará lleno, en caso de que la solicitud sea GET, se crea un formulario recibiendo a un objeto de tipo estudiante como
clave foranea en un form lleno de los datos de este, de ahi una vez tenemos los datos, cuando los cambiemos la request
se volvera post a traves del <p><input type='submit' value='Agregar'/></p> del crearNumeroTelefonicoEstudiante.html
y de ahi se actualizaran los datos nuevos.


<img width="1920" alt="Screenshot 2025-06-25 at 8 07 46 am" src="https://github.com/user-attachments/assets/5c14026c-e9c2-4a72-bd59-0247567c2cd6" />


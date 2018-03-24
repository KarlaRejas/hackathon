## Retos

### 1. Crear un *styleguide* de Laboratoria con componentes en React

Crea un *styleguide* de componentes para Laboratoria utilizando el nuevo branding. Puedes proponer nuevos elementos o
mejoras a los elementos existentes. En este [link](http://laboratoria.la/) puedes encontrar algunos componentes hechos
con el nuevo branding.  

La propuesta de *styleguide* es libre. Si quieres una referencia, [esta](https://polaris.shopify.com/components/get-started/ ) es la que más nos gusta.

### 2. Crear un app de clima

Crea una app para chequear las condiciones del clima y compararlas com la perceción individual del usuario, puedes usar cualquier API de clima para ayudarte.

La idea es que todos los días muestre cómo será el clima del día y le pregunte al suario cómo siente el clima (percepción), por ejemplo: "tengo frío", "tengo mucho frío", "Me derrito de calor", "Está perfecto", etc. 

La app deberá guardar las respuestas para luego relacionarlas con el pronóstico y decirte cómo se sentirá el usuario ese día. 

### 3. Programa de préstamo de bicis

La municipalidad de San Borja tiene un programa de préstamos de bicicletas (puedes verlo [aquí](http://piap.msb.gob.pe/webbici/viaja-en-bici.html)). 
Luego de haber hecho todo manual por un tiempo, quieren pasar a tener una herramienta digital, que tú propondrás
y desarrollarás para dar mejor y mayor acceso de la cantidad de bicis, las estaciones, los tiempos de préstamos a sus usuarios. Además, buscan que esta herramienta sirva para atraer usuarios al programa y facilitar su inscripción. 

### 4. Eventos

Vamos a crear una web app para organizar eventos considerando:
1. Existen al menos 2 sesiones simultáneas. Por ejemplo, dos speakers en dos lugares diferentes a la misma hora.
2. Hay cupos limitados para los asistentes para cada sesión.
3. Hay un “Admin” que crea los eventos y define la cantidad de cupos para cada sesión.
4. Los usuarios se pueden registrar en los eventos que quieran.
  - No puede registrarse a la misma hora en más de un evento
  - Los cupos se van agotando (o aumentando si alguien cancela su registro).
5. Bonus:
  - Chat general para cada sesión.
  - Ping a asistentes para pedir contacto para networking. El que recibe el ping, acepta o no el pedido.

### 5. Integrarse con un backend

Tenemos un app construida en Ruby on Rails que utiliza una base de datos en Postgres. El app no está completa, por lo que es necesario trabajar en back-end y front-end para tener un app más completa.

Tendrás que clonar este [reposotorio](https://github.com/Laboratoria/hackathon-rails). 

En la rama `master` del repositorio están las instrucciones de cómo instalar ruby, ruby on rails y postgres en tu computador, ya sea Windows o Ubuntu. Sigue las instrucciones y estarás lista. En la rama `main` está el proyecto sobre el cual tendrás que trabajar. 

El app en el que vas a trabajar es un catálogo de productos de una tienda donde existen 2 tipos de usuarios: el administrador del catálogo y los compradores. El administrador del catálogo tiene un acceso privado (login) a varios formularios donde puede agregar, editar, eliminar o actualizar productos. Estos productos pertenecen a distintas categorías. Cada producto tiene su propia descripción, precio, stock e imagen(es). Por otro lado, los compradores podrán ver el catálogo de productos y entrar en el detalle de cada uno.

- Crear un seed de categorias y productos para que el app pueda tener una base de datos más grande y diversa.
- Mantener Materialize como *framework*.
- Trabajar en todas las vistas del app para que sean más amigables y puedan transmitir conexión con la marca a los usuarios.
- Agregar validaciones en los formularios.
- Agregar paginaciones cuando la lista de productos sea mayor a 10 (puedes hacerlo desde el back-end o desde el front-end).
- Agregar *breadcrumbs* (migas de pan) a las vistas.
- Sustituir o crear una vista de productos donde se pueda filtrar por categoría.
- Desplegar el app en Heroku

### 6. Replicar la app de Square POS

Square POS es una de las mejores apps para punto de venta, sin embargo, no tiene aún soporte para latinoamérica.[Esta](https://squareup.com/pos) es la app y [aquí](https://www.youtube.com/watch?v=D3uwIww7flw 
) puedes ver un video de sus principales funciones. La idea es que crees una app parecida pero adaptada a las necesidades de tu país en términos de flujos, monedas e impuestos.

¿Qué funcionalidades debes priorizar?
- Catálogo de productos con precios y stocks.
- Cobros en efectivo y tarjeta de crédito (intenta usar un API).
- Cuadre de caja al final del día.

### 7. "The bible app" o aplicaciones similares

Elige una app del *App Store o Play Store* que tenga muchas descargas pero que su experiencia no sea tan buena. Testéala, re-diséñala e impleménta tu versión mejorada.

### 8. Entrevistas online <L>

Crear una aplicación web que pueda “entrevistar”, de manera remota y autónoma las postulantes a Laboratoria. Cada postulante debe grabar (audio y video) una respuesta para cada pregunta que le haga la app.

#### Requisitos generales
- Las preguntas se hacen una a la vez.
- La respuesta a cada pregunta tiene una duración máxima permitida.
- La postulante puede grabar la respuesta a cada pregunta UNA SOLA VEZ.
- La postulante decide el momento en el que comienza a grabar su respuesta.
- La postulante puede decidir el momento en el que detiene la grabación (si es que el tiempo no ha terminado)
- La app decide el momento en el que se corta la grabación (de acuerdo a la duración predefinida para la respuesta).

#### Material
- Documento con descrpción completa del reto y materiales: [Aquí](https://docs.google.com/document/d/14QQOHYmsyuWyVXSoy4Mrd7J7tuQN0dF1bXaBMXMkYBU/edit#heading=h.up3vvjpkwjgq)

### 9. Distribución de Squads

Como sabes, en Laboratoria redistribuimos los squads en cada sprint, para que vayan conociéndose y potenciándose entre uds.
Aprender en squads nos trae muchos beneficios, sin embargo, generar estos squads cada sprint es una tarea tediosa para las
Training Managers. Creemos que esta distribución de squads puede ser más automática y así le facilitar la vida a las Training
Managers. Así que les pedimos a uds, que nos ayuden a crear esta herramienta que pueda redistribuir los squads cada sprint
basándose en distintas variables.

#### Qué variables tenemos en cuenta

- % tech skills
- % soft skills:
- Comunicación eficaz
- Manejo del tiempo
- Nivel de inglés
- Perfil
- Que no hayan estado en un mismo squad antes

#### Consideraciones

Los squads son de 6 estudiantes, y su distribución debería incluir como mínimo:

- 1 estudiante con nota tech mayor a 70%
- 1 estudiante con comunicación eficaz mayor a 70%
- 1 estudiante con nivel de inglés 2  o 3
- 1 estudiante con nivel de inglés 0 o 1


### Datos adicionales

Los niveles de inglés se miden así:
- 0: Sin conocimientos
- 1: Básico
- 2: Intermedio
- 3: Avanzado

Puedes ver más sobre este reto en este [link](https://docs.google.com/document/d/16kznuB-CJRWJU4ptEYp_5GLuwIP1ZGNfp7hrRtq7YtQ/edit?usp=sharing)

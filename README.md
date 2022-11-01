# Web-dasboard-semillas
Fundacion semillas

# Contexto.

La Fundación Semillas, que ofrece diplomados en sostenibilidad del medio ambiente, desea saber el estado de ánimo sus alumnos, además de querer suministrarles una herramienta de fácil manejo, donde puedan organizar las tareas diarias propuestas por la institución.

Para ello, plantea que se desarrolle una aplicación web con varios dashboard, que muestren indicadores sobre las emociones que un alumno puede llegar a sentir durante el desarrollo de la formación por cada actividad que realizan.

# Requerimientos tecnicos.

-Hacer uso de metodologia scrum.

-Utilizar Git flow.

-Pressentar la vista con indicadores de un alumno especifico.

-Realizar wireframe, mockup y prototipo de la propuesta.

-La página debe ser responsive (mobile, tablet y desktop)

-El producto final debe ser acorde con el manual de marca de la fundacion.

-Debe tener mínimo 5 formas (no iconos), realizadas mediante CSS, diferentes al círculo, cuadrado o rectángulo.

-Todas las graficas deben estar hechas con HTML y CSS.

-DEBE tener al menos 6 animaciones diferentes hechas con CSS.

-La maquetación debe ser 100% en HTML y CSS, asegurando ACCESIBILIDAD.

-No se pueden utilizar frameworks o librerias de ningun tipo o lenguajes de programacion como javascript, python, etc

-Aplicar buenas practicad de codigo.

-Se debe implementar ATOMIC DESIGN.

-El repositorio DEBE tener un README detallado, con capturas de pantalla y documentación del desarrollo (estructura de carpetas, átomos, moléculas…)

-Se debe entregar un prototipo de una aplicacion web que le permite al usuario (estudiante) organizar sus actividades en general con varios dashboard, que muestren indicadores sobre las emociones que un alumno puede llegar a sentir durante el desarrollo de la formación por cada actividad que realizan.

-Realizar una demo para sustentar el proyecto


# Prototipos.

El diseño de los prototipos fue realizado con el manual de imagen suministrado por el cliente: 

https://drive.google.com/drive/folders/1LeFh4-b6gbr-dchM9CjCX2bLmb0a7sOT


Se asignaron tres colores a las mediciones de los dashboard para que fuera mas facil su comprensión, como lo son: rojo (#FB6535), amarillo (#F9B93E) y verde (#1F8D16).
Se creo una sección al principio de la pagina para la version movil y tablet y en el costado derecho debajo del perfil para la versión de escritorio que contiene el listado de los diplomados actuales de la fundación, donde se encuentran los listados de los estudiantes activos para asi brindar comodidad al usuario a la hora de seleccionar el estudiante a evaluar.
La version movil y de tablet contienen menus en la parte inferior siempre visibles para su navegación, mientras que en la version de escritorio es un menu flotante a la derecha.

https://www.figma.com/file/Jvj11uJ3PhRmnovkH3MHAM/Semillas---DASHBOARD?node-id=35%3A214


# Documentacion tecnica.

Entre los requerimientos propuestos por el cliente encontrabamos el uso e implemntacion del Git flow durante el desarrollo del repositorio por lo que de manera interna creamos tanto ramas personales como generales, las cuales nos permitieron realizar avances tanto individuales como cooperativos, a continuacion el git flow implementado:

![image](https://user-images.githubusercontent.com/114700033/199152165-81ba5fa7-c6e2-4722-acfd-e2ee08af0b3b.png)

Asi mismo durante el desarrollo del proyecto se hizo uso del atomic design el cual nos permitio empezar por los elemntos mas pequeños e ir escalando de manera proporcional creando moleculas y organismos, por lo que iniciamos creando el index y las hojas de estilo destinados para esto, cada integrante del equipo se encargo de realizar un atomo, molecula y organismo diferente para que luego de hacer merge los mismos se encontraran a disposicion de quien los necesitara, las carpetas las distribuimos de la siguiente manera:


![image](https://user-images.githubusercontent.com/114700033/199151524-94751197-ec6b-4c42-9e62-da3d95fd3619.png)

![image](https://user-images.githubusercontent.com/114700033/199151681-9ca6c862-916c-4cf0-8345-c4ae926e3380.png)


Un index para las secciones, finalizadas y aprovadas e igualmente, unahoja de estilos para atomos y otra para organismos y elementos en general.

ASPECTOS GENERALES.

![image](https://user-images.githubusercontent.com/114700033/199152556-5933f866-3dcd-440a-a8b7-9466d1f1f664.png)

Para iniciar el proyecto la distribucion de las tareas y los pequeños aspectos fue fundamental,por lo que se decidio englobar los colores y fuentes dentro de variables que fueran mas faciles y rapidas de usar.

Es importante recalcar que se hizo uso de procentajes y medidas estandar en algunos elemntos para que al momento de ser requeridas su manipulacion fuese mucho mas sencilla.

![image](https://user-images.githubusercontent.com/114700033/199152806-483b43ef-87ee-4170-83a4-cb6bed2fe324.png)

FIGURAS E ICONOS.

Las figuras e iconos eran igualmente parte de los requerimientos que el cliente solicito por lo que dentro de su creacion y agrupacion nacieron las caras que darian vida a las emociones dentro del dashboard final, asi mismo otros iconos y figuras dentro del proyecto son:

![image](https://user-images.githubusercontent.com/114700033/199153982-783cba42-1263-4f2c-b190-d123b43e36d2.png)
![image](https://user-images.githubusercontent.com/114700033/199154431-a6bba177-7de0-46e0-b302-768685862069.png)
![image](https://user-images.githubusercontent.com/114700033/199154556-7e0870b0-ce3c-4272-814a-30af6e800300.png)
![image](https://user-images.githubusercontent.com/114700033/199154486-c3245eef-c562-4277-9861-fcca4a7dcee0.png)
Cabe aclarar que lo que se mostro anteriormente fue dise;ado y maqueteado haciendo uso unicamente de CSS y HTML

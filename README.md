## **PRACTICA 3 FUNDAMENTOS DE REACT Y NEXT.JS**

### **CHAPTER-1:** ABOUT REACT AND NEXT.JS

#### ¿QUE ES REACT?

REACT es una biblioteca de JavaScript el cual nos brinda codigo ya hecho por asi decirlo,  que nos permite hacer una pagina web de majera mas sencilla y no tener que hacer todo desde cero.

#### ¿QUE ES NEXT.JS?

Es un fremework o marco de trabajo que se basa en REACT. Proporciona la estructura de trabajo, para la creacion de una pagina web de manera organizada y optimizada.

-------------------------------------------------------------------------------------------------------

### **CHAPTER-2:** RENDERING USER INTERFACES (UI)

#### DOM (DOCUMENT OBJECT MODEL)

El DOM es un termino que usamos para referirnos a como el navegador interpreta nuestro HTML. 
El navegador convierte el HTML en una estructura de objetos organizada que tiene la forma de arbol donde cada etiqueta de nuestro HTML se transforma en un objeto que puede ser manipulado con JavaScript para cambiar lo que vemos y como interactuamos con la pagina y que no sea estatica.

-------------------------------------------------------------------------------------------------------

### **CHAPTER-3:** UPDATING UI WITH JAVASCRIPT

Usando JavaScrip y DOM podemos crear, modificar y eliminar elementos u objetos de la estructura del HTML
lo que nos permite actualizar dinamicamente el contenido de una pagina web.Podemos crea etiquetas html , modificar estilos css y responder eventos del usuario como los clicks.

#### REACT UNA INTERFAZ DE USUARIO DECLARATIVA

Cuando se dice que react es declaratica nos referimos declaramos que queremos que se muestre pero no especificamos paso a paso como la pagina debe modificar o construri el DOM, esto corresponde a la programacion imperativa.
En el codigo de este capitulo usamos programacion imperativa pero como se ve suele ser un poco mas extenso y puede ser cansador especificar como queremos manipular el DOM.
Pero React esta pensado precisamente para eso y no preocuparnos como se va hacer cada cosa en detalle sino solo nos interesa el resultado que queremos obtener.

--------------------------------------------------------------------------------------------------------

### **CHAPTER-4:** GETTING  STARTED WITH REACT

Pare empezar a trabajar con React en nuestro proyecto debemos cargar la libreria principal de React para que sin eso nuestra pagina no puede usar React:

     <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
     <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>

Como React trabaja con JSX que es una extension de sintaxis de JavaScript que permite escribir HTML dentro de de JavaScript, pero como el navegador no entiende eso se convierte el JSX a JavaScript puro mediante el siguiente script:

    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>

Las funcion es que se usan para poder iniciar un proyeto en React son los diguientes:

    const root = ReactDOM.createRoot(domNode); Esto 

indica donde queremos que React empiece a trabajar

    root.render(<h1>Develop. Preview. Ship.</h1>); Y con esto indicas que mostrar dentro de ese espacio

----------------------------------------------------------------------------------------------------------

### **CHAPTER-5:** BUILDING UI WITH COMPONENTS

Uno de los conceptos centrales de React son lo componentes.

#### COMPONENTES

Un componente es como un funcion en JavaScript el cual retorna un elemento de la interfaz de usuario por que combina sintaxis HTML y de JavaScript. Los componentes se usan por que al ser como un bloque de contruccion se puede reutilizar en cualquier parte de codigo y al ser una parte pequeña de todo el codigo permite tener mejor control de cada parte y poder escalar el codigo facilmente y modificar solo un componente si es necesario sin afectar al resto de codigo.

----------------------------------------------------------------------------------------------------------

### **CHAPTER-6:** DISPLAYING DATA WITH PROPS

El segundo cocepto central en React son los props(accesorios o parametros).

#### PROPS

Son como los atributos que se tienen en HTML para pasar alguna informacion adicional al elemento HTML, un drop cumple la misma funcion pero para un componente en React y asi cambiar el comportamiento del componente.Ejemplo: 

    <Header title="React" />.

Para mostrar variables y expresiones de JavaScript en el HTML se hace uso de las llaves {}, por ejemplo:

    <h1>{title}</h1>


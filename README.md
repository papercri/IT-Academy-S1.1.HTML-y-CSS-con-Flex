# Flexbox Responsive Layout

## Descripción

Este proyecto consiste en la creación de un layout responsive utilizando HTML y CSS con Flexbox. La maquetación se adapta a distintos dispositivos: escritorio, tableta y móvil, siguiendo las indicaciones de los wireframes proporcionados.

## Tecnologías utilizadas

- HTML
- CSS (Flexbox, Scss y Media Queries)

## Instrucciones de instalación y ejecución

1. Clonar el repositorio:
   ```sh
   git clone https://github.com/papercri/IT_Academy_S1.1.HTML_y-CSS_con_Flex.git
   ```
2. Acceder al directorio del proyecto:
   ```sh
   cd IT_Academy_S1.1.HTML_y-CSS_con_Flex
   ```
3. Abrir el archivo `index.html` en el navegador.

## Requisitos previos

Para facilitar la resolución de esta práctica, es recomendable tener conocimientos en:

- HTML y CSS
- Flexbox -> [Guía Completa](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- Media Queries -> [Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

## Consideraciones generales

- Evitar establecer un `height` fijo a los elementos para que se adapten dinámicamente al contenido.
- La página no debe mostrar barras de desplazamiento horizontal.
- Evitar redundancias en la declaración de estilos como `display: flex; flex-direction: column` en elementos que ya tienen un comportamiento en bloque por defecto.
- No es necesario especificar `width: 100%` en elementos `div`, ya que ocupan el ancho completo de su contenedor por defecto.

## Estructura del repositorio

El repositorio debe contar con:

- Un archivo `index.html`.
- Un archivo `styles.css`.
- Una carpeta `img/` para almacenar capturas de pantalla.

Cada ejercicio debe estar reflejado en un commit distinto con mensajes descriptivos.

## Features principales

### **Nivel 1**

#### **Ejercicio 1**

- Implementar la maquetación en formato escritorio siguiendo el wireframe proporcionado.
- La capa principal tendrá un ancho máximo de `1200px` (`max-width: 1200px`).

#### **Ejercicio 2**

- Adaptar la maquetación para tabletas mediante Media Queries.
- Aplicar cambios en la distribución y color de algunos elementos según el wireframe.

#### **Ejercicio 3**

- Adaptar la maquetación para móviles.

### **Nivel 2**

#### **Ejercicio 4**

- Modificar el color de fondo de la web dependiendo del ancho del dispositivo (escritorio, tableta y móvil).

**Ejemplo de visualización:**

- **Versión Desktop**  
  ![Versión Desktop](/img/desktop.jpg)

- **Versión Tablet**  
  ![Versión Tablet](/img/tablet.jpg)

- **Versión Mobile**  
  ![Versión Mobile](/img/mobile.jpg)

### **Nivel 3**

#### **Ejercicio 5**

- Utilizar la propiedad `animation` de CSS para que, al hacer `hover` sobre el primer `div`, cambie de tamaño y color.
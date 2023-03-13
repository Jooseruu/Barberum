# Proyecto Barberum 🪒💈
## ¿Porque una Barbería?

Elegir la temática para una página web puede ser un proceso complicado, especialmente si se tiene en cuenta la variedad de opciones disponibles. Después de revisar diferentes opciones, he decidido que una barbería sería una excelente elección para implementar los requisitos que se mencionaron en la asignación.

En primer lugar, una barbería ofrece una amplia variedad de oportunidades para mostrar visualmente los servicios y productos que se ofrecen. Desde los cortes de pelo clásicos hasta los modernos estilos de barba, las barberías son un lugar donde los hombres pueden recibir servicios de alta calidad. Las barberías suelen tener una estética visual muy atractiva y característica, lo que permite la creación de una galería de fotos llamativa y atractiva.

Además, una barbería también puede ser una excelente opción para la implementación de otros requisitos, como un menú desplegable que permita a los visitantes ver las reseñas y comentarios de otros clientes. 


![Rotulo Barber](https://github.com/Jooseruu/Barberum/blob/main/img/rotulo.png)  


## Estructura del proyecto
El proyecto está dividido en tres fases: planificación, maquetación y perfeccionamiento. Durante la fase de planificación, se definieron los requisitos de los archivos HTML, CSS y JPG y se diseñó la estructura del proyecto. Se utilizaron tres tipos de archivos: HTML, CSS y JPG, y se crearon dos tipos de CSS: el CSS global y el CSS particular de cada HTML. El proyecto consta de cuatro archivos HTML, cinco archivos CSS y seis archivos JPG.

Durante la fase de maquetación, surgieron varios problemas, especialmente en el CSS, donde algunas cosas no quedaron como se deseaba. La creación de un diseño responsive resultó especialmente tediosa.

En la fase de perfeccionamiento, se dedicó tiempo a comentar el código y mejorar el aspecto visual de la web. Aunque no se logró una personalización óptima, en cuanto a combinación de colores y otros aspectos.

![HTML-CSS](https://github.com/Jooseruu/Barberum/blob/main/img/CSS.png)  

## Esquema
### Menu General
~~~
El menú esta dotado de 4 opciones cada una con su CSS particular y css general
<link rel="stylesheet" href="globalstyles.css"> <!-- Se vinculan los archivos CSS para aplicar estilos a la página web -->
<link rel="stylesheet" href="0.css">
~~~
### Formulario
~~~
El formulario es muy completo y tiene un diseño muy cuidado consta de varios inputs obligatorios y de varios tipos explicados tanto en el HTML que puedes ver a continuación como en el CSS particular 

      <section class="reservation"> <!-- Se establece un formulario de reserva de cita con un diseño limpio y claro, que utiliza etiquetas "label" para cada campo del formulario y atributos "id" y "name" para cada entrada de usuario. -->
        <h2>Reserva una cita</h2>
        <form>
          <label for="name">Nombre:</label>
          <input type="text" id="name" name="name" required>
          <label for="email">Correo electrónico:</label>
          <input type="email" id="email" name="email" required>
          <label for="phone">Teléfono:</label>
          <input type="tel" id="phone" name="phone" required> <!-- Incluye campos de entrada obligatorios para el nombre, correo electrónico, teléfono, barbero, servicio, fecha y hora. Las opciones predefinidas para los campos "barbero" y "servicio" se presentan en una lista desplegable utilizando el elemento "select" y la etiqueta "option". -->
          <label for="barber">Barbero:</label>
          <select id="barber" name="barber" required>
            <option value="">Selecciona un barbero</option>
            <option value="Juan Pérez">Juan Pérez</option>
            <option value="Pedro Gómez">Pedro Gómez</option>
            <option value="Carlos Martínez">Carlos Martínez</option>
          </select>
          <label for="service">Servicio:</label>
          <select id="service" name="service" required>
            <option value="">Selecciona un servicio</option>
            <option value="Corte de cabello">Corte de cabello</option>
            <option value="Arreglo de barba">Arreglo de barba</option>
            <option value="Teñido de cabello">Teñido de cabello</option>
          </select>
          <label for="date">Fecha:</label>
          <input type="date" id="date" name="date" required>
          <label for="time">Hora:</label>
          <input type="time" id="time" name="time" required>
          <input type="submit" value="Reservar">
        </form>
      </section>
~~~
### Reseñas 
~~~
Podriamos decir que el apartado reseñas es un submenú donde puedes visualizar las reseñas de otros usuarios tiene 2 estados, antes de pulsar y despues de pulsar

 <section class="reviews"><!-- Sección reviews, muestra un boton "toggle-reviews" este botón utiliza un input tipo "Checkbox" y una etiqueta label para activar el cambio de estado de "checkbox"  -->
          <h2>Reseñas</h2>
          <label for="toggle-reviews" class="toggle-reviews">Ver reseñas</label>
          <input type="checkbox" id="toggle-reviews" class="toggle-reviews-checkbox">
          <div class="reviews-container">
            <h3>Carlos Grimal</h3>
            <p>Gran servicio, la mejor peluquería en la que he estado.</p>
          </div>
        </section>
~~~







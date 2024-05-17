# arquitectura
Página web de arquitectura, aplicando CSS Grid, Flexbox, animaciones, object-fit, Media queries y Estilo Mobile first. 

#Notas Interesantes.

#Uso del Pseudocodigo Before.

.telefono {
    display: flex;
}

.telefono::before {
    content: ' ';                                      /* Indicamos que va a ir algo */
    background-image: url(../img/telefono.png);
    width: 3rem;
    height: 3rem;
    display: block;
    background-repeat: no-repeat;
    background-position: center center;
    margin-right: 1rem;
}

#Agregar un telefono como link para marcar.

< a class="telefono" href="tel:01-800-0000-000">01-800-0000-000</>
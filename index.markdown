---
layout: custom
title: Boda de María y Emilio

hero-section:
    title: ¡Ven y celebra con nosotros dos!
    subtitle: Estamos muy contentos de que estés aquí para poder contarte todos los detalles de nuestra boda.
    main-button:
        href: /paginas/formulario-registro.html
        text: Confirmar asistencia
    secondary-button:
        href: \#lista-hoteles
        text: Ver hoteles cercanos

mapa:
    title: Lugar de celebración
    description: La ceremonia del Sacramento del Matrimonio se celebrará en la <b>Iglesia de la Santísima Trinidad</b> de Antequera, Málaga y el posterior banquete tendrá lugar en el <b>Hotel Finca Eslava</b>.
    locations:
        - src: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3475.800642916149!2d-4.56260482384464!3d37.02269367218443!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd728fe231f2dedf%3A0x796ecf34252375aa!2sParroquia%20de%20La%20Santisima%20Trinidad%20Antequera!5e1!3m2!1ses!2ses!4v1772996917041!5m2!1ses!2ses
        - src: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3475.3113030626682!2d-4.564018323844211!3d37.03338797218157!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd728fde25ef650b%3A0xd4c347d29d5af2ec!2sHotel%20Finca%20Eslava!5e1!3m2!1ses!2ses!4v1772996964997!5m2!1ses!2ses

time-left:
    background-image: /galeria/cuenta_atras.jpg
    wedding-date: "2026-10-24T188:00:00"

dia-boda:
    title: Día de la boda
    description: Estamos encantados de compartir contigo los detalles de nuestro día especial. A continuación, encontrarás el horario de la celebración y los momentos que hemos preparado con tanto cariño para disfrutar juntos.
    events:
        - title: Ceremonia
          text: "La misa dará comienzo a las 18:00 en la glesia de la Santísima Trinidad en Antequera de Málaga."
          image: /galeria/dia-boda/iglesia.jpg
        - title: Buses al hotel
          text: "Al terminar la misa, habrá una flota de autobuses esperando para llevaros a todos al hotel."
          image: /galeria/dia-boda/autobus.jpg
        - title: Aperitivo en jardines
          text: "Comenzaremos la celebración disfrutando de un aperitivo en los jardines de la finca."
          image: /galeria/dia-boda/aperitivo.jpg
        - title: Banquete
          text: "Tras el aperitivo nos dirigiremos a la zona de banquete para disfrutar de la comida."
          image: /galeria/dia-boda/banquete.jpg
        - title: Fiesta
          text: "Esperamos que hayas cogido energía en la comida porque te queremos dándolo todo en la pista de baile."
          image: /galeria/dia-boda/fiesta-2.jpg

hoteles:
    title: Hoteles y apartamentos
    description: Para facilitar la búsqueda de alojamiento, te compartimos una selección de hoteles que quedan cerca de los puntos de recogida de los autobuses. Además, en algunos de ellos hemos conseguido un descuento específico para el fin de semana de la boda.

regalos:
    title: Participa en nuestra historia
    description: Esta sección es nuestra lista de bodas. Si quieres te la puedes saltar, porque para nosotros lo más importante es contar con tu presencia. Si de todas formas quieres hacernos un regalo para que empecemos nuestra aventura juntos, te dejamos algunas sugerencias.
    aclaracion: ¡Contribuye al regalo que quieras!
    IBAN: ES00 1111 2222 3333 4444 5555
    codigo_bic: AABBCCD2
---

{% include hero-section.html %}
{% include mapa.html %}
{% include time-left.html %}
{% include dia-boda.html %}
{% include hoteles.html %}
{% include regalos.html %}

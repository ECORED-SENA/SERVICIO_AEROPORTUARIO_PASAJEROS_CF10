<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 3
      h1 <em>Dangerous goods</em> // Mercancías peligrosas
    figure
      img(src="@/assets/template/tema-3-1.png")
    .row.mt-5
      .col-12.col-lg-10
        .row.px-5
          .col-12.bandera.bg-amarillo-usa.px-5.py-4
            figure
              img(src="@/assets/template/escudo-usa.svg" alt="Bandera USA")
            p.italic At the time of the trip, passengers carry a number of items with them to enjoy the activities on their trip. In most cases, they do not have the knowledge that these can be considered dangerous goods.
        .row.px-5
          .col-12.bandera-spain.bg-amarillo-spain.px-5.py-4
            figure 
              img(src="@/assets/template/escudo-spain.svg" alt="Bandera ESPAÑOL")
            p.mb-0  En el momento del viaje, los pasajeros llevan consigo un sinnúmero de elementos para el disfrute de las actividades en su viaje. En la mayoría de los casos, no tienen el conocimiento de que estos pueden ser considerados mercancías peligrosas.
      .col-4.col-lg-2.offset-4.offset-lg-0.align-self-center
        figure
          img(src="@/assets/template/tema-3-2.svg").w-75.margin-0-auto
    .h4.mt-5 <em>Prohibited items in luggage</em> // PObjetos prohibidos en el equipaje
    .h4.mt-5 <em>In warehouse</em> // En bodega
    .row.mt-5
      .col-10.offset-1
        figure
          img(src="@/assets/template/tema-3-3.png")
    .h4.mt-5 <em>In hand</em> // De mano
    .row.mt-5
      .col-6.offset-1
        figure
          img(src="@/assets/template/tema-3-4.png")
    .titulo-segundo.mt-5
      #t_3_1.h4 3.1	<em>Dangerous goods characteristics</em>  // Características de las mercancías peligrosas
    .row.mt-5
      .col-12.col-lg-7
        .row.px-4
          .col-12.bandera.bg-amarillo-usa.px-5.py-4
            figure
              img(src="@/assets/template/escudo-usa.svg" alt="Bandera USA")
            p.italic For safety reasons, it is important to bear in mind that some merchandise that passengers carry with them must have a special treatment or appropriate packaging. In all cases, the passenger is obliged to report the content of the items they carry in their luggage and, with this, it is possible to detect possible dangerous goods and avoid risks during flights.
        .row.px-4
          .col-12.bandera-spain.bg-amarillo-spain.px-5.py-4
            figure 
              img(src="@/assets/template/escudo-spain.svg" alt="Bandera ESPAÑOL")
            p.mb-0 Por temas de seguridad, es importante tener en cuenta que algunas mercancías que los pasajeros llevan consigo deben tener un tratamiento especial o embalaje apropiado. En todos los casos, el pasajero está obligado a informar el contenido de los elementos que lleva en su equipaje y, con esto, se pueden detectar las posibles mercancías peligrosas y evitar riesgos durante los vuelos. Existen diversos tipos de mercancías peligrosas, como son:
      .col-4.col-lg-5.offset-4.offset-lg-0.align-self-center
        figure
          img(src="@/assets/template/tema-3-5.png")
    ol.lista-ol--cuadro.mt-5
      li 
        .lista-ol--cuadro__vineta.secundario
          span a
        .h4 <em>Dangerous goods classes</em> // Clases de mercancías peligrosas
    .row.mt-5
      .col-12.bandera.bg-amarillo-usa.px-5.py-4
        figure
          img(src="@/assets/template/escudo-usa.svg" alt="Bandera USA")
        p.italic Dangerous goods are categorized into nine hazard classes that describe different types of risks. 
    .row
      .col-12.bandera-spain.bg-amarillo-spain.px-5.py-4
        figure 
          img(src="@/assets/template/escudo-spain.svg" alt="Bandera ESPAÑOL")
        p.mb-0 Las mercancías peligrosas se clasifican en nueve clases de peligro que describen diferentes tipos de riesgos.
    .row.mt-5
      .col-12
        .tabla-a.color-secundario.mb-5 
          table
            thead
              tr.bg-secundario.text-center
                th.py-3.w-15
                  .h4 Class // Clase
                th.py-3 
                  .h4 DESCRIPTION // DESCRIPCIÓN
                th 
                  .h4 DEXAMPLE //  EJEMPLO
            tbody
              tr.bg-gris-claro
                td.text-center.py-4 1
                td <em>Explosives</em> // Explosivos
                td <em>Fireworks, Ammunition, Gelignite</em> // Fuegos artificiales, municiones, gelignita
              tr
                td.text-center.py-4 2.1
                td <em>Flammable Gases</em> // Gases inflamables
                td <em>Acetylene, Hydrogen LPG.</em>// Acetileno, Hidrógeno GLP 
              tr.bg-gris-claro
                td.text-center.py-4 2.2
                td <em>Non-flammable, Non-toxic gases</em> // Gases no inflamables, no tóxicos
                td <em>Nitrogen, Carbon dioxide, Refrigerant gases</em> // Nitrógeno, dióxido de carbono, gases refrigerantes
              tr
                td.text-center.py-4 2.3
                td <em>Toxic Gases</em> // Gases tóxicos
                td <em>Chlorine (gas), Ammonia</em> // Cloro (gas), Amoníaco
              tr.bg-gris-claro
                td.text-center.py-4 3
                td <em>Flammable Liquids</em> // Líquidos inflamables
                td <em>Ethanol, Methanol, Hexane</em>
              tr
                td.text-center.py-4 4.1
                td <em>Flammable Solids</em> // Sólidos Inflamables
                td <em>Sulphur</em> // Azufre
              tr.bg-gris-claro
                td.text-center.py-4 4.2
                td <em>Spontaneously Combustible</em> // Espontáneamente combustible
                td <em>White Phosphorous, Activated Carbon</em> // Fósforo blanco, carbón activado
              tr
                td.text-center.py-4 4.3
                td <em>Dangerous When Wet</em>  // Peligrosa cuando está mojada
                td <em>Sodium Metal, Calcium carbide</em> // Metal de sodio, carburo de calcio
              tr.bg-gris-claro
                td.text-center.py-4 5.1
                td <em>Oxidizing Substances</em> // Sustancias oxidantes
                td <em>Sodium Peroxide, Calcium Hypochlorite (Pool Chlorine)</em> // Peróxido de sodio, hipoclorito de calcio (cloro de piscina)  
              tr
                td.text-center.py-4 5.2
                td <em>Organic Peroxide</em> // Peróxido orgánico
                td <em>Methyl Ethyl Ketone Peroxide</em> // Peróxido de metiletilcetona
              tr.bg-gris-claro
                td.text-center.py-4 6.1
                td <em>Toxic Substances</em> // Sustancias toxicas
                td <em>Sodium Cyanide</em> // Cianuro de sodio
              tr
                td.text-center.py-4 6.2
                td <em>Infectious Substance</em> // Sustancia infecciosa
                td <em>Clinical or Medical Waste</em> // Residuos clínicos o médicos
              tr.bg-gris-claro
                td.text-center.py-4 7
                td <em>Radioactive Material</em> // Material radioactivo
                td <em>Tritium</em> // Tritio
              tr
                td.text-center.py-4 8
                td <em>Corrosives</em> // Corrosivas
                td <em>Hydrochloric Acids, Sodium Hydroxide</em> // Ácido clorhídrico, hidróxido de sodio
              tr.bg-gris-claro
                td.text-center.py-4 9
                td <em>Miscellaneous Dangerous Goods</em> // Mercancías peligrosas diversas
                td <em>Asbestos, Dry Ice</em> // Amianto, hielo seco
    ol.lista-ol--cuadro.mt-5
      li 
        .lista-ol--cuadro__vineta.secundario
          span b
        .h4 <em>Dangerous goods diamond signs</em> // Señales con forma de rombo para mercancías peligrosas
    .row.mt-5
      .col-12.bandera.bg-amarillo-usa.px-5.py-4
        figure
          img(src="@/assets/template/escudo-usa.svg" alt="Bandera USA")
        p.italic Diamonds on dangerous goods labels are used in packaging where dangerous goods are transported or may be stored.
    .row
      .col-12.bandera-spain.bg-amarillo-spain.px-5.py-4
        figure 
          img(src="@/assets/template/escudo-spain.svg" alt="Bandera ESPAÑOL")
        p.mb-0 Las etiquetas con forma de rombo para las mercancías peligrosas se utilizan en embalajes donde se transportan o pueden almacenarse mercancías peligrosas.]
    .row.mt-5
      .col-10.offset-1
        figure
          img(src="@/assets/template/tema-3-6.png", alt="Texto que describa la imagen")
    ol.lista-ol--cuadro.mt-5
      li 
        .lista-ol--cuadro__vineta.secundario
          span c
        .h4 <em>No dangerous goods on the aircraft</em> // No se permiten mercancías peligrosas en la aeronave
    .row.mt-5
      .col-12.col-lg-7
        .row.px-4
          .col-12.bandera.bg-amarillo-claro.px-5.py-4
            figure
              img(src="@/assets/template/escudo-usa.svg" alt="Bandera USA")
            p.italic Many common items used every day at home or workplace may seem harmless. However, when transported on the aircraft, they can be very dangerous. During the flight, variation in temperature and pressure can cause items to leak, generate toxic fumes or start a fire. 
        .row.px-4
          .col-12.bandera-spain.bg-amarillo-spain.px-5.py-4
            figure 
              img(src="@/assets/template/escudo-spain.svg" alt="Bandera ESPAÑOL")
            p.mb-0  Muchos artículos comunes que se usan todos los días en el hogar o en el lugar de trabajo pueden parecer inofensivos. Sin embargo, cuando se transportan en avión, pueden ser muy peligrosos. Durante el vuelo, las variaciones de temperatura y de presión pueden hacer que los elementos goteen, generen humo tóxico o inicien un incendio.
      .col-4.col-lg-5.offset-4.offset-lg-0.align-self-center
        figure
          img(src="@/assets/template/tema-3-7.png")
    ol.lista-ol--cuadro.mt-5
      li 
        .lista-ol--cuadro__vineta.secundario
          span d
        .h4 <em>Items that need special treatment or appropriate packaging</em> // Elementos que necesitan un tratamiento especial o embalaje apropiado
    figure.mt-5
      img(src="@/assets/template/tema-3-8.png", alt="Texto que describa la imagen")
    p.mt-5 <em>Some of such items can be:</em> // Algunos de tales productos pueden ser:
    .row.mt-5
      .col-12.bandera.bg-amarillo-claro.px-5.py-4
        figure
          img(src="@/assets/template/escudo-usa.svg" alt="Bandera USA")
        p.italic There are elements in aviation that, although they are not considered dangerous goods, must have a special handling in the packaging so that they do not represent a risk for the flight.
    .row
      .col-12.bandera-spain.bg-amarillo-spain.px-5.py-4
        figure 
          img(src="@/assets/template/escudo-spain.svg" alt="Bandera ESPAÑOL")
        p.mb-0 Existen en aviación elementos que, si bien no son considerados mercancías peligrosas, deben tener un manejo especial en el embalaje para que así no representen un riesgo para el vuelo.
    .row.mt-5
      .col-10.offset-1
        .tarjeta.bg-amarillo-deg.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/template/tema-3-9.svg" alt="Texto que describa la imagen").w-50.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Elementos de tratamiento especial
                  p.text-small Para conocer y familiarizarse con algunos de tales productos que requieren un tratamiento o embalaje especial, descargue el siguiente documento 
                .col-sm-auto
                  a.boton.color-acento-botones.text-white(:href="obtenerLink('/downloads/Elementos_de_tratamiento_especial.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download



</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass" scoped></style>

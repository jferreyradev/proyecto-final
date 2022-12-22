<template>
  <div>
   <base-lista-productos  v-bind:productos="suculentas" />
  </div>
</template>

<script>
// @ is an alias to /src
import BaseListaProductos from '@/components/BaseListaProductos.vue'

export default {
  name: 'ProductosView',
  components: {
    BaseListaProductos
  },
  data() {
    return {
      suculentas: [
        {
          nombre: "Mala madre",
          descripcion:
            "Así se le denomina también a este tipo de suculenta, no sólo a la otra planta de interior. Ésta suele tener hojas ligeras, delgadas y largas que verás crecer increíblemente rápido. Es por ello que los hijitos se reproducen si están en espacios luminosos. Además, en las puntas nacen algunas florecitas que se transforman —en ocasiones— en más hojitas luciendo aún más amplias.",
          breve: "",
          precio: "",
          imagen: "mala_madre.webp",
        },
        {
          nombre: "Madre perla",
          descripcion:
            "Esta suculenta no alcanza los 20 cm de altura, pero genera ramificaciones que, en definitiva, la harán lucir increíblemente larga o frondosa. Es tan rápida que puedes cortar algunos bebés y propagarlos a otros lados.De igual manera, puedes colocar la madreperla en una maceta amplia para que al crecer se vayan aferrando las ramas en la tierra.",
          breve: "",
          precio: "",
          imagen: "madre_perla.jpg",
        },
        {
          nombre: "Hoya",
          descripcion:
            "Este tipo de suculenta crece rápidamente ya que suele ser colgante. No obstante, los expertos le dan forma hacia arriba con ganchos y la mantienen firme; así crecen hasta 30 cm en menos de un año y por ello, tendrás que cortarla y reproducirla aún mejor o bien, si mantienes las ramas en agua conseguirás otro tipo de planta.",
          breve: "",
          precio: "",
          imagen: "hoya.jpg",
        },
        {
          nombre: "Castillo de hadas",
          descripcion:
            "La ventaja de este tipo de suculenta es que se asemeja un cactus y por eso crece fuerte y firme hacia arriba como uno, pero se expande en ramificaciones como las suculentas en sí. Así que es muy fácil de que crezca y lo hace muy estrepitosamente, así que si quieres una suculenta alocada y bella, ésta es la que necesitas.",
          breve: "",
          precio: "",
          imagen: "castillo_hadas.jpg",
        },
        {
          nombre: "Echeveria",
          descripcion:
            "Éste es uno de los tipos de suculenta más comunes, ya que es popular y afortunadamente crece, porque en realidad es común y muy amplia. Al crecer solita y rápido, se reproduce muy velozmente, por lo que, si pierde alguna hoja, puedes reproducirla fácilmente y además, tiene bebés entre hojas.",
          breve: "",
          precio: "",
          imagen: "castillo_hadas.jpg",
        },
      ],
    };
  },
}
</script>
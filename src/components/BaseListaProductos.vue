<template>
  <div class="container">
    <div class="row">
      <div class="col-lg-10 col-xl-9 mx-auto">
        <div
          class="card flex-row my-5 border-0 shadow rounded-3 overflow-hidden"
        >
          <div class="card-body p-4 p-sm-5">
            <h5 class="card-title text-center mb-5 fw-light fs-5">
              Lista de productos
            </h5>
            <ul class="list-group">
              <li
                class="list-group-item"
                v-for="(item, i) in productos"
                :key="i"
              >
                <div class="card" style="width: 18rem">
                  <img
                    class="card-img-top"
                    :src="item.imagen"
                    :alt="item.nombre"
                  />
                  <div class="card-body">
                    <h5 class="card-title">{{ item.nombre }}</h5>
                    <p class="card-text">{{ item.descripcion }}</p>
                    <a href="#" class="btn btn-primary">Agregar a carrito</a>
                  </div>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  nombre: "BaseListaProductos",
  props: {
    productos: Array,
  },
};
</script>

<style>
</style>
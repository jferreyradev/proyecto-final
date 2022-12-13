<template>
  <div class="container">
    <div class="row">
      <div class="col-lg-10 col-xl-9 mx-auto">
        <div
          class="card flex-row my-5 border-0 shadow rounded-3 overflow-hidden"
        >
          <div class="card-img-left d-none d-md-flex"></div>
          <div class="card-body p-4 p-sm-5">
            <h5 class="card-title text-center mb-5 fw-light fs-5">
              Registro de usuario
            </h5>
            <form>
              <div class="form-floating mb-3">
                <input
                  type="text"
                  class="form-control"
                  id="floatingInputUsername"
                  placeholder="name"
                  required
                  autofocus
                  v-model="nombre"
                />
                <label for="floatingInputUsername">Nombre completo</label>
              </div>

              <div class="form-floating mb-3">
                <input
                  type="email"
                  class="form-control"
                  id="floatingInputEmail"
                  placeholder="name@example.com"
                  v-model="email"
                />
                <label for="floatingInputEmail">Email</label>
              </div>

              <hr />

              <div class="form-floating mb-3">
                <input
                  type="password"
                  class="form-control"
                  id="floatingPassword"
                  placeholder="Password"
                  v-model="password"
                />
                <label for="floatingPassword">Password</label>
              </div>

              <div class="form-floating mb-3">
                <input
                  type="password"
                  class="form-control"
                  id="floatingPasswordConfirm"
                  placeholder="Confirm Password"
                  v-model="confirmpass"
                />
                <label for="floatingPasswordConfirm">Confirma Password</label>
              </div>

              <button type="button" class="btn btn-primary btn-block mb-4">
                Registrar
              </button>

              <a class="d-block text-center mt-2 small" href="#"
                >¿Ya tiene una cuenta? Ingrese</a
              >
              <hr class="my-4" />
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BaseRegistroLogin",
  data(){
    return {
        email:'',
        password:'',
        nombre:'',
        confirmpass:''
    }
  },
  methods:{
    
  }
};
</script>

<style>
</style>
<template>
  <section class="container-fluid">
    <section class="row justify-content-center">
      <section class="col-12 col-sm-6 col-md-3">
        <form class="form-container">
          <p class="h4">Sign in</p>
          <div class="mb-3">
            <input
              type="email"
              class="form-control"
              id="exampleInputEmail1"
              aria-describedby="emailHelp"
              placeholder="Email Id"
            />
          </div>
          <div class="mb-3">
            <input
              type="password"
              class="form-control"
              id="exampleInputPassword1"
              placeholder="Password"
            />
          </div>
          <p class="forgot-password text-right mt-2 mb-4">Forgot password</p>
          <button class="btn btn-custom" type="button">Sign In</button>
          <span style="padding-left: 60px"
            ><button type="button" class="btn btn-custom-1">
              Sign Up
            </button></span
          >
        </form>
      </section>
    </section>
  </section>
</template>

<style scoped>
.form-container {
  position: absolute;
  top: 15vh;
  padding: 30px;
  border: 1px solid;
  border-radius: 5px;
  box-shadow: 1px 1px;
}
p.h4 {
  font-weight: 300;
}
.btn-custom {
  color: #fff;
  background-color: #5f2646;
  border-color: #5f2646;
}
.btn-custom-1 {
  color: #5f2646;
  background-color: #fff;
  border-color: #5f2646;
}
</style>

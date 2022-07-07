<template>
  <div class="container">
  <body>
    <main role="main" class="container my-auto">
      <div class="row">
        <div id="login" class="col-lg-4 offset-lg-4 col-md-6 offset-md-3col-12">
          <h2 class="text-center">Bienvenido</h2>
          <form>
            <div class="form-group">
              <label for="correo">Correo</label>
              <input id="correo" name="correo" class="form-control" type="email" placeholder="Correo electrónico">
            </div>
            <br>
            <div class="form-group">
              <label for="password">Contraseña</label>
              <input id="password" name="password" class="form-control" type="password" placeholder="Contraseña">
            </div>
            <br><br>
            <button type="submit" class="btn btn-primary mb-2">Entrar</button>
            <br>
            <a href="#">Contraseña olvidada</a>
          </form>
        </div>
      </div>
    </main>
  </body>
  </div>
</template>

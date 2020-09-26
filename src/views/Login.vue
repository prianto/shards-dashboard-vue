<template>
  <form class="form-signin text-center">
    <d-link class="nav-link mb-3" :to="{ name: 'index' }">
      <img
        class="mx-auto "
        src="@/assets/images/shards-dashboards-logo.svg"
        alt="Shards Dashboard"
        width="72"
        height="72"
      />
    </d-link>

    <h1 class="h3 mb-4">Shards Dashboard</h1>

    <label for="inputEmail" class="sr-only">Email address</label>

    <input
      type="email"
      id="inputEmail"
      class="form-control rounded-0"
      placeholder="Email address"
      required
      autofocus
    />

    <label for="inputPassword" class="sr-only">Password</label>

    <input
      type="password"
      id="inputPassword"
      class="form-control rounded-0"
      placeholder="Password"
      required
    />

    <div class="checkbox text-left mb-3">
      <label><input type="checkbox" value="remember-me" /> Remember me</label>
    </div>

    <d-link
      class="btn btn-lg btn-primary btn-block rounded-0"
      :to="{ name: 'home' }"
    >
      Sign In
    </d-link>

    <p class="mt-4 text-muted">
      Copyright &copy; 2018 DesignRevision
    </p>
  </form>
</template>

<style lang="scss" scoped>
.form-signin {
  width: 100%;
  max-width: 330px;
  padding: 15px;
  margin: auto;

  button {
    text-transform: uppercase;
  }

  .checkbox {
    font-weight: 400;
  }

  .form-control {
    position: relative;
    box-sizing: border-box;
    height: auto;
    padding: 10px;
    font-size: 16px;

    &:focus {
      z-index: 2;
    }
  }

  input[type='email'] {
    margin-bottom: -1px;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0;
  }

  input[type='password'] {
    margin-bottom: 10px;
    border-top-left-radius: 0;
    border-top-right-radius: 0;
  }
}
</style>

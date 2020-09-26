<template>
  <div class="cover-container d-flex w-100 h-100 p-3 mx-auto flex-column">
    <header class="masthead mb-auto">
      <div class="inner">
        <h3 class="masthead-brand">Shards Dashboard</h3>
        <nav class="nav nav-masthead justify-content-center">
          <a class="nav-link" href="#">Home</a>
          <a class="nav-link" href="#">Features</a>
          <a class="nav-link" href="#">Contact</a>
        </nav>
      </div>
    </header>

    <main role="main" class="inner cover">
      <h1 class="cover-heading mb-4">Lorem Ipsum Dolor sit Amet</h1>
      <p class="lead">
        Aliquam pretium placerat nibh vel lacinia. Sed at lorem in velit
        hendrerit rutrum quis at sem. Mauris rutrum purus non metus pulvinar,
        quis euismod felis pharetra.
      </p>
      <p class="lead">
        <d-link
          class="btn btn-lg btn-primary rounded-0"
          :to="{ name: 'login' }"
        >
          Getting Started
        </d-link>
      </p>
    </main>

    <footer class="mastfoot mt-auto">
      <div class="inner">
        <p>
          Copyright &copy; 2018 DesignRevision
        </p>
      </div>
    </footer>
  </div>
</template>

<style lang="scss" scoped>
/*
 * Base structure
 */
.cover-container {
  max-width: 42em;

  /*
   * Header
   */
  .masthead {
    margin-bottom: 2rem;
  }

  .masthead-brand {
    margin-bottom: 0;
  }

  .nav-masthead .nav-link {
    padding: 0.25rem 0;
    background-color: transparent;
    border-bottom: 0.25rem solid transparent;
  }

  .nav-masthead .nav-link:hover,
  .nav-masthead .nav-link:focus {
    border-bottom-color: rgba(255, 255, 255, 0.25);
  }

  .nav-masthead .nav-link + .nav-link {
    margin-left: 1rem;
  }

  .nav-masthead .active {
    color: #fff;
    border-bottom-color: #fff;
  }

  @media (min-width: 48em) {
    .masthead-brand {
      float: left;
    }
    .nav-masthead {
      float: right;
    }
  }

  /*
   * Cover
   */
  .cover {
    padding: 0 1.5rem;
  }
  .cover .btn-lg {
    padding: 0.75rem 1.25rem;
    font-weight: 700;
  }
}
</style>

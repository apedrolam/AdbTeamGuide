<template>
  <div id="app">
    <header>
      <h1>Adobe Practice Barcelona Guidelines</h1>
      <div class="menu">
        <ul>
          <a href=""><li>Outlook</li></a>
          <a href=""><li>Teams</li></a>
          <a href=""><li class="last">Holidays</li></a>
        </ul>
      </div>
    </header>
    <main>
      <div class="content">
        
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      entries: []
    }
  }
}
</script>

<style lang="scss">

body {
  background-color: #ebebeb;
  color: #2d2d2d;
  font-family: Arial;
  margin: 0 auto;

  header {
    color: #ebebeb;
    background-color: #2d2d2d;

    h1 {
      width: 50%;
      display: inline;
    }

    .menu {
      width: 50%;
      display: inline-block;

      a {
        text-decoration: none;
        color: #ebebeb;

        li {
          display: inline-block;
          margin-right: 20px;

          &.last {
            margin-right: 0;
          }
        }
      }
    }
  }
}

</style>

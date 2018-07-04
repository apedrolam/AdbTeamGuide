<template>
  <div id="app">
    <header>
      <h1>Adobe Practice Barcelona Guidelines</h1>
      <div class="menu">
        <ul>
          <a class="menu-list" href=""><li>Outlook</li></a>
          <a class="menu-list" href=""><li>Teams</li></a>
          <a class="menu-list menu-list_last" href=""><li>Holidays</li></a>
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
import outlook from './components/outlook.vue'
import teams from './components/teams.vue'
import holidays from './components/holidays.vue'

export default {
  name: 'app',
  data () {
    return {
      
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
    background-color: #1a4b77;

    h1 {
      padding: 20px;
      width: 50%;
      font-size: 20px;
      display: inline;
      margin-left: 50px;
    }

    .menu {
      width: 50%;
      display: inline-block;
      font-size: 20px;
      text-align: right;
      padding: 20px;
      margin-left: 80px;

      ul {
        margin: 0;
      }

      a {
        padding: 20px;
        text-decoration: none;
        color: #ebebeb;
        transition: 0.6s;

        &:hover {
          background-color: #2A76BA;
        }

        .menu-list {
          display: inline-block;
          margin-right: 20px;
        }
        .menu-list_last {
          margin-right: 0;
        }

        li {
          display: inline-block;
        }      
      }
    }
  }
}

</style>

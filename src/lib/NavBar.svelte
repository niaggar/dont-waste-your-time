<script>
  import { page } from '$app/stores';
</script>

<nav>
  <ul>
    <li><a class:active="{$page.url.pathname == '/user/pomodoro'}" href="/user/pomodoro">Pomodoro</a></li>
    <li><a class:active="{$page.url.pathname == '/user'}" href="/user">Todos</a></li>
    <li><a class:active="{$page.url.pathname == '/user/stats'}" href="/user/stats">Stats</a></li>
  </ul>
</nav>


<style>
  * {
    transition: all 0.5s ease-in-out;
  }

  nav {
    background-color: var(--gray-2);
    border-bottom: 2px solid var(--light-gray);
    overflow: hidden;
    position: sticky;
    top: 0;
    padding: 0.5rem 2rem;
  }

  nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }

  nav li {
    float: left;
  }

  nav li a {
    display: block;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }

  nav li a.active {
    font-weight: bold;
  }

</style>


<script>
  
</script>

<header class="main-header">
  <h2 class="logo">Gymmedari</h2>
  <nav class="navigation">
    <ul>
      <li class="active">Questions</li>
      <li>Diet</li>
      <li>Exercise</li>
    </ul>
  </nav>
</header>

<style>
  .main-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .main-header .navigation ul{
    display: grid;
    grid-template-columns: 100px 100px 100px;
    align-items: center;
    justify-content: center;
  }

  .main-header .navigation ul li {
    cursor: not-allowed;
    list-style: none;
  }

  .main-header .navigation ul li.active {
    color: cadetblue;
    cursor: default;
  }
</style>
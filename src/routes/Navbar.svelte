<!-- Navbar.svelte -->
<script>
    let links = ["About", "Services", "Portfolio", "Contact"];
  </script>
  
  <style>
    .navbar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px;
      background-color: #333;
    }
  
    .logo {
      font-size: 2rem;
      font-weight: bold;
      color: #fff;
    }
  
    .links {
      display: flex;
      list-style: none;
    }
  
    .links li {
      margin-left: 20px;
    }
  
    .links a {
      text-decoration: none;
      color: #fff;
    }
  </style>
  
  <nav class="navbar">
    <div class="logo">Neteor</div>
    <ul class="links">
      {#each links as link}
        <li><a href="#">{link}</a></li>
      {/each}
    </ul>
  </nav>
  
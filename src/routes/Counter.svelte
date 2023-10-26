<!-- Counter.svelte -->
<script>
    import { onMount } from "svelte";
  
    let projects = 0;
    let clients = 0;
    let awards = 0;
  
    onMount(() => {
      // Simulate fetching data from an API
      setTimeout(() => {
        projects = Math.floor(Math.random() * 100);
        clients = Math.floor(Math.random() * 50);
        awards = Math.floor(Math.random() * 10);
      }, 1000);
    });
  </script>
  
  <style>
    .counter {
      display: flex;
      justify-content: space-around;
      padding: 20px;
      background-color: #222;
    }
  
    .counter-item {
      text-align: center;
      font-size: 2rem;
      color: #fff;
    }
  
  </style>
  
  <div class="counter">
      <div class="counter-item">
          <h2>{projects}</h2>
          <p>Projects</p>
      </div>
      <div class="counter-item">
          <h2>{clients}</h2>
          <p>Clients</p>
      </div>
      <div class="counter-item">
          <h2>{awards}</h2>
          <p>Awards</p>
      </div>
  </div>
  
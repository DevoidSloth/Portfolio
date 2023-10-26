<!-- Profile.svelte -->
<script>
    export let name;
    export let role;
  </script>
  
  <style>
    .profile {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 80vh;
    }
  
    .picture {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      background-color: brown;
      margin-right: 50px;
    }
  
    .info {
      font-size: 2rem;
    }
  </style>
  
  <div class="profile">
    <div class="picture"></div>
    <div class="info">
      <h1>{name}</h1>
      <p>{role}</p>
    </div>
  </div>
  
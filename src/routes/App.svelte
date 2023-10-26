<!-- App.svelte -->
<script>
    import Profile from "./Profile.svelte";
    import Navbar from "./Navbar.svelte";
    import Counter from "./Counter.svelte";
  </script>
  
  <style>
    :global(body) {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: black;
      color: white;
    }
  </style>
  
  <Navbar />
  <Profile name="John Doe" role="Web Designer" />
  <Counter />
  
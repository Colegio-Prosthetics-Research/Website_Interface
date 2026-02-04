<!-- This is where the top bar is created -->

<script>
	let { children } = $props();
	import "../app.css";
</script>
  


  <!-- This is the navigation bar presentation -->

  <style>

    /* This is the color and size of the Bar */
    nav {
      background: rgba(40, 42, 49, 0.757);
      padding: 1rem;
    }
  
    /* This the presentation of the buttons */
    ul {
      display: flex;
      list-style: none;
      align-items: center;  
      justify-content: center;  
      margin: 0;
      padding: 0;
      gap: 1.5rem;
    }
  
    /* This is the word thikness */
    a {
      text-decoration: none;
      color: #ccc;
      font-weight: 500;
    }
  
    /* This is the color that the buttons change when hovering ontop */
    a:hover {
      color: white;
    }
  
    /* This the color that the buttons change when pressed */
    a:active {
      color: #534b46;
    }
  </style>



<!-- This is the control of the top bar -->
<nav>
    <ul>
        <li>
            <a href="/">Home</a>
        </li>
        <li>
            <a href="control">Control</a>
        </li>
        <li>
          <a href="/config">Config</a>
      </li>
      <li>
        <a href="/logs">Logs</a>
      </li>
    </ul>

</nav>


{@render children()}
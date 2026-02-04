<script>
	let { children } = $props();
	import "../app.css";
  </script>
  



  <!-- This is the nabigation bar -->

  <style>
    nav {
      background: rgba(40, 42, 49, 0.757);
      padding: 1rem;
    }
  
    ul {
      display: flex;
      list-style: none;
      align-items: center;  
      justify-content: center;  
      margin: 0;
      padding: 0;
      gap: 1.5rem;
    }
  
    a {
      text-decoration: none;
      color: #ccc;
      font-weight: 500;
    }
  
    a:hover {
      color: white;
    }
  
    .active {
      color: #00bfff;
      border-bottom: 2px solid #00bfff;
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

<!-- <slot /> -->
{@render children()}
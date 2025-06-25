Prueba

Si ponemos `subMaxLevel: x`, deberia auto-generarse la tabla de contenido del sidebar según las cabeceras en markdowns\
Ver [docsify](https://docsify.js.org/#/more-pages?id=table-of-contents)

```
<!-- index.html -->
<script>
  window.$docsify = {
    loadSidebar: true,
    subMaxLevel: 2
  }
</script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
```

Modificar la Cover Page: [docs](https://docsify.js.org/#/cover)

If all you want is a GitHub link, you can use this built-in Docsify config:

```
<script>
  window.$docsify = {
    repo: 'yourusername/your-repo-name'
  };
</script>
```

To add custom links (e.g. GitHub issues, app login), just add a <nav> block inside your index.html before the Docsify #app element.

```
<body>
  <!-- Top navigation bar -->
  <nav>
    <a href="https://github.com/youruser/yourrepo/issues" target="_blank">Issues</a>
    <a href="https://yourapp.com/login" target="_blank">Login</a>
  </nav>

  <!-- Docsify content container -->
  <div id="app"></div>

  <!-- Docsify scripts -->
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
</body>
```

If you want to customize the layout or align it better:

```
<style>
  nav {
    position: fixed;
    right: 20px;
    top: 20px;
    z-index: 1000;
  }

  nav a {
    margin-left: 15px;
    color: #007acc;
    text-decoration: none;
    font-weight: bold;
  }

  nav a:hover {
    text-decoration: underline;
  }
</style>
```

Que pasa si hago esto

<details>
  <summary>Toggle me!</summary>

This is the detailed content

</details>

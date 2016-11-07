
# <%= config.get('presentationTitle') %>

From the terminal, pop in:

  ```yo reveal:slide "Slide Title"```

Available options:

 ```--markdown --attributes --notes```

<% if (config.get('useMathJax')) { %>
  With MaThJaX
  $$ \int \int \sum \Psi $$
<% } %>

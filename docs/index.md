---
layout: default
---

<!-- Html Elements for Search -->
<div id="search-container" stype ="float: left;">
<input type="text" id="search-input" placeholder="searching....">
<ul id="results-container"> </ul>
</div>

<!-- Script pointing to search-script.js -->
<script src="./js/search-script.js" type="text/javascript"> </script>

<!-- Configuration -->
<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: "./search.json"
})
</script>

# Contents

> 1. [Home](./posts/home.md)
> 2. [Files List](/Files-List.md)
> 3. [Publication](/Publication.md)
> 4. [Publish-a-File](/Publish-a-File.md)
> 5. [Synchronization](/Synchronization.md)

<!-- ![Demo Image](./assets/images/download.png) -->


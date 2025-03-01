<div id="image-slider"></div>

<script type="module">
  import { createElement } from 'https://cdn.skypack.dev/react';
  import { render } from 'https://cdn.skypack.dev/react-dom';
  import ImageSlider from 'https://your-cdn-link.com/ImageSlider.js';

  document.addEventListener("DOMContentLoaded", function () {
    render(createElement(ImageSlider), document.getElementById("image-slider"));
  });
</script>

<style>
  #image-slider {
    width: 100%;
    max-width: 1200px;
    margin: auto;
  }
</style>

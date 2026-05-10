---
title: "Final Project Dashboards"
permalink: /final-project/dashboards/
---


<style>
  .tableau-wrapper {
    width: 100%;
    overflow: hidden;
  }
  .tableau-scaler {
    width: 850px;
    height: 1100px;
    transform-origin: top left;
  }
</style>

<div class="tableau-wrapper" id="tableau-outer">
  <div class="tableau-scaler" id="tableau-inner">

    <div class='tableauPlaceholder' id='viz1778369572912' style='position:relative'>
      <noscript>
        <a href='#'>
          <img alt='CRP5580_FinalProject'
               src='https://public.tableau.com/static/images/Fi/Final_17782315842430/CRP5580_FinalProject/1_rss.png'
               style='border: none' />
        </a>
      </noscript>
      <object class='tableauViz' style='display:none;'>
        <param name='host_url'             value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version'   value='3' />
        <param name='site_root'            value='' />
        <param name='name'                 value='Final_17782315842430/CRP5580_FinalProject' />
        <param name='tabs'                 value='no' />
        <param name='toolbar'              value='yes' />
        <param name='static_image'         value='https://public.tableau.com/static/images/Fi/Final_17782315842430/CRP5580_FinalProject/1.png' />
        <param name='animate_transition'   value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner'      value='yes' />
        <param name='display_overlay'      value='yes' />
        <param name='display_count'        value='yes' />
        <param name='language'             value='en-US' />
      </object>
    </div>
    <script type='text/javascript'>
      var divElement = document.getElementById('viz1778369572912');
      var vizElement  = divElement.getElementsByTagName('object')[0];
      vizElement.style.width  = '850px';
      vizElement.style.height = '1100px';
      var scriptElement = document.createElement('script');
      scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
      vizElement.parentNode.insertBefore(scriptElement, vizElement);
    </script>

  </div>
</div>

<script>
  function scaleTableau() {
    var outer = document.getElementById('tableau-outer');
    var inner = document.getElementById('tableau-inner');
    var scale = outer.offsetWidth / 850;
    inner.style.transform = 'scale(' + scale + ')';
    outer.style.height = Math.round(1100 * scale) + 'px';
  }
  scaleTableau();
  window.addEventListener('resize', scaleTableau);
</script>

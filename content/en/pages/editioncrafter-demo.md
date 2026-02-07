---
title: Edition Crafter demo
---
<!-- see documentation here: https://editioncrafter.org/guide/ -->
<div id="ec"></div>

<script type="text/javascript" src="https://www.unpkg.com/@cu-mkp/editioncrafter-umd"></script>

<script type="text/javascript">

     EditionCrafter.viewer({
         id: 'ec',
         documentName: 'LJS 225',
         iiifManifest:'https://github.com/cynthiaheider/elva/blob/main/content/_data/ljs225-test/ljs225-imgs/iiif/manifest.json',
         transcriptionTypes: {
           original: 'Original',
           code: 'Code'
         }
     });

</script>



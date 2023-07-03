---
widget: accomplishments 
widget_id: accomplishments
headless: true
weight: 70
title: Accomplishments
subtitle: null
design:
  columns: "2"  

<div class="row">
  {{ range $.Site.Data.accomplishments }}
  <div class="col-md-6">  
    <div class="card mb-3">
      ...
    </div>
  </div>
  {{ end }}
</div>

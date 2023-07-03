---
widget: accomplishments
widget_id: accomplishments
headless: true
weight: 70
title: Accomplishments
subtitle: null
design:
  columns: "1"
---

<div class="row">
  {{ range $.Site.Data.accomplishments }}
  <div class="col-md-6">
    <div class="card mb-3">
      <div class="card-body">
        <h5 class="card-title">{{ .name }}</h5>
        <h6 class="card-subtitle mb-2 text-muted">{{ .time }}</h6>
        <p class="card-text">{{ .description }}</p>
        <p class="card-text"><small class="text-muted">{{ .venue }}</small></p>
      </div>
    </div>
  </div>
  {{ end }}
</div>

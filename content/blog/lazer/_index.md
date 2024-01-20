---
title: "Categorias"
category_title: "Lazer"
---
{{ range where .Site.RegularPages "Params.categories" "in" "categoria-1" }}
  ### [{{ .Title }}]({{ .Permalink }})
  {{ .Summary }}
{{ end }}
---
title: "Categorias"
category_title: "Raças"
---
{{ range where .Site.RegularPages "Params.categories" "in" "categoria-1" }}
  ### [{{ .Title }}]({{ .Permalink }})
  {{ .Summary }}
{{ end }}
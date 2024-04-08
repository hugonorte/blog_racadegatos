---
title: "Categorias"
category_title: "Adoção"
---
{{ range where .Site.RegularPages "Params.categories" "in" "categoria-1" }}
  ### [{{ .Title }}]({{ .Permalink }})
  {{ .Summary }}
{{ end }}
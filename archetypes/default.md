---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
p: {{ add 100 (len (where .Site.Pages "Type" "==" "page")) }}
---


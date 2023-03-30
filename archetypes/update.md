---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
p: {{ add 200 (len (where .Site.RegularPages "Section" "==" "update")) }}
---


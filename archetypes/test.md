{{- $v := getenv "version" -}}
---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
---
```sh
{{$v}}
```

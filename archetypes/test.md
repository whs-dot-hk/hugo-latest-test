{{- $v := getenv "version" -}}
---
title: "KeepassXC {{$v}} Released"
date: {{ .Date }}
tags:
  - KeepassXC
  - Releases
---
[KeepassXC][keepassxc] {{$v}} is out. Download with the following command

```sh
cd ~/Downloads
curl -OL https://github.com/keepassxreboot/keepassxc/releases/download/{{$v}}/KeePassXC-{{$v}}-x86_64.AppImage
{{$v}}
```

[keepassxc]: https://github.com/keepassxreboot/keepassxc

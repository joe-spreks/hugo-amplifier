---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
url: '{{ .File.ContentBaseName }}'
draft: true
---

+++
date = {{ .Date | dateFormat "2006-01-02" }}
lastmod = {{ .Date | dateFormat "2006-01-02" }}
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++

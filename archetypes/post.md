+++
title = "{{ replace .TranslationBaseName "-" " " | title }}"
date = {{ .Date }}
description = "This text was generated using the After Dark post archetype."
draft = true
toc = false
categories = ["hacking"]
tags = ["after", "dark"]
owner = "{{ .Site.Params.author | default .Site.Title }}"
date = "{{ now.Format "2006" }}"
license = "cc-by-nc-sa-4.0"
+++

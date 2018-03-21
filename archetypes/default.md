---
title: "{{ replace .Name "-" " " | title }}" # Pas aan naar titel
date: {{ .Date }} # controleer datum/tijd
type: post
image: link_naar_plaatje
draft: true  # zet op 'false' als je klaar bent
categories:  # Aanpassen (hou deze vorm aan, gebruik geen tabs, alleen spaties)
  - Voorbeeld
  - Voorbeeld2
tags:
  - tag1
  - tag2
---

Tekst komt hier
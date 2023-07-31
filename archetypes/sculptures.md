---
title: "{{ replace .Name "-" " " | title }}"
layout: page
media: 
event: 
competition: 
awards:
year: {{ .Date | time.Format "2006" }}
team_members:
  - Eric Hutchinson
image: 
---
---
title: {{ .Name | humanize | title }}
date: "{{ .Date }}"
url: "/meetups/{{ .Dir }}"
slides: ""
record: ""
outputs:
  - Calendar
---
Temat dnia: {{ .Name | humanize | title}}

Nasze meetupy to spotkania na temat infrastruktury, automatyzacji, chmur i procesów wytwarzania oprogramowania.

Każde spotkanie składa się z głównej prezentacji (~45 minut) oraz dyskusji, w trakcie której można porozmawiać o prezentacji, podzielić się znaleziskiem albo udostępnić ekran i pokazać coś ciekawego (~45 minut)

Spotkania są całkowicie online, do dołączenia nie potrzeba żadnej rejestracji.
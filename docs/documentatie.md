---
layout: page-with-side-nav
title: Documentatie StUF-BG
folder_files:
  - title:  RSG Basisgegevens 202 deel I (pdf)
    path: documenten/RSG_Basisgegevens_2.02_deel_II_(in_gebruik).pdf
    group: 202
    versie: 2.02
    status: Definitief
    omschrijving: 
    datum: 
  - title:  RSG Basisgegevens 202 deel II (pdf)
    path: documenten/RSG_Basisgegevens_2.02_deel_I_(in_gebruik).pdf
    group: 202
    versie: 2.02
    status: Definitief
    omschrijving: 
    datum: 
  - title:   Wijzigingen RSGB 2.02 (pdf)
    path: documenten/Wijzigingen_RSGB_2.02.pdf
    group: 202
    versie: 2.02
    status: Definitief
    omschrijving: 
    datum: 
---

# Documentatie

## RSGB 2.02

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 202 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

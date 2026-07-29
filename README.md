# valueforge-reports

Static host for ValueForge audit reports. Written to by the ValueForge service.

Reports live at `/r/<id>.html` with unguessable ids. Every report carries a
`noindex, nofollow` meta tag and this repo serves a blanket-disallow robots.txt,
so audits never end up in search results.

Do not put anything private here. It is a public repo.

# Score de visibilité IA — page événement

Page publique (QR code) : collecte des coordonnées puis redirection vers le score express `miascore.com/score?domain=…`.
Leads stockés dans Supabase (projet `maveilleia-leads-evenements`, table `leads`, insertion seule pour le public).
Paramètre `?e=<code-evenement>` pour tracer l'événement d'origine.

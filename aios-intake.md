# AIS-OS Intake

This is the source-of-truth file for your AIOS. Fill it in by typing, voice-pasting (Wispr Flow / OS dictation), or running `/onboard` for a guided conversation. Whichever mode, this file is what `/onboard` reads to scaffold your Day-1 setup.

**Hard cap: 7 questions.** Each answerable in under 60 seconds. Don't overthink — you can edit and re-run `/onboard` any time.

---

## Q1 — Who are you, what do you sell, who do you sell it to?

Identity, offer, ICP. One paragraph each is fine.

```
Identité : RABARIJAONA Harena Juan — consultant IA pour dirigeants et chefs d'entreprise.

Offre : L'Activation AIOS — une session 60 minutes qui connecte l'expertise métier du client à un système IA opérationnel, avant la fin de l'appel. Prix : 300–500 €/session. Offre d'entrée (Rung 0) vers un ladder : Audit IA (1 500–3 000 €) → Déploiement sur mesure (5 000–15 000 €) → Retainer mensuel (1 000–3 000 €/mois).

ICP : Dirigeants / chefs d'entreprise submergés par le bruit IA — peur de prendre du retard, paralysie face à l'abondance d'outils, concurrents qui automatisent. Ciblage sectoriel : coachs, cabinets comptables, agences marketing, artisans premium. Pouvoir d'achat accessible (300–500 € psychologiquement accessible). Canaux : LinkedIn, BNI, chambres de commerce, newsletters sectorielles.
```

---

## Q2 — Paste 1-2 things you've written recently. Don't edit them.

An email, a LinkedIn post, a DM, a doc — anything that sounds like you when you're not trying. **Paste verbatim.** Do not type these mid-conversation with Claude — chat-shaped samples are worse than no samples (voice contamination).

```
Sample 1 — LinkedIn post (EN)

Madagascar's digital challenge used to be about access. It isn't anymore, at least not only.

I was at a World Bank roundtable a couple weeks ago with digital users, entrepreneurs, and people building pieces of the ecosystem. 
The conversation was more grounded than these things usually are. 
Less about what the roadmap should look like, more about what actually happens when someone in Antananarivo tries to run a small business online.

A few things I'm still chewing on:

Mobile money is working. Madagascar has built something real there. The question now is whether that infrastructure can do more than payments — support small businesses, extend financial access, anchor other digital services.

Skills are the actual bottleneck. More people have access to digital tools than can use them to generate income. That gap is wider than the connectivity gap, and it's not closing as fast.

Trust matters more than it gets credit for. When data protection fails or a digital service scams someone, adoption doesn't just slow down — it reverses. Cybersecurity and digital literacy aren't nice-to-haves.

On AI: the honest question isn't whether Madagascar will use these tools, but whether it will shape them. Importing ready-made solutions and building locally relevant ones lead to very different outcomes ten years from now.

None of this is simple, and the roundtable didn't pretend otherwise. What I appreciated was the focus on what's actually happening on the ground rather than what the indicators say should be.

Thanks to Michel Rogy, Mehnaz Safavian, and the The World Bank Group team for making room for that kind of conversation.

Heureux d'avoir pu contribuer à cette réflexion collective sur l'avenir numérique de Madagascar.
```

```
Sample 2 — Message de recrutement (FR)

Tu mets les gens à l'aise sans effort. Dans un événement, tu es naturellement celle ou celui vers qui les gens se tournent pour trouver leur chemin, et tu aimes ça.

On recrute un responsable pour la commission Accueil & Relations Participants : enregistrement des délégués, orientation sur place, gestion de l'ambiance dès les premières minutes.

C'est le premier rôle visible de l'événement. Et en 3 jours, tu passes par tous les délégués nationaux. Ce réseau-là ne se construit pas autrement.

Si tu te reconnais dans ce profil, envoie-moi un message en privé.
```

---

## Q3 — What are your 2-3 biggest priorities for the next 90 days?

Quarterly priorities. Not yearly aspirations. Things that, if not done by July, would make you say "I wasted Q2."

```
1. Installer l'AIOS gratuitement chez 3 personnes de mon réseau — obtenir de bonnes références/recommandations et des preuves concrètes que la solution marche.
2. Convertir cette preuve sociale en premiers clients payants (L'Activation AIOS, 300–500 €/session).
```

---

## Q4 — Where does revenue actually land, and where is it tracked?

Multiple answers OK. Stripe? Skool? GoHighLevel? QuickBooks? A spreadsheet?

```
Réception : Orange Money (principal, clients Madagascar). Clients internationaux : TBD — Orange Money ou BMOI (banque locale).
Suivi : Notion (espace à créer — pas encore connecté).
```

---

## Q5 — Where do you talk to customers, your team, and the outside world day-to-day?

Email (which one — Gmail / Outlook)? Slack? Teams? DMs (Skool / Discord / iMessage)? Phone?

```
Email (Gmail — yoan.rab@gmail.com), WhatsApp, LinkedIn DMs, Messenger.
```

---

## Q6 — Where do meeting recordings, notes, and important docs live?

Granola? Otter? Fireflies? Google Drive? Notion? Dropbox? A folder on your desktop you keep meaning to organize?

```
Notion, Google Drive, fichiers en local.
```

---

## Q7 — What's the one task that eats your week, and where do you currently track work?

The single biggest time-suck or recurring drudgery. Plus where tasks/projects live (ClickUp / Asana / Linear / Notion / a notebook).

```
Top pain : reformuler l'offre L'Activation AIOS pour chaque type de client selon son secteur — rédiger un message personnalisé à chaque prospect prend beaucoup de temps en phase de lancement.
Suivi des tâches : Notion (workspace business pas encore créé — à créer sous une page "Business").
```

---

When this file is filled, run `/onboard` (or re-run it) and the wizard will scaffold your Day-1 file set: `context/`, `references/voice.md`, populated `connections.md`, and a filled `CLAUDE.md`.

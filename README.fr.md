<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Dictée vocale IA pour Chrome" />
</p>

<h3 align="center">LinguaVox — Dictée Vocale IA pour Chrome · Transcription et Traduction en 21+ Langues</h3>

<p align="center">
  Appuyez sur le raccourci · parlez · relâchez · le texte s'insère automatiquement dans n'importe quel champ web<br>
  OpenAI Whisper · 21+ langues · 6 modes IA · Sous-titres en temps réel en réunion · Aucune clé API requise
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licence-MIT-blue.svg" alt="Licence" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/site%20web-linguavox-brightgreen" alt="Site Web" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Installer%20Gratuitement-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/tableau%20de%20bord-ouvrir-orange" alt="Tableau de bord" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/version-3.0.0-green" alt="Version" /></a>
</p>

---

## Qu'est-ce que LinguaVox ?

LinguaVox est une extension Chrome pour la dictée vocale et la traduction par intelligence artificielle. Appuyez sur Ctrl+Espace, parlez, relâchez — le texte transcrit apparaît immédiatement dans le champ actif : chat, e-mail, formulaire CRM, commentaire dans Jira, bloc dans Notion. L'extension utilise OpenAI Whisper pour une précision de 95%+ et GPT-4o-mini pour l'amélioration optionnelle du texte : correction grammaticale, changement de style, traduction.

Contrairement à la plupart des outils de dictée, LinguaVox ne nécessite pas de clé API OpenAI personnelle. Les utilisateurs gratuits reçoivent 20 requêtes par jour depuis le pool partagé — sans aucune configuration. Les utilisateurs avancés et les équipes peuvent connecter leur propre clé pour une utilisation illimitée.

**v3.0 — Mode Réunion :** sous-titres traduits en temps réel pour Google Meet, Zoom, Teams et tout autre appel basé sur navigateur. L'audio de l'onglet est capturé via l'API Chrome → transmis à Deepgram → les sous-titres apparaissent comme une superposition flottante.

## Comment ça fonctionne

**Avant LinguaVox :** ouvrir une application séparée → enregistrer → copier → basculer vers le navigateur → coller  
**Avec LinguaVox :**

```
1. Cliquez dans n'importe quel champ web (Slack, Gmail, Notion, Jira…)
2. Maintenez  Ctrl+Espace  →  parlez
3. Relâchez  →  le texte apparaît en ~3 secondes  ✓
```

Pas de copier-coller. Pas de changement d'application. Sur n'importe quel site.

## Où ça fonctionne

| Plateforme | Statut | Notes |
|------------|--------|-------|
| Slack (navigateur) | ✅ | Contournement de la capture clavier au niveau du navigateur |
| Gmail | ✅ | Champs de composition et de réponse |
| Notion | ✅ | Tous les blocs contenteditable |
| Jira | ✅ | Champs de problèmes, commentaires, descriptions |
| Asana | ✅ | Champs de tâches et de commentaires |
| Salesforce | ✅ | Champs de saisie CRM |
| Tout `<input>` / `<textarea>` | ✅ | Universel — tout site web |
| Tout `contenteditable` | ✅ | Compatible React, Draft.js, Quill |
| Google Docs | ⚠️ | Limité — éditeur de canevas personnalisé |

## Fonctionnalités principales

- **Aucune clé API requise** — 20 requêtes/jour gratuites via pool partagé
- **Apportez votre propre clé** — utilisation illimitée au coût OpenAI
- **Comptes d'organisation** — pool de clés partagées, gestion des membres, analyse d'utilisation
- **21+ langues** — transcription + traduction en une seule étape
- **6 modes d'amélioration IA** — correction grammaticale, style professionnel, académique, décontracté, créatif, polissage intelligent
- **Mode Réunion** — sous-titres en temps réel pour tout audio d'onglet via Deepgram
- **Confidentialité totale** — l'audio vocal n'est jamais stocké
- **Moins de 3 secondes** — du discours à l'insertion du texte
- **Précision 95%+** — OpenAI Whisper

## Modes d'amélioration IA

| Mode | Ce qu'il fait |
|------|--------------|
| Polissage intelligent | Corriger la grammaire, améliorer la clarté, préserver le sens |
| Style professionnel | Ton de communication formelle et professionnelle |
| Correction grammaticale | Corriger uniquement la grammaire et l'orthographe |
| Style créatif | Écriture vivante et captivante |
| Style décontracté | Ton conversationnel et amical |
| Style académique | Langage académique formel |

## Tarification

| Plan | Requêtes/jour | Conditions |
|------|---------------|-----------|
| Gratuit | 20 | Compte Google (connexion OAuth) |
| Apportez votre propre clé | Illimitées | Compte Google + votre clé API OpenAI |
| Organisation | Illimitées | Compte Google + clé API d'équipe partagée |

## Questions fréquentes

**LinguaVox fonctionne-t-il sur Slack ?**  
Oui. Slack intercepte les événements clavier au niveau de la page. LinguaVox enregistre le raccourci au niveau du navigateur via `chrome.commands.onCommand`, contournant la capture de Slack.

**Ai-je besoin d'une clé API OpenAI ?**  
Non. Les utilisateurs gratuits reçoivent 20 requêtes/jour du pool partagé. Ajoutez votre propre clé dans le tableau de bord pour une utilisation illimitée.

**Ma voix est-elle enregistrée ou stockée ?**  
Non. L'audio est traité en temps réel par Whisper et supprimé immédiatement. Zéro donnée vocale conservée.

**Quelles langues sont prises en charge ?**  
21+ langues : anglais, ukrainien, russe, espagnol, français, allemand, japonais, coréen, chinois, arabe, portugais, italien, polonais, néerlandais, turc, suédois, roumain, grec, tagalog, ourdou, pendjabi et plus.

## Communauté et support

| | |
|--|--|
| 📺 YouTube | [Vidéos de démonstration et tutoriels](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [Canal de la Communauté LinguaVox](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Rejoindre linguavox.slack.com](https://linguavox.slack.com) |

## Vidéos de démonstration

| Cas d'utilisation | Regarder |
|-------------------|---------|
| Gmail — rédiger des e-mails par la voix | [▶ Regarder](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — messages vocaux | [▶ Regarder](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — dictée vocale | [▶ Regarder](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — rédiger des publications par la voix | [▶ Regarder](https://youtube.com/watch?v=3WX9EmYNYjk) |
| Mode Réunion — sous-titres en temps réel | [▶ Regarder](https://youtube.com/watch?v=agcMJVPKlxE) |

## Installation

**Option A — Chrome Web Store (recommandé) :**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — cliquez sur « Ajouter à Chrome »
2. Cliquez sur l'icône LinguaVox → « Se connecter avec Google »
3. Appuyez sur Ctrl+Espace n'importe où et commencez à parler

**Option B — Installation manuelle (ZIP) :**
1. Téléchargez `linguavox-3.0.0.zip` depuis [Versions →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. Décompressez dans un dossier
3. Chrome → `chrome://extensions` → activez « Mode développeur » → « Charger l'extension non empaquetée » → sélectionnez le dossier

## Liens

| | |
|--|--|
| 🌐 Site web | https://linguavox.uk |
| 📊 Tableau de bord | https://linguavox.uk/login |
| 🔒 Politique de confidentialité | https://linguavox.uk/privacy/ |
| 🤖 Docs IA (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Support | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Licence

MIT — voir [LICENSE](LICENSE)
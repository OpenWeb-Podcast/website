---
ID: 409
post_title: 'Folge 33: Das neue Facebook und ein bisschen Google+'
author: Matthias Pfefferle
post_date: 2011-09-27 00:22:30
post_excerpt: ""
layout: post
permalink: 409/folge-33-das-neue-facebook-und-ein-bisschen-google/
published: true
enclosure:
  - https://openwebpodcast.de/mp3/openweb33.mp3
  - 1234
categories:
  - Podcast
tags:
  - API
  - Facebook
  - Google
  - Timeline
---

...und weiter geht's! Heute mal als _ClosedWebPodcast_ zu den neuen Features von Facebook und Google... Viel Spaß beim hören :)

<audio controls>
  <source src="https://openwebpodcast.de/mp3/openweb33.mp3" type="audio/mpeg">
  Ihr Browser unterstützt diesen Audio-Player nicht.
</audio>

<small>Länge: 56m, [Download MP3](https://openwebpodcast.de/mp3/openweb33.mp3)</small>

**Facebook**
* [Smart Lists](http://www.facebook.com/blog.php?post=10150278932602131)
* [Live Ticker](http://allfacebook.de/news/live-ticker-nun-fur-sehr-viele-facebook-nutzer-online)
* [Subscribe-Button](http://www.facebook.com/about/subscribe)
* f8
  * [Timeline](http://www.facebook.com/about/timeline)
  * [OpenGraph V2](http://allfacebook.de/connect/so-funktioniert-der-neue-open-graph-fur-entwickler)
  * Neue und eigene "Things"/"Verbs" erstellen
  * ["App Scrobling" -> Neue Buttons](http://www.nytimes.com/2011/09/19/business/media/facebook-is-expected-to-unveil-media-sharing-service.html)
* Strategie?
  * Wegen G+?
  * Semantic Web?
  * Motivation
  * Ontologien

**Google+**

* für alle offen
* [Neue iPhone App](https://plus.google.com/102034052532213921839/posts/JzKPakBwHQR)
* Suche
* [Hangouts with Extras](http://googleblog.blogspot.com/2011/09/google-92-93-94-95-96-97-98-99-100.html)
* APIs
* Read only API
* Hangouts API/Apps/Widgets

**Google+ API**

Link: [https://developers.google.com/+/](https://developers.google.com/+/)

* Zugriff per API Key oder per OAuth 2.0, letzteres kann mehr (Zugriff auf private Daten)
* API-Key und Co kann man sich hier holen: [https://code.google.com/apis/console/b/0/](https://code.google.com/apis/console/b/0/)
* Basis-Features: Feld-Selektionen, Batching usw.
* Zugriff auf das Profil: `https://www.googleapis.com/plus/v1/people/userId`
* URLs, Orgs, PlacesLived usw.
* geht aber nur mit Key!
* People: `https://developers.google.com/+/api/latest/people`
* Activities: `https://developers.google.com/+/api/latest/activities`
* Kurz: Einfach zu nutzen, alles JSON, ähnlich FB Graph API, aber weniger Content Types.

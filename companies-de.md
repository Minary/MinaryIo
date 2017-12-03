---
layout: page
title: Firmen
lang: de
permalink: /companies/
---

Um es als Firma besser zu machen, hier einige Tipps, mit denen man sich auch gegen Tools wie Minary wehren kann:

  - Minary greift Zielsysteme durch broadcastende Protokolle an. Gegenwärtig ist es ARP, die folgenden Protokolle werden DHCP und NDP für IPv6 sein. Diese Angriffe können auf (professionellen) Switches eliminiert werden. 

  - Es gibt keinen plausiblen Grund mehr, kein HTTPS anzubieten. [Let's Encrypt](https://letsencrypt.org/) bietet gratis Zertifikate an, die im Nu erstellt sind.
  
  - Erzwinge den Gebrauch der verschlüsselten Seite durch Verweise mittels **Permanent  Redirects** auf die HTTPS-Web-Seite.
  
  - **Verwende HTTPS flächendeckend** auf allen Systemen. Systeme können aufeinander verlinken und unverschlüsselte Systeme sind anfällig für Manipulationen. Je weniger Angriffs-Oberfläche ein Hacker erhält, um so geringer das Risiko für die User.
  
  - **Verwende HSTS** damit die User ausschliesslich verschlüsselt mit den Systemen kommunizieren. Verwende _includeSubDomains_ sowie auch _preload_.
  
  

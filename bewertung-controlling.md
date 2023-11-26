---
context-lang: @(Projekt.contextlang)
title: @(Projekt.title)
subtitle: @(Projekt.subtitle)
cover: @(Projekt.pdfCover)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
author: @(Autor.name)
---


# Einführung Controlling
@include "organisation.md"

# Bausteine des Controllings
@include "bausteine.md"

# Budgetierung
@include "bugetierung.md"

# Jahresabschluss bei offenlegungspflichtigen Unternehmen
@include "offenlegung.md"

# Auswertung des Jahresabschlusses
@include "auswertung_ja.md"

# Übungen zur Lernzielkontrolle

